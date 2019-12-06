.. raw:: html

    <style>
        .row {clear: both}

        .column img {border: 1px solid black;}

        @media only screen and (min-width: 1000px),
               only screen and (min-width: 500px) and (max-width: 768px){

            .column {
                padding-left: 5px;
                padding-right: 5px;
                float: left;
            }

            .column3  {
                width: 33.3%;
            }

            .column2  {
                width: 50%;
            }
        }
    </style>

=================================
Space Aliens - CircuitPython Game
=================================

.. raw:: html

    <div style="text-align: center; margin-bottom: 2em;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/PpzAbdmxzPU?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </div>

In this project we will be making an old school style video game for the `Adafruit PyBadge <https://www.adafruit.com/product/4200>`_. We will be using `CircuitPython <https://circuitpython.org>`_ and the `stage library <https://learn.adafruit.com/circuitpython-stage-game-library>`_ to create a `Space Invaders <https://en.wikipedia.org/wiki/Space_Invaders>`_ like game.  

The stage library makes it easy to make classic video games, with helper libraries for sound, sprites and collision detection. The game will also work on other variants of PyBadge hardware, like the `PyGamer <https://www.adafruit.com/product/4242>`_ and the `EdgeBadge <https://www.adafruit.com/product/4400>`_.

Parts
=====

You will need the following items:

.. container:: twocol

  .. container:: leftside

    .. image:: ./images/4200-01.jpg
      :width: 320 px
      :height: 240 px
      :alt: PyBadge
      :align: left

  .. container:: rightside

    `Adafruit PyBadge for MakeCode Arcade, CircuitPython or Arduino <https://www.adafruit.com/product/4200>`_
    
    PRODUCT ID: 4200

.. raw:: html
  <p>

.. container:: twocol

  .. container:: leftside

    .. image:: ./images/4148-00.jpg
      :width: 320 px
      :height: 240 px
      :alt: USB Cable
      :align: left

  .. container:: rightside

    `Pink and Purple Braided USB A to Micro B Cable - 2 meter long <https://www.adafruit.com/product/4148>`_
    
    PRODUCT ID: 4148

You might also want
- Lipo Battery
- Speaker
- 3D Printed Case


.. toctree::
   :maxdepth: 2
   :hidden:
   :titlesonly:

   Install CircuitPython <./install/index>
   Needed Hardware <./needed_hardware/index>
   Creating Image Bank <./image_bank/index>
   Drawing a Background <./background/index>
   Getting Sprite on Screen <./sprites/index>
