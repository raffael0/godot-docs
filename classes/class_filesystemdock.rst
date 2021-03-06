:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the FileSystemDock.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_FileSystemDock:

FileSystemDock
==============

**Inherits:** :ref:`VBoxContainer<class_VBoxContainer>` **<** :ref:`BoxContainer<class_BoxContainer>` **<** :ref:`Container<class_Container>` **<** :ref:`Control<class_Control>` **<** :ref:`CanvasItem<class_CanvasItem>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`



Methods
-------

+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`       | :ref:`can_drop_data_fw<class_FileSystemDock_method_can_drop_data_fw>` **(** :ref:`Vector2<class_Vector2>` arg0, :ref:`Variant<class_Variant>` arg1, :ref:`Control<class_Control>` arg2 **)** const |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                          | :ref:`drop_data_fw<class_FileSystemDock_method_drop_data_fw>` **(** :ref:`Vector2<class_Vector2>` arg0, :ref:`Variant<class_Variant>` arg1, :ref:`Control<class_Control>` arg2 **)**               |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Variant<class_Variant>` | :ref:`get_drag_data_fw<class_FileSystemDock_method_get_drag_data_fw>` **(** :ref:`Vector2<class_Vector2>` arg0, :ref:`Control<class_Control>` arg1 **)**                                           |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                          | :ref:`navigate_to_path<class_FileSystemDock_method_navigate_to_path>` **(** :ref:`String<class_String>` arg0 **)**                                                                                 |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Signals
-------

.. _class_FileSystemDock_signal_display_mode_changed:

- **display_mode_changed** **(** **)**

----

.. _class_FileSystemDock_signal_file_removed:

- **file_removed** **(** :ref:`String<class_String>` file **)**

----

.. _class_FileSystemDock_signal_files_moved:

- **files_moved** **(** :ref:`String<class_String>` old_file, :ref:`String<class_String>` new_file **)**

----

.. _class_FileSystemDock_signal_folder_moved:

- **folder_moved** **(** :ref:`String<class_String>` old_folder, :ref:`String<class_String>` new_file **)**

----

.. _class_FileSystemDock_signal_folder_removed:

- **folder_removed** **(** :ref:`String<class_String>` folder **)**

----

.. _class_FileSystemDock_signal_inherit:

- **inherit** **(** :ref:`String<class_String>` file **)**

----

.. _class_FileSystemDock_signal_instance:

- **instance** **(** :ref:`PackedStringArray<class_PackedStringArray>` files **)**

Method Descriptions
-------------------

.. _class_FileSystemDock_method_can_drop_data_fw:

- :ref:`bool<class_bool>` **can_drop_data_fw** **(** :ref:`Vector2<class_Vector2>` arg0, :ref:`Variant<class_Variant>` arg1, :ref:`Control<class_Control>` arg2 **)** const

----

.. _class_FileSystemDock_method_drop_data_fw:

- void **drop_data_fw** **(** :ref:`Vector2<class_Vector2>` arg0, :ref:`Variant<class_Variant>` arg1, :ref:`Control<class_Control>` arg2 **)**

----

.. _class_FileSystemDock_method_get_drag_data_fw:

- :ref:`Variant<class_Variant>` **get_drag_data_fw** **(** :ref:`Vector2<class_Vector2>` arg0, :ref:`Control<class_Control>` arg1 **)**

----

.. _class_FileSystemDock_method_navigate_to_path:

- void **navigate_to_path** **(** :ref:`String<class_String>` arg0 **)**

