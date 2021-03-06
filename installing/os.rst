NodeBB Installation by OS
=========================

The following are step-by-step guides to help you get up and running.

.. note::

    If your operating system is not listed here, please feel free to request a guide on our `community <https://community.nodebb.org>`_ or even better yet, submit one here.



.. toctree::
    :hidden:
    :maxdepth: 0

    Arch Linux <os/arch>
    Ubuntu <os/ubuntu>
    Debian <os/debian>
    SmartOS <os/smartos>
    Windows <os/windows8>

* :doc:`Arch Linux <os/arch>`
* :doc:`Ubuntu <os/ubuntu>`
* :doc:`Debian <os/debian>`
* :doc:`SmartOS <os/smartos>`
* :doc:`Windows <os/windows8>`
* :doc:`Mac <os/osx-mavericks>`
* `CentOS <https://blog.tommyparnell.com/installing-nodebb-on-centos-6-5/>`_ (external)

Cluster Setting
=======
NodeBB uses the node-cluster module to utilize more than one cpu core. Edit config.json and add a new property called cluster. You should ideally set this to the number of cores your server has. 
