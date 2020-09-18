Installation
=================

.. code-block:: bash

    sudo apt-get install -y libceres-dev
    ./cartographer_ros/scripts/prepare_catkin_workspace.sh
    ./cartographer_ros/scripts/install_debs.sh
    ./cartographer/scripts/install_abseil.sh
    catkin_make_isolated --install --use-ninja
