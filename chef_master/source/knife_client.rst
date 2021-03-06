=====================================================
knife client
=====================================================

.. include:: ../../includes_knife/includes_knife_client.rst

.. note:: Review the list of :doc:`common options </knife_common_options>` available to this (and all) |knife| subcommands and plugins.

bulk delete
=====================================================
.. include:: ../../includes_knife/includes_knife_client_bulk_delete.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_bulk_delete_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_bulk_delete_options.rst

Examples
-----------------------------------------------------
None.

create
=====================================================
.. include:: ../../includes_knife/includes_knife_client_create.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_create_syntax.rst

Options
-----------------------------------------------------
``-a``, ``--admin``
   Open source 11 |chef server|. |admin client| This option will have no effect when used with |chef server oec| server or Chef 12 server.

``-f FILE``, ``--file FILE``
   Write the private key to a file if the server generated one.

``--validator``
   Use to create the client as the |chef validator|. Default value: ``true``.

``-p FILE``, ``--public-key FILE``
   Set the initial default key for the client from a file on disk (cannot pass with --create-key).

``-k``, ``--prevent-keygen``
   API V1 only. Prevent server from generating a default key pair for you. Cannot be passed with --public-key.

.. note:: See :doc:`knife.rb </config_rb_knife_optional_settings>` for more information about how to add certain |knife| options as settings in the |knife rb| file.

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Create an admin client**

.. include:: ../../step_knife/step_knife_client_create_admin.rst

**Create an admin client for Enterprise Chef**

.. include:: ../../step_knife/step_knife_client_create_hosted_and_private.rst

delete
=====================================================
.. include:: ../../includes_knife/includes_knife_client_delete.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_delete_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_delete_options.rst

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Delete a client**

.. include:: ../../step_knife/step_knife_client_delete.rst

edit
=====================================================
.. include:: ../../includes_knife/includes_knife_client_edit.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_edit_syntax.rst

Options
-----------------------------------------------------
|no_options|

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Edit a client**

.. include:: ../../step_knife/step_knife_client_edit.rst

key create
=====================================================
.. include:: ../../includes_knife/includes_knife_client_key_create.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_key_create_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_key_create_options.rst

Examples
-----------------------------------------------------
None.

key delete
=====================================================
.. include:: ../../includes_knife/includes_knife_client_key_delete.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_key_delete_syntax.rst

Examples
-----------------------------------------------------
None.

key edit
=====================================================
.. include:: ../../includes_knife/includes_knife_client_key_edit.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_key_edit_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_key_edit_options.rst

Examples
-----------------------------------------------------
None.

key list
=====================================================
.. include:: ../../includes_knife/includes_knife_client_key_list.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_key_list_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_key_list_options.rst

Examples
-----------------------------------------------------
None.

key show
=====================================================
.. include:: ../../includes_knife/includes_knife_client_key_show.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_key_show_syntax.rst

Examples
-----------------------------------------------------
None.

list
=====================================================
.. include:: ../../includes_knife/includes_knife_client_list.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_list_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_list_options.rst

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**View a list of clients**

.. include:: ../../step_knife/step_knife_client_list_all.rst

.. include:: ../../step_knife/step_knife_client_list_authenticate.rst

reregister
=====================================================
.. include:: ../../includes_knife/includes_knife_client_reregister.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_reregister_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_reregister_options.rst

.. note:: See :doc:`knife.rb </config_rb_knife_optional_settings>` for more information about how to add certain |knife| options as settings in the |knife rb| file.

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Re-register a client**

.. include:: ../../step_knife/step_knife_client_reregister.rst

show
=====================================================
.. include:: ../../includes_knife/includes_knife_client_show.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_show_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_client_show_options.rst

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Show clients**

.. include:: ../../step_knife/step_knife_client_show.rst

.. include:: ../../step_knife/step_knife_client_show_json.rst
