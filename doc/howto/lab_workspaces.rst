.. ##################################################
.. THIS PAGE IS AUTOMATICALLY IMPORTED FROM https://raw.githubusercontent.com/jupyter/repo2docker/master/docs/source/howto/lab_workspaces.rst.
.. DO NOT EDIT IT DIRECTLY.
.. ##################################################

.. howto/lab_workspaces::

=============================================
Share JupyterLab Workspaces with a repository
=============================================

JupyterLab uses `workspaces <https://jupyterlab.readthedocs.io/en/stable/user/urls.html#managing-workspaces-ui>`_
to save the current state of windows, settings, and documents that
are open in a JupyterLab session. It is a way to persist the general
configuration over time.

It is possible to export JupyterLab workspaces and load them in to
another JupyterLab installation in order to share a workspace with
someone else.

In order to package your workspace with a repository, we recommend
following the steps in this example repository:

https://github.com/ian-r-rose/binder-workspace-demo/
