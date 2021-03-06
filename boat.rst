The boat
========

.. image:: figures/boat_minimal_label.png
   :alt: Diagram of a simple sailing boat
   :align: right
   :width: 350px

A standard sailing boat has four main parts:

- **Hull**: Base platform, floats in the water.
  Probably also holds most of your electronics.
- **Sails**: Transfers energy from the wind to the boat.
  Sails are most effective when acting as an airfoil,
  not just a bag catching the wind.
- **Keel**: Heavy weight underwater, stops the boat falling over.
- **Rudder**: Sticks into the water, turns to steer the boat.

If you don't want to build your own boat, a good shortcut is to look for remote
controlled model sailing boats. Complete boats with servos for the sails and the
rudder are available for a few hundred euros/dollars/pounds. The *RC laser*
is one popular model, while the *International One Metre* class is a
specification that many different models are made to.

.. figure:: _static/images/black-python-viana-small.jpg
   :alt: A small sailing boat in the water

   The *Black Python*, based on an International One Metre class design,
   at WRSC 2016 (`larger image <_static/images/black-python-viana.jpg>`__).

If you are interested in building a hull, the `MaxiMOOP
<https://www.sailbot.org/maximoop/>`_ design is freely available
(`files on GitHub <https://github.com/WRSC/reference-design>`__).
This is designed for robotic sailing, and among other features,
it has much more space for electronics than most remote controlled boats.

.. figure:: _static/images/maximoop-hull-design.png
   :alt: 3D hull shape with large keel

   The MaxiMOOP hull design

Other things to try
-------------------

.. image:: figures/boat_strangest.png
   :alt: Boat with wing sail and air rudder
   :align: right
   :width: 150px

- *Wing sails* are rigid airfoils rather than a flexible sheet.
  They can be balanced so that changing and holding their position needs little
  force. Åland sailing robots have used a wing sail controlled by a smaller
  tail wing, avoiding the need to actively turn the main wing (`2016 paper
  <https://link.springer.com/chapter/10.1007%2F978-3-319-45453-5_1>`__).
- An *air rudder* steers by deflecting air instead of water.
- *Multi-hull* designs, like catamarans and trimarans, have two or more hulls
  side-by-side, with a gap between them. This can help make the boat more
  stable.
