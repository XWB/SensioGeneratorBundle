Generating a New Command
========================

Usage
-----

The ``generate:command`` command generates a new Command class for the given
console command.

By default the command is run in the interactive mode and asks questions to
determine the bundle and the command name:

.. code-block:: bash

    $ php app/console generate:command

The command can be run in a non interactive mode by using the
``--no-interaction`` and poviding the needed arguments:

.. code-block:: bash

    $ php app/console generate:command --no-interaction AcmeBlogBundle blog:publish-posts

Available Arguments
-------------------

* ``bundle``: The name of the bundle where the command class is generated.
* ``name``: The name of the command as you type it in the console.
