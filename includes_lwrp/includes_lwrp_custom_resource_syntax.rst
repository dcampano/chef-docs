.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


The syntax for a lightweight resource is as follows:

.. code-block:: ruby

   require 'required_item'

   actions :action_name1, :action_name2, :action_name...
   default_action :action_name1
   
   attribute :attribute_name, :kind_of => 'value', :name_attribute => true
   attribute :attribute_name, :kind_of => 'value', :validation_parameter => 'value'
   ...
   attribute :attribute_name, :kind_of => 'value', :validation_parameter => 'value'

   attr_accessor :attribute, :attribute

where 

* ``require`` lists any external entities that may be required by the lightweight resources, such as a library; a lightweight resource is |ruby| and anything that can be done in |ruby| can be done in a lightweight resource
* ``:action_name1``, ``:action_name2``, and ``:action_name...`` represents a comma-delimited list of ``actions`` that are available to this lightweight resource; there must be at least one action
* ``action_name1`` is set to be the ``default_action``
* ``:attribute_name`` is the name of the property; a lightweight resource may define as many properties as necessary
* ``:kind_of => value`` specifies the |ruby| class (or an array of |ruby| classes) that are used to define this property's value
* ``:name_attribute`` is associated with one ``attribute`` to indicate which property's value will be defined by the name of the resource as it is defined in the recipe (i.e. the string that appears in front of the ``do`` block in the recipe and after the resource: ``resource_name "name_attribute" do``)
* ``:validation_parameter`` represents a comma-delimited list of validation parameters for each property
* ``attr_accessor`` allows the lightweight resource to use the ``Module`` |ruby| class to check for one (or more) named properties, such as ``:exists`` or ``:running``

For example, the ``cron_d`` lightweight resource (found in the |cookbook cron| cookbook) can be used to manage files located in ``/etc/cron.d``:

.. code-block:: ruby

   actions :create, :delete
   default_action :create

   attribute :name, :kind_of => String, :name_attribute => true
   attribute :cookbook, :kind_of => String, :default => 'cron'
   attribute :minute, :kind_of => [Integer, String], :default => '*'
   attribute :hour, :kind_of => [Integer, String], :default => '*'
   attribute :day, :kind_of => [Integer, String], :default => '*'
   attribute :month, :kind_of => [Integer, String], :default => '*'
   attribute :weekday, :kind_of => [Integer, String], :default => '*'
   attribute :command, :kind_of => String, :required => true
   attribute :user, :kind_of => String, :default => 'root'
   attribute :mailto, :kind_of => [String, NilClass]
   attribute :path, :kind_of => [String, NilClass]
   attribute :home, :kind_of => [String, NilClass]
   attribute :shell, :kind_of => [String, NilClass]

where

* the ``actions`` allow a recipe to manage entries in a |crontab| file (create entry, delete entry)
* ``:create`` is the default action
* ``:minute``, ``:hour``, ``:day``, ``:month``, and ``:weekday`` are the collection of properties used to schedule a |cron| job, assigned a default value of ``'*'``
* ``:command`` is the command that will be run (and also required)
* ``:user`` is the user by which the command is run
* ``:mailto``, ``:path``, ``:home``, and ``:shell`` are optional environment variables that do not have default value, which each being defined as an array that supports the ``String`` and ``NilClass`` |ruby| classes
