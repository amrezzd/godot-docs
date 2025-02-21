:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VisualScriptVariableSet.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VisualScriptVariableSet:

VisualScriptVariableSet
=======================

**Inherits:** :ref:`VisualScriptNode<class_VisualScriptNode>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Changes a variable's value.

Description
-----------

Changes a variable's value to the given input.

\ **Input Ports:**\ 

- Sequence

- Data (variant): ``set``\ 

\ **Output Ports:**\ 

- Sequence

Properties
----------

+-------------------------------------+------------------------------------------------------------------+---------+
| :ref:`StringName<class_StringName>` | :ref:`var_name<class_VisualScriptVariableSet_property_var_name>` | ``&""`` |
+-------------------------------------+------------------------------------------------------------------+---------+

Property Descriptions
---------------------

.. _class_VisualScriptVariableSet_property_var_name:

- :ref:`StringName<class_StringName>` **var_name**

+-----------+---------------------+
| *Default* | ``&""``             |
+-----------+---------------------+
| *Setter*  | set_variable(value) |
+-----------+---------------------+
| *Getter*  | get_variable()      |
+-----------+---------------------+

The variable's name.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
