.. _class_Thread:

Thread
======

Inherits: :ref:`Reference<class_reference>`
-------------------------------------------

Category: Core
--------------

Brief Description
-----------------



Member Functions
----------------

+------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Error                        | :ref:`start<class_Thread_start>`  **(** :ref:`Object<class_object>` instance, :ref:`String<class_string>` method, var userdata=NULL, :ref:`int<class_int>` priority=1  **)** |
+------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`  | :ref:`get_id<class_Thread_get_id>`  **(** **)** const                                                                                                                        |
+------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`      | :ref:`is_active<class_Thread_is_active>`  **(** **)** const                                                                                                                  |
+------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Variant                      | :ref:`wait_to_finish<class_Thread_wait_to_finish>`  **(** **)**                                                                                                              |
+------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Numeric Constants
-----------------

- **PRIORITY_LOW** = **0**
- **PRIORITY_NORMAL** = **1**
- **PRIORITY_HIGH** = **2**

Member Function Description
---------------------------

.. _class_Thread_start:

- Error  **start**  **(** :ref:`Object<class_object>` instance, :ref:`String<class_string>` method, var userdata=NULL, :ref:`int<class_int>` priority=1  **)**

.. _class_Thread_get_id:

- :ref:`String<class_string>`  **get_id**  **(** **)** const

.. _class_Thread_is_active:

- :ref:`bool<class_bool>`  **is_active**  **(** **)** const

.. _class_Thread_wait_to_finish:

- Variant  **wait_to_finish**  **(** **)**

