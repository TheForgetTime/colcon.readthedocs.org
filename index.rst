colcon - 批量构建
================================

`colcon`_ 是一个改进构建、测试和使用多个软件包的工作流程的命令行工具.
它自动化了软件包构建以及环境变量设置这个过程使得使用软件包更加方便.

.. _colcon: http://colcon.readthedocs.io

工具是开源的,可以在 `available on GitHub`_ 上找到源码.

.. _available on GitHub: http://github.com/colcon

The documentation exists in two version:

* `released <http://colcon.readthedocs.io/en/released/>`_: matching the latest released version of all packages
* `latest <http://colcon.readthedocs.io/en/master/>`_: matching the latest state on the default branch of all packages

The documentation is organized into a few sections:

* :ref:`user-docs`
* :ref:`migration-docs`

Information about development is also available:

* :ref:`developer-docs`

.. _user-docs:

.. toctree::
   :maxdepth: 2
   :caption: User Documentation

   user/installation
   user/quick-start
   user/configuration
   user/how-to

.. _reference-docs:

.. toctree::
   :maxdepth: 2
   :caption: Reference

   reference/verb/build
   reference/verb/edit
   reference/verb/graph
   reference/verb/info
   reference/verb/list
   reference/verb/metadata
   reference/verb/mixin
   reference/verb/test
   reference/verb/test-result
   reference/global-arguments
   reference/executor-arguments
   reference/event-handler-arguments
   reference/discovery-arguments
   reference/package-selection-arguments
   reference/mixin-arguments

.. _developer-docs:

.. toctree::
   :maxdepth: 2
   :caption: Developer Documentation

   developer/design
   developer/bootstrap
   developer/environment
   developer/program-flow
   developer/extension-point
   developer/contribution
   developer/changelog

.. _migration-docs:

.. toctree::
   :maxdepth: 2
   :caption: Migrate from other build tools

   migration/ament_tools
   migration/catkin_make_isolated
   migration/catkin_tools
