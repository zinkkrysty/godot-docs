.. _class_Area2D:

Area2D
======

Inherits: :ref:`CollisionObject2D<class_collisionobject2d>`
-----------------------------------------------------------

Category: Core
--------------

Brief Description
-----------------

General purpose area detection and influence for 2D physics.

Member Functions
----------------

+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_space_override_mode<class_Area2D_set_space_override_mode>`  **(** :ref:`int<class_int>` enable  **)**                           |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                      | :ref:`get_space_override_mode<class_Area2D_get_space_override_mode>`  **(** **)** const                                                   |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_gravity_is_point<class_Area2D_set_gravity_is_point>`  **(** :ref:`bool<class_bool>` enable  **)**                               |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                    | :ref:`is_gravity_a_point<class_Area2D_is_gravity_a_point>`  **(** **)** const                                                             |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_gravity_distance_scale<class_Area2D_set_gravity_distance_scale>`  **(** :ref:`float<class_float>` distance_scale  **)**         |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                  | :ref:`get_gravity_distance_scale<class_Area2D_get_gravity_distance_scale>`  **(** **)** const                                             |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_gravity_vector<class_Area2D_set_gravity_vector>`  **(** :ref:`Vector2<class_vector2>` vector  **)**                             |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_vector2>`              | :ref:`get_gravity_vector<class_Area2D_get_gravity_vector>`  **(** **)** const                                                             |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_gravity<class_Area2D_set_gravity>`  **(** :ref:`float<class_float>` gravity  **)**                                              |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                  | :ref:`get_gravity<class_Area2D_get_gravity>`  **(** **)** const                                                                           |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_linear_damp<class_Area2D_set_linear_damp>`  **(** :ref:`float<class_float>` linear_damp  **)**                                  |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                  | :ref:`get_linear_damp<class_Area2D_get_linear_damp>`  **(** **)** const                                                                   |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_angular_damp<class_Area2D_set_angular_damp>`  **(** :ref:`float<class_float>` angular_damp  **)**                               |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                  | :ref:`get_angular_damp<class_Area2D_get_angular_damp>`  **(** **)** const                                                                 |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_priority<class_Area2D_set_priority>`  **(** :ref:`float<class_float>` priority  **)**                                           |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                  | :ref:`get_priority<class_Area2D_get_priority>`  **(** **)** const                                                                         |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_collision_mask<class_Area2D_set_collision_mask>`  **(** :ref:`int<class_int>` collision_mask  **)**                             |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                      | :ref:`get_collision_mask<class_Area2D_get_collision_mask>`  **(** **)** const                                                             |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_layer_mask<class_Area2D_set_layer_mask>`  **(** :ref:`int<class_int>` layer_mask  **)**                                         |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                      | :ref:`get_layer_mask<class_Area2D_get_layer_mask>`  **(** **)** const                                                                     |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_collision_mask_bit<class_Area2D_set_collision_mask_bit>`  **(** :ref:`int<class_int>` bit, :ref:`bool<class_bool>` value  **)** |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                    | :ref:`get_collision_mask_bit<class_Area2D_get_collision_mask_bit>`  **(** :ref:`int<class_int>` bit  **)** const                          |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_layer_mask_bit<class_Area2D_set_layer_mask_bit>`  **(** :ref:`int<class_int>` bit, :ref:`bool<class_bool>` value  **)**         |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                    | :ref:`get_layer_mask_bit<class_Area2D_get_layer_mask_bit>`  **(** :ref:`int<class_int>` bit  **)** const                                  |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_enable_monitoring<class_Area2D_set_enable_monitoring>`  **(** :ref:`bool<class_bool>` enable  **)**                             |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                    | :ref:`is_monitoring_enabled<class_Area2D_is_monitoring_enabled>`  **(** **)** const                                                       |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| void                                       | :ref:`set_monitorable<class_Area2D_set_monitorable>`  **(** :ref:`bool<class_bool>` enable  **)**                                         |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                    | :ref:`is_monitorable<class_Area2D_is_monitorable>`  **(** **)** const                                                                     |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_array>`                  | :ref:`get_overlapping_bodies<class_Area2D_get_overlapping_bodies>`  **(** **)** const                                                     |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_array>`                  | :ref:`get_overlapping_areas<class_Area2D_get_overlapping_areas>`  **(** **)** const                                                       |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PhysicsBody2D<class_physicsbody2d>`  | :ref:`overlaps_body<class_Area2D_overlaps_body>`  **(** :ref:`Object<class_object>` body  **)** const                                     |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Area2D<class_area2d>`                | :ref:`overlaps_area<class_Area2D_overlaps_area>`  **(** :ref:`Object<class_object>` area  **)** const                                     |
+--------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+

