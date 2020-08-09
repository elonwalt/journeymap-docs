Settings
========

JourneyMap provides more than a few configuration options, allowing you
to customize the behaviour and appearance of many different aspects of
the mod. All of these settings are made available through the settings
manager.

.. figure:: /_static/images/settings/overview.png
    :alt: Settings manager
    :align: center

To get to the settings manager, open the :ref:`full-screen map <full-screen>`
and click the settings button at the bottom, or press the :kbd:`O` key.
Each entry in the list represents a specific category of settings - click
on it to expand and see the settings within.

.. note::
    Each category has a **Reset** button. Please note that **pressing this button
    will reset the settings in that category to the default settings** bundled
    with JourneyMap, instead of simply discarding your changes.

Some of these categories have quite a few settings. Feel free to skip to a specific
category by clicking on one of the links below.

.. contents::
    :local:

Grid Settings
-------------

Both minimap presets and the full-screen map may have a configurable grid overlay.
You can customize this overlay by clicking on the **Edit Grid...** button below
the settings in each respective category.

.. figure:: /_static/images/settings/grid.png
    :alt: Minimap settings
    :align: center

Minimap Settings
----------------

JourneyMap allows you to have two minimap presets. Each preset represents a separate
set of settings - essentially allowing you to have two distinct minimaps available
to switch between.

.. note::
    The settings for each minimap are identical, so we'll only cover a single preset 
    below.

To switch between minimap presets, press the switch minimap preset key 
(the :kbd:`#` key by default).

.. figure:: /_static/images/settings/minimap.png
    :alt: Minimap settings
    :align: center

Toggles
~~~~~~~

By default, all of the following toggle settings are enabled.

.. table::
    :widths: 30 70

    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Toggle                                | Description                                                                          |
    +=======================================+======================================================================================+
    | Enable Minimap                        | Enable or disable this minimap preset                                                |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Animals                          | Show or hide animals                                                                 |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Caves                            | Toggle automatically switching to cave mode                                          |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Compass                          | Toggle showing compass points around the edge of the minimap                         |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Day/Night                        | Toggle automatically switching between day and night mode                            |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Entity Names                     | Show or hide entity names                                                            |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Grid                             | Show or hide the grid overlay                                                        |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Mob Headings                     | Toggle showing which way mobs are facing                                             |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Mobs                             | Show or hide mobs                                                                    |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Pets                             | Show or hide pets                                                                    |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Player Headings                  | Toggle showing which way other players are facing                                    |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Players                          | Show or hide other players                                                           |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Reticle                          | Show or hide midpoint lines pointing to the center of the minimap                    |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Self                             | Show or hide your own location and heading                                           |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Villagers                        | Show or hide villagers                                                               |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Waypoint Labels                  | Show or hide the names of waypoints                                                  |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Show Waypoints                        | Show or hide all waypoints                                                           |
    +---------------------------------------+--------------------------------------------------------------------------------------+
    | Verbose Location                      | Toggle between a long or short form of your current coordinates                      |
    +---------------------------------------+--------------------------------------------------------------------------------------+

Info Slots
~~~~~~~~~~

Info slots are text areas above and below the minimap that show extra contextual 
information. There are four of them, numbered from top to bottom.

.. figure:: /_static/images/minimap-slots.png
    :alt: Minimap info slots
    :align: center

All info slots can be set to one of the following:

* **Blank**: Nothing, hide this info slot
* **Biome**: The biome you're currently in
* **Dimension**: The dimension you're currently in
* **FPS**: The game's FPS counter
* **Game Time**: The current ingame time, as represented by Minecraft's daylight cycle
* **Game Time Real**: The current ingame time, shifted to match a real clock
* **Light Level**: The light level of the block you're standing in
* **Location**: Your current coordinates
* **Region**: Your current region coordinates
* **System Time**: The current real time, according to your computer

Other Settings
~~~~~~~~~~~~~~

The default option for each setting below is marked with **bold text**.

