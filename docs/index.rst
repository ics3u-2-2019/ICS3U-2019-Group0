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

|
|
|
|
|
|
|

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

    So you can move your CircuitPython code onto the PyBadge.

|
|
|
|
|

You might also want:

.. container:: twocol

  .. container:: leftside

    .. image:: ./images/3898-00.jpg
      :width: 320 px
      :height: 240 px
      :alt: Lipo Battery
      :align: left

  .. container:: rightside

    `Lithium Ion Polymer Battery Ideal For Feathers - 3.7V 400mAh <https://www.adafruit.com/product/3898>`_
    
    PRODUCT ID: 3898

    So that you can play the game without having it attached to a computer with a USB cable.

|
|
|
|
|

.. container:: twocol

  .. container:: leftside

    .. image:: ./images/3923-04.jpg
      :width: 320 px
      :height: 240 px
      :alt: USB Cable
      :align: left

  .. container:: rightside

    `Mini Oval Speaker - 8 Ohm 1 Watt <https://www.adafruit.com/product/4148>`_
    
    PRODUCT ID: 3923

    If you want lots of sound. Be warned, the built in speaker is actually pretty loud.

|
|
|
|
|

.. container:: twocol

  .. container:: leftside

    .. image:: ./images/printed_case.jpg
      :width: 320 px
      :height: 240 px
      :alt: USB Cable
      :align: left

  .. container:: rightside

    `3D Printed Case <https://www.tinkercad.com/things/fHOWOY88j9A?utm_source=externalsite&utm_medium=embedver1&utm_campaign=embed>`_

    I did not create this case. I `altered Adafruit's design <https://learn.adafruit.com/pybadge-case/>`_. One of the screw posts was hitting the built in speaker and the case was not closing properly. I also added a peice of plastic over the display ribbon cable, to keep it better protected. You will need 4 x 3M screws to hold the case together.


.. toctree::
   :maxdepth: 2
   :hidden:
   :titlesonly:

   Home <./index>
   Install CircuitPython <./install/index>
   Install Mu IDE <./mu/index>
   Creating Image Bank <./image_bank/index>
   Drawing a Background <./background/index>
   Getting Sprite on Screen <./sprites/index>
