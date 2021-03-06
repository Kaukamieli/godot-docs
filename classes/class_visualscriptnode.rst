.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VisualScriptNode.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VisualScriptNode:

VisualScriptNode
================

**Inherits:** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Inherited By:** :ref:`VisualScriptLocalVar<class_visualscriptlocalvar>`, :ref:`VisualScriptSceneNode<class_visualscriptscenenode>`, :ref:`VisualScriptEmitSignal<class_visualscriptemitsignal>`, :ref:`VisualScriptEngineSingleton<class_visualscriptenginesingleton>`, :ref:`VisualScriptBasicTypeConstant<class_visualscriptbasictypeconstant>`, :ref:`VisualScriptSequence<class_visualscriptsequence>`, :ref:`VisualScriptVariableSet<class_visualscriptvariableset>`, :ref:`VisualScriptSelf<class_visualscriptself>`, :ref:`VisualScriptConstant<class_visualscriptconstant>`, :ref:`VisualScriptReturn<class_visualscriptreturn>`, :ref:`VisualScriptSceneTree<class_visualscriptscenetree>`, :ref:`VisualScriptIndexSet<class_visualscriptindexset>`, :ref:`VisualScriptResourcePath<class_visualscriptresourcepath>`, :ref:`VisualScriptPropertyGet<class_visualscriptpropertyget>`, :ref:`VisualScriptVariableGet<class_visualscriptvariableget>`, :ref:`VisualScriptIndexGet<class_visualscriptindexget>`, :ref:`VisualScriptInputAction<class_visualscriptinputaction>`, :ref:`VisualScriptDeconstruct<class_visualscriptdeconstruct>`, :ref:`VisualScriptTypeCast<class_visualscripttypecast>`, :ref:`VisualScriptGlobalConstant<class_visualscriptglobalconstant>`, :ref:`VisualScriptFunctionCall<class_visualscriptfunctioncall>`, :ref:`VisualScriptYield<class_visualscriptyield>`, :ref:`VisualScriptSwitch<class_visualscriptswitch>`, :ref:`VisualScriptBuiltinFunc<class_visualscriptbuiltinfunc>`, :ref:`VisualScriptClassConstant<class_visualscriptclassconstant>`, :ref:`VisualScriptCondition<class_visualscriptcondition>`, :ref:`VisualScriptOperator<class_visualscriptoperator>`, :ref:`VisualScriptIterator<class_visualscriptiterator>`, :ref:`VisualScriptCustomNode<class_visualscriptcustomnode>`, :ref:`VisualScriptSubCall<class_visualscriptsubcall>`, :ref:`VisualScriptYieldSignal<class_visualscriptyieldsignal>`, :ref:`VisualScriptLocalVarSet<class_visualscriptlocalvarset>`, :ref:`VisualScriptWhile<class_visualscriptwhile>`, :ref:`VisualScriptConstructor<class_visualscriptconstructor>`, :ref:`VisualScriptMathConstant<class_visualscriptmathconstant>`, :ref:`VisualScriptComment<class_visualscriptcomment>`, :ref:`VisualScriptExpression<class_visualscriptexpression>`, :ref:`VisualScriptPropertySet<class_visualscriptpropertyset>`, :ref:`VisualScriptFunction<class_visualscriptfunction>`, :ref:`VisualScriptPreload<class_visualscriptpreload>`, :ref:`VisualScriptSelect<class_visualscriptselect>`

**Category:** Core

Brief Description
-----------------

A node which is part of a :ref:`VisualScript<class_visualscript>`.

Member Functions
----------------

+------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Variant<class_variant>`            | :ref:`get_default_input_value<class_VisualScriptNode_get_default_input_value>`  **(** :ref:`int<class_int>` port_idx  **)** const                                |
+------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`VisualScript<class_visualscript>`  | :ref:`get_visual_script<class_VisualScriptNode_get_visual_script>`  **(** **)** const                                                                            |
+------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`ports_changed_notify<class_VisualScriptNode_ports_changed_notify>`  **(** **)**                                                                            |
+------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                     | :ref:`set_default_input_value<class_VisualScriptNode_set_default_input_value>`  **(** :ref:`int<class_int>` port_idx, :ref:`Variant<class_variant>` value  **)** |
+------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Signals
-------

-  **ports_changed**  **(** **)**
Emitted when the available input/output ports are changed.


Member Variables
----------------

- :ref:`Array<class_array>` **_default_input_values**

Description
-----------

A node which is part of a :ref:`VisualScript<class_visualscript>`. Not to be confused with :ref:`Node<class_node>`, which is a part of a :ref:`SceneTree<class_scenetree>`.

Member Function Description
---------------------------

.. _class_VisualScriptNode_get_default_input_value:

- :ref:`Variant<class_variant>`  **get_default_input_value**  **(** :ref:`int<class_int>` port_idx  **)** const

Returns the default value of a given port. The default value is used when nothing is connected to the port.

.. _class_VisualScriptNode_get_visual_script:

- :ref:`VisualScript<class_visualscript>`  **get_visual_script**  **(** **)** const

Returns the :ref:`VisualScript<class_visualscript>` instance the node is bound to.

.. _class_VisualScriptNode_ports_changed_notify:

- void  **ports_changed_notify**  **(** **)**

Notify that the node's ports have changed. Usually used in conjunction with :ref:`VisualScriptCustomNode<class_visualscriptcustomnode>` .

.. _class_VisualScriptNode_set_default_input_value:

- void  **set_default_input_value**  **(** :ref:`int<class_int>` port_idx, :ref:`Variant<class_variant>` value  **)**

Change the default value of a given port.


