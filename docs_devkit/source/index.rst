=====================================================
All about the |chef dk_title| ...  
=====================================================

.. include:: ../../includes_chef_dk/includes_chef_dk.rst

Getting Started
=====================================================
.. include:: ../../includes_chef/includes_chef_index.rst

.. raw:: html

   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/chef_overview.html">An Overview of Chef</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/install_dk.html">Install the Chef DK</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/getting_started.html">Getting Started with the Chef DK and Kitchen</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/ruby.html">Using Ruby</a> </br>

.. note:: See this blog post by Irving Popovetsky about running the Chef DK on Windows: https://www.chef.io/blog/2014/11/04/the-chefdk-on-windows-survival-guide/.

.. note:: The topic "Getting Started with the Chef DK and Kitchen" is a work in progress. It needs some editing, but you should be able to install the Chef DK and then configure Kitchen to build CentOS and Ubuntu instances, and then converge a node using the NTP cookbook. More sections are planned for future updates that will include more scenarios for Kitchen, new scenarios for ChefSpec, Berkshelf, and Chef policy. Feedback on the getting started page may be sent to docs@chef.io.

About Workflow
-----------------------------------------------------
.. include:: ../../includes_chef_dk/includes_chef_dk_workflow.rst

Tools
=====================================================
.. include:: ../../includes_chef_dk/includes_chef_dk_tools.rst

.. include:: ../../includes_chef_dk/includes_chef_dk_tools_main.rst

|chef dk_title| Tools
-----------------------------------------------------
The following tools are available only in the |chef dk|:

.. raw:: html

   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/ctl_chef.html">chef (executable)</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/policy.html">Policy</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/config_rb_policyfile.html">Policyfile.rb</a> </br>

|chef provisioning_title|
-----------------------------------------------------
The following resources are part of |chef provisioning| and are now available in the |chef dk|:

.. raw:: html

   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/resource_machine.html">machine</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/resource_machine_batch.html">machine_batch</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/resource_machine_execute.html">machine_execute</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/resource_machine_file.html">machine_file</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/resource_machine_image.html">machine_image</a> </br>
   
The following resources are available in the |chef dk| and may be used as part of |chef provisioning|:

.. raw:: html

   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_acl.html">chef_acl</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_client.html">chef_client</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_container.html">chef_container</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_data_bag_item.html">chef_data_bag_item</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_data_bag.html">chef_data_bag</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_environment.html">chef_environment</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_group.html">chef_group</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_mirror.html">chef_mirror</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_node.html">chef_node</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_organization.html">chef_organization</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_role.html">chef_role</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_chef_user.html">chef_user</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_private_key.html">private_key</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/resource_public_key.html">public_key</a> </br>

The following driver-specific resources are available for |amazon aws| and may be used as part of |chef provisioning|:

.. raw:: html

   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-auto-scaling-group">aws_auto_scaling_group</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-cache-cluster">aws_cache_cluster</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-cache-replication-group">aws_cache_replication_group</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-cache-subnet-group">aws_cache_subnet_group</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-dhcp-options">aws_dhcp_options</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-ebs-volume">aws_ebs_volume</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-eip-address">aws_eip_address</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-image">aws_image</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-instance">aws_instance</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-internet-gateway">aws_internet_gateway</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-key-pair">aws_key_pair</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-launch-configuration">aws_launch_configuration</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-load-balancer">aws_load_balancer</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-network-acl">aws_network_acl</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-network-interface">aws_network_interface</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-route-table">aws_route_table</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-s3-bucket">aws_s3_bucket</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-security-group">aws_security_group</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-server-certificate">aws_server_certificate</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-sns-topic">aws_sns_topic</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-sqs-queue">aws_sqs_queue</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-subnet">aws_subnet</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#aws-vpc">aws_vpc</a> </br>

The following driver-specific resources are available for |fog| and may be used as part of |chef provisioning|:

.. raw:: html

   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#fog-key-pair">fog_key_pair</a> </br>

The following driver-specific resources are available for |vagrant| and may be used as part of |chef provisioning|:

.. raw:: html

   &nbsp;&nbsp;&nbsp;   <a href="https://docs.chef.io/provisioning.html#vagrant-box">vagrant_box</a> </br>

Community Tools
-----------------------------------------------------
The following tools have been developed by members of the |chef| community. These tools are considered to be a useful part of the |chef| workflow and have been packaged as part of the |chef dk|. (They are all available independently of the |chef dk|, as well.) The use of these tools as part of your workflow is recommended, but at the same time is completely optional. Use them in the way that makes sense for your organization:

.. raw:: html

   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/berkshelf.html">Berkshelf</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/chef_vault.html">chef-vault</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/chefspec.html">ChefSpec</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/foodcritic.html">Foodcritic</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/kitchen.html">Kitchen</a> </br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/ctl_kitchen.html">kitchen (the command-line executable for Kitchen)</a> </br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/config_yml_kitchen.html">kitchen.yml (the configuration file for Kitchen)</a> </br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/plugin_kitchen_vagrant.html">kitchen-vagrant (the default driver plugin for Kitchen)</a> </br>
   &nbsp;&nbsp;&nbsp;   <a href="http://docs.chef.io/devkit/rubocop.html">RuboCop</a> </br>



.. Hide the TOC from this file.

.. toctree::
   :hidden:

   berkshelf
   chef_overview
   chef_vault
   chefspec
   config_rb_policyfile
   config_yml_kitchen
   ctl_chef
   ctl_kitchen
   foodcritic
   getting_started
   install_dk
   install_dk_windows
   kitchen
   plugin_kitchen_vagrant
   policy
   rubocop
   ruby
   serverspec
