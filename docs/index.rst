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

In this project we will be making an old school style video game for the PyBadge. We will be using CircuitPython with the stage library, to create a Space Invaders like game.

The stage library makes it easy to make classic video games, with access to backgrounds, sound, sprites and collision detection. The game will also work on other variants of hareware that runs CircuitPython and has a screen, like the PyGames and the PyEdge Badge.

.. toctree::
   :maxdepth: 2
   :hidden:
   :titlesonly:

   Install CircuitPython <./install/index>
   Creating Image Bank
   Drawing a Background
   Getting Sprite on Screen