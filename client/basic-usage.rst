Basic Usage
===========

Once you have JourneyMap :ref:`installed <installing>`,
all you need to do is join a server or load up a single-player world.

For the most part, JourneyMap works right out of the box. All you need to do
to start mapping your world is to begin exploring it! The area around you will
be mapped automatically as you travel, and will be visible in each of the three
types of map that JourneyMap supports.

Key Mappings
------------

The following key mappings are available by default when you're playing on a
world or multiplayer server.

* :kbd:`J` - Show/hide the full-screen map
* :kbd:`Ctrl` :kbd:`J` - Show/hide the minimap

* :kbd:`=` and :kbd:`–` - Zoom the minimap in and out respectively
* :kbd:`[` - Cycle the map type shown in the minimap
* :kbd:`#` - Switch between minimap presets

* :kbd:`B` - Create :ref:`a waypoint <waypoints>` where you're currently standing
* :kbd:`Ctrl` :kbd:`B` - Open the :ref:`waypoint manager <waypoints>` (this conflicts with 
  the narrator keybind, so you may want to change or disable that)
* :kbd:`Z` - Toggle the visibility of all waypoints

All keys specified in the documentation can be customized in Minecraft's own
settings. Just open the menu (by default, with the :kbd:`Esc` key), click on
:code:`Options` and then :code:`Controls`, and you'll see two new categories 
for all of JourneyMap's keys.

Markers
-------

All map types contain markers. These markers denote various pieces of information -
such as the position of an entity or :ref:`a waypoint <waypoints>` on the map.

.. table:: 
    :class: icon-table
    :widths: 10 40 10 40

    +------------------------------------------------------------------+-----------------------------------------------------------------------------------------+------------------------------------------------------+-----------------------------------------+
    |.. image:: /_static/images/markers/marker-player.png              | Your position on the map. *Note: This icon has a white border ingame.*                                                                                                                   |
    +------------------------------------------------------------------+-----------------------------------------------------------------------------------------+------------------------------------------------------+-----------------------------------------+
    |.. image:: /_static/images/markers/waypoint.png                   | :ref:`A waypoint <waypoints>`. The colour can be set in the waypoint manager.           |.. image:: /_static/images/markers/waypoint-death.png | :ref:`A death waypoint <waypoints>`.    |
    +------------------------------------------------------------------+-----------------------------------------------------------------------------------------+------------------------------------------------------+-----------------------------------------+

.. table:: 
    :class: icon-table
    :widths: 10 40 10 40

    +------------------------------------------------------------+------------------------------------------+--------------------------------------------------------+-----------------------------------------+
    |.. image:: /_static/images/markers/marker-white.png         | A marker denoting an entity on the map. The colour of the marker denotes the type of entity.                                                |
    +------------------------------------------------------------+------------------------------------------+--------------------------------------------------------+-----------------------------------------+
    |.. image:: /_static/images/markers/marker-white-down.png    | An entity below you.                     | .. image:: /_static/images/markers/marker-white-up.png | An entity above you.                    |
    +------------------------------------------------------------+------------------------------------------+--------------------------------------------------------+-----------------------------------------+

.. table:: 
    :class: icon-table
    :widths: 10 40 10 40

    +------------------------------------------------------------+------------------------------------------+--------------------------------------------------------+-----------------------------------------+
    |.. image:: /_static/images/markers/marker-grey.png          | A neutral entity, like an animal.        | .. image:: /_static/images/markers/marker-green.png    | A villager.                             |
    +------------------------------------------------------------+------------------------------------------+--------------------------------------------------------+-----------------------------------------+
    |.. image:: /_static/images/markers/marker-blue.png          | Another player.                          | .. image:: /_static/images/markers/marker-red.png      | A hostile entity, like a monster.       |
    +------------------------------------------------------------+------------------------------------------+--------------------------------------------------------+-----------------------------------------+

Markers and their display can be customized in the :ref:`settings manager <settings>`.

The Minimap
-----------

By default, the minimap will be displayed in the top-right corner of your screen.

.. figure:: /_static/images/minimap.png
    :alt: Minimap example

This is your minimap. By default, it displays the area around your character,
as well as some basic information and the positions of your character, other 
players, animals and monsters.

The minimap can be zoomed in and out at any time by pressing either of the
**zoom keys** (by default, the :kbd:`=` and :kbd:`–` keys).

The four lines of text above and below the minimap are known as **info slots**.
By default, they show (in order):

* The current time in the real world
* The current time ingame
* The coordinates of your character
* The current biome your character is in

The minimap and its info slots may be customized in the :ref:`settings manager <settings>`.

The Full-Screen Map
-------------------

By pressing the **full-screen map key** (by default, the :kbd:`J` key), you can open
the full-screen map.

.. figure:: /_static/images/full-screen.png
    :alt: Full-screen example

This map gives you a scrollable view of all of the areas of the map you've explored 
so far, displayed as it was when you discovered them. It also provides access to 
JourneyMap's :ref:`settings` and a number of map display options.

For more information on the full-screen map, please see :ref:`the full-screen map page <full-screen>`.

The Webmap
----------

Once enabled in the :ref:`settings manager <settings>`, the webmap allows you to view and explore your
generated map in a web browser, including accessing it from another device (such as
a phone or tablet). This will work as long as the game is running.

.. figure:: /_static/images/webmap.png
    :alt: Webmap example

For more information on the webmap map, please see :ref:`the webmap page <webmap>`.
