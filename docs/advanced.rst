.. _advanced:

Advanced Usage
#################

Below are examples of how to use specific ``pySYD`` features, as well as plots showing results before and after their usage.

``--kc``
++++++++

**Before:**

.. code-block:: bash

    $ pysyd run -star 3852594


1st way:

.. list-table:: 

    * - .. figure:: figures_advanced/3852594_after.png

           Fig 1. Before

      - .. figure:: figures_advanced/3852594_after.png

           Fig 2. After

2nd way:

.. image:: figures_advanced/3852594_after.png
    :width: 50 %
.. image:: figures_advanced/3852594_after.png
    :width: 50 %

3rd way:

.. code-block:: bash

    $ pysyd run -star 3852594

.. image:: figures_advanced/3852594_after.png
  :width: 600
  :alt: Fit background output plot for KIC 3852594.
  

**After:**

.. code-block:: bash

    $ pysyd run -star 3852594 --kc

.. image:: figures_advanced/3852594_after.png
  :width: 600
  :alt: Fit background output plot for KIC 3852594.