Signals
-------

-  **body_enter**  **(** :ref:`Object<class_object>` body  **)**
-  **body_enter_shape**  **(** :ref:`int<class_int>` body_id, :ref:`Object<class_object>` body, :ref:`int<class_int>` body_shape, :ref:`int<class_int>` area_shape  **)**
-  **area_enter**  **(** :ref:`Object<class_object>` area  **)**
-  **area_enter_shape**  **(** :ref:`int<class_int>` area_id, :ref:`Object<class_object>` area, :ref:`int<class_int>` area_shape, :ref:`int<class_int>` area_shape  **)**
-  **body_exit**  **(** :ref:`Object<class_object>` body  **)**
-  **body_exit_shape**  **(** :ref:`int<class_int>` body_id, :ref:`Object<class_object>` body, :ref:`int<class_int>` body_shape, :ref:`int<class_int>` area_shape  **)**
-  **area_exit**  **(** :ref:`Object<class_object>` area  **)**
-  **area_exit_shape**  **(** :ref:`int<class_int>` area_id, :ref:`Object<class_object>` area, :ref:`int<class_int>` area_shape, :ref:`int<class_int>` area_shape  **)**

Description
-----------

General purpose area detection for 2D physics. Areas can be used for detection of objects that enter/exit them, as well as overriding space parameters (changing gravity, damping, etc). For this, use any space override different from AREA_SPACE_OVERRIDE_DISABLE and point gravity at the center of mass.

Member Function Description
---------------------------

.. _class_Area2D_set_space_override_mode:

- void  **set_space_override_mode**  **(** :ref:`int<class_int>` enable  **)**

Set the space override mode. This mode controls how an area affects gravity and damp.

AREA_SPACE_OVERRIDE_DISABLED: This area does not affect gravity/damp. These are generally areas that exist only to detect collisions, and objects entering or exiting them.

AREA_SPACE_OVERRIDE_COMBINE: This area adds its gravity/damp values to whatever has been calculated so far. This way, many overlapping areas can combine their physics to make interesting effects.

AREA_SPACE_OVERRIDE_COMBINE_REPLACE: This area adds its gravity/damp values to whatever has been calculated so far. Then stops taking into account the rest of the areas, even the default one.

AREA_SPACE_OVERRIDE_REPLACE: This area replaces any gravity/damp, even the default one, and stops taking into account the rest of the areas.

AREA_SPACE_OVERRIDE_REPLACE_COMBINE: This area replaces any gravity/damp calculated so far, but keeps calculating the rest of the areas, down to the default one.

.. _class_Area2D_get_space_override_mode:

- :ref:`int<class_int>`  **get_space_override_mode**  **(** **)** const

Return the space override mode.

.. _class_Area2D_set_gravity_is_point:

- void  **set_gravity_is_point**  **(** :ref:`bool<class_bool>` enable  **)**

When overriding space parameters, this method sets whether this area has a center of gravity. To set/get the location of the center of gravity, use :ref:`set_gravity_vector<Area2D_set_gravity_vector>`/:ref:`get_gravity_vector<Area2D_get_gravity_vector>`.