.. table::
    :widths: 20 20 60

    +-----------------------+------------------+--------------------------------------------------------------------------------------+
    | Setting               | Options          | Description                                                                          |
    |                       |                  |                                                                                      |
    +=======================+==================+======================================================================================+      
    | Location              | * **x, z, y (v)**| The format of your coordinates, as shown in an info slot                             |
    |                       | * x, y (v), z    |                                                                                      |
    |                       | * x, z, y        |                                                                                      |
    |                       | * x, y, z        |                                                                                      |
    |                       | * x, z           |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Map Heading           | * **North**      | Which direction the top of the map should face - Note: only circle maps support the  |
    |                       | * Old North      | "My Heading" setting                                                                 |
    |                       | * My Heading     |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Mob Display           | * **Small Dots** | How mobs should be displayed on the minimap                                          |
    |                       | * Large Dots     |                                                                                      |
    |                       | * Small Icons    |                                                                                      |
    |                       | * Large Icons    |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Player Display        | * **Small Dots** | How other players should be displayed on the minimap                                 |
    |                       | * Large Dots     |                                                                                      |
    |                       | * Small Icons    |                                                                                      |
    |                       | * Large Icons    |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Position              | * **Top Right**  | The location of the minimap on your screen                                           |
    |                       | * Bottom Right   |                                                                                      |
    |                       | * Bottom Left    |                                                                                      |
    |                       | * Top Left       |                                                                                      |
    |                       | * Top Center     |                                                                                      |
    |                       | * Center         |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Real Game Time Format | * **HH:mm:ss**   | The text format of the real game time, as shown in an info slot                      |
    |                       | * H:mm:ss        |                                                                                      |
    |                       | * HH:mm          |                                                                                      |
    |                       | * H:mm           |                                                                                      |
    |                       | * hh:mm:ss a     | * **H**: Hours (24-hour, without leading 0)                                          |
    |                       | * h:mm:ss a      | * **HH**: Hours (24-hour, with leading 0)                                            |
    |                       | * hh:mm:ss       | * **h**: Hours (12-hour, without leading 0)                                          |
    |                       | * h:mm:ss        | * **hh**: Hours (12-hour, with leading 0)                                            |
    |                       | * h:mm a         | * **mm**: Minutes                                                                    |
    |                       | * h:mm a         | * **ss**: Seconds                                                                    |
    |                       | * hh:mm          | * **a**: Time of day (AM/PM)                                                         |
    |                       | * h:mm           |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Reticle Heading       | * **Compass**    | Change the orientation of the reticle                                                |
    |                       | * My Heading     |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Shape                 | * **Circle**     | Change the shape of the minimap                                                      |
    |                       | * Square         |                                                                                      |
    |                       | * Rectangle      |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | System Time Format    | * **HH:mm:ss**   | The text format of the system time, as shown in an info slot                         |
    |                       | * H:mm:ss        |                                                                                      |
    |                       | * HH:mm          |                                                                                      |
    |                       | * H:mm           |                                                                                      |
    |                       | * hh:mm:ss a     | * **H**: Hours (24-hour, without leading 0)                                          |
    |                       | * h:mm:ss a      | * **HH**: Hours (24-hour, with leading 0)                                            |
    |                       | * hh:mm:ss       | * **h**: Hours (12-hour, without leading 0)                                          |
    |                       | * h:mm:ss        | * **hh**: Hours (12-hour, with leading 0)                                            |
    |                       | * h:mm a         | * **mm**: Minutes                                                                    |
    |                       | * h:mm a         | * **ss**: Seconds                                                                    |
    |                       | * hh:mm          | * **a**: Time of day (AM/PM)                                                         |
    |                       | * h:mm           |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Compass Font Scale    | Range: **1** - 4 | How large the compass text should be relative to the GUI scale setting               |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Font Scale            | Range: **1** - 4 | How large the info slot text should be relative to the GUI scale setting             |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Frame Opacity         | Percentage,      | How opaque the frame around the outside of the minimap should be                     |
    |                       | default: **100%**|                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Map Opacity           | Percentage,      | How opaque the map view itself should be                                             |
    |                       | default: **100%**|                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        
    | Size                  | Percentage,      | How large the minimap should be, as a percentage of the window size                  |
    |                       | default: **30%** |                                                                                      |
    +-----------------------+------------------+--------------------------------------------------------------------------------------+        

Full-Screen Map Settings
------------------------

.. figure:: /_static/images/settings/full-screen.png
    :alt: Full-screen map settings
    :align: center

Webmap Settings
---------------

.. figure:: /_static/images/settings/webmap.png
    :alt: Webmap settings
    :align: center

Waypoint Settings
-----------------

.. figure:: /_static/images/settings/waypoints.png
    :alt: Waypoint settings
    :align: center

Waypoint Beacon Settings
------------------------

.. figure:: /_static/images/settings/waypoint-beacons.png
    :alt: Waypoint beacon settings
    :align: center

Cartography Settings
--------------------

.. figure:: /_static/images/settings/cartography.png
    :alt: Cartography settings
    :align: center

Advanced Settings
-----------------

.. figure:: /_static/images/settings/advanced.png
    :alt: Advanced settings
    :align: center