.. _class_Area2D_is_gravity_a_point:

- :ref:`bool<class_bool>`  **is_gravity_a_point**  **(** **)** const

Return whether gravity is a point. A point gravity will attract objects towards it, as opposed to a gravity vector, which moves them in a given direction.

.. _class_Area2D_set_gravity_distance_scale:

- void  **set_gravity_distance_scale**  **(** :ref:`float<class_float>` distance_scale  **)**

Set the falloff factor for point gravity. The greater this value is, the faster the strength of gravity decreases with the square of distance.

.. _class_Area2D_get_gravity_distance_scale:

- :ref:`float<class_float>`  **get_gravity_distance_scale**  **(** **)** const

Return the falloff factor for point gravity.

.. _class_Area2D_set_gravity_vector:

- void  **set_gravity_vector**  **(** :ref:`Vector2<class_vector2>` vector  **)**

Set the gravity vector. This vector does not have to be normalized.

If gravity is a point (see :ref:`is_gravity_a_point<Area2D_is_gravity_a_point>`), this will be the attraction center.

.. _class_Area2D_get_gravity_vector:

- :ref:`Vector2<class_vector2>`  **get_gravity_vector**  **(** **)** const

Return the gravity vector. If gravity is a point (see :ref:`is_gravity_a_point<Area2D_is_gravity_a_point>`), this will be the attraction center.

.. _class_Area2D_set_gravity:

- void  **set_gravity**  **(** :ref:`float<class_float>` gravity  **)**

Set the gravity intensity. This is useful to alter the force of gravity without altering its direction.

This value multiplies the gravity vector, whether it is the given vector (:ref:`set_gravity_vector<Area2D_set_gravity_vector>`), or a calculated one (when using a center of gravity).

.. _class_Area2D_get_gravity:

- :ref:`float<class_float>`  **get_gravity**  **(** **)** const

Return the gravity intensity.

.. _class_Area2D_set_linear_damp:

- void  **set_linear_damp**  **(** :ref:`float<class_float>` linear_damp  **)**

Set the rate at which objects stop moving in this area, if there are not any other forces moving it. The value is a fraction of its current speed, lost per second. Thus, a value of 1.0 should mean stopping immediately, and 0.0 means the object never stops.

In practice, as the fraction of speed lost gets smaller with each frame, a value of 1.0 does not mean the object will stop in exactly one second. Only when the physics calculations are done at 1 frame per second, it does stop in a second.

.. _class_Area2D_get_linear_damp:

- :ref:`float<class_float>`  **get_linear_damp**  **(** **)** const

Return the linear damp rate.

.. _class_Area2D_set_angular_damp:

- void  **set_angular_damp**  **(** :ref:`float<class_float>` angular_damp  **)**

Set the rate at which objects stop spinning in this area, if there are not any other forces making it spin. The value is a fraction of its current speed, lost per second. Thus, a value of 1.0 should mean stopping immediately, and 0.0 means the object never stops.

In practice, as the fraction of speed lost gets smaller with each frame, a value of 1.0 does not mean the object will stop in exactly one second. Only when the physics calculations are done at 1 frame per second, it does stop in a second.

.. _class_Area2D_get_angular_damp:

- :ref:`float<class_float>`  **get_angular_damp**  **(** **)** const

Return the angular damp rate.

.. _class_Area2D_set_priority:

- void  **set_priority**  **(** :ref:`float<class_float>` priority  **)**

Set the order in which the area is processed. Greater values mean the area gets processed first. This is useful for areas which have an space override different from AREA_SPACE_OVERRIDE_DISABLED or AREA_SPACE_OVERRIDE_COMBINE, as they replace values, and are thus order-dependent.

Areas with the same priority value get evaluated in an unpredictable order, and should be differentiated if evaluation order is to be important.

.. _class_Area2D_get_priority:

- :ref:`float<class_float>`  **get_priority**  **(** **)** const

Return the processing order of this area.

.. _class_Area2D_set_collision_mask:

- void  **set_collision_mask**  **(** :ref:`int<class_int>` collision_mask  **)**

Set the physics layers this area can scan for collisions.

.. _class_Area2D_get_collision_mask:

- :ref:`int<class_int>`  **get_collision_mask**  **(** **)** const

Return the physics layers this area can scan for collisions.

.. _class_Area2D_set_layer_mask:

- void  **set_layer_mask**  **(** :ref:`int<class_int>` layer_mask  **)**

Set the physics layers this area is in.

Collidable objects can exist in any of 32 different layers. These layers are not visual, but more of a tagging system instead. A collidable can use these layers/tags to select with which objects it can collide, using :ref:`set_collision_mask<Area2D_set_collision_mask>`.

A contact is detected if object A is in any of the layers that object B scans, or object B is in any layer scanned by object A.

.. _class_Area2D_get_layer_mask:

- :ref:`int<class_int>`  **get_layer_mask**  **(** **)** const

Return the physics layer this area is in.

.. _class_Area2D_set_collision_mask_bit:

- void  **set_collision_mask_bit**  **(** :ref:`int<class_int>` bit, :ref:`bool<class_bool>` value  **)**

Set/clear individual bits on the collision mask. This makes selecting the areas scanned easier.

.. _class_Area2D_get_collision_mask_bit:

- :ref:`bool<class_bool>`  **get_collision_mask_bit**  **(** :ref:`int<class_int>` bit  **)** const

Return an individual bit on the collision mask.

.. _class_Area2D_set_layer_mask_bit:

- void  **set_layer_mask_bit**  **(** :ref:`int<class_int>` bit, :ref:`bool<class_bool>` value  **)**

Set/clear individual bits on the layer mask. This makes getting an area in/out of only one layer easier.

.. _class_Area2D_get_layer_mask_bit:

- :ref:`bool<class_bool>`  **get_layer_mask_bit**  **(** :ref:`int<class_int>` bit  **)** const

Return an individual bit on the layer mask.

.. _class_Area2D_set_enable_monitoring:

- void  **set_enable_monitoring**  **(** :ref:`bool<class_bool>` enable  **)**

Set whether this area can detect bodies/areas entering/exiting it.

.. _class_Area2D_is_monitoring_enabled:

- :ref:`bool<class_bool>`  **is_monitoring_enabled**  **(** **)** const

Return whether this area detects bodies/areas entering/exiting it.

.. _class_Area2D_set_monitorable:

- void  **set_monitorable**  **(** :ref:`bool<class_bool>` enable  **)**

Set whether this area can be detected by other, monitoring, areas. Only areas need to be marked as monitorable. Bodies are always so.

.. _class_Area2D_is_monitorable:

- :ref:`bool<class_bool>`  **is_monitorable**  **(** **)** const

Set whether this area can be detected by other, monitoring, areas.

.. _class_Area2D_get_overlapping_bodies:

- :ref:`Array<class_array>`  **get_overlapping_bodies**  **(** **)** const

Return a list of the bodies (:ref:`PhysicsBody2D<class_physicsbody2d>`) that are totally or partially inside this area.

.. _class_Area2D_get_overlapping_areas:

- :ref:`Array<class_array>`  **get_overlapping_areas**  **(** **)** const

Return a list of the areas that are totally or partially inside this area.

.. _class_Area2D_overlaps_body:

- :ref:`PhysicsBody2D<class_physicsbody2d>`  **overlaps_body**  **(** :ref:`Object<class_object>` body  **)** const

Return whether the body passed is totally or partially inside this area.

.. _class_Area2D_overlaps_area:

- :ref:`Area2D<class_area2d>`  **overlaps_area**  **(** :ref:`Object<class_object>` area  **)** const

Return whether the area passed is totally or partially inside this area.

