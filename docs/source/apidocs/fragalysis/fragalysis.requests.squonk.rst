:py:mod:`fragalysis.requests.squonk`
====================================

.. py:module:: fragalysis.requests.squonk

.. autodoc2-docstring:: fragalysis.requests.squonk
   :allowtitles:

Module Contents
---------------

Functions
~~~~~~~~~

.. list-table::
   :class: autosummary longtable
   :align: left

   * - :py:obj:`projects <fragalysis.requests.squonk.projects>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.projects
          :summary:
   * - :py:obj:`instances <fragalysis.requests.squonk.instances>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.instances
          :summary:
   * - :py:obj:`monitor_jobs <fragalysis.requests.squonk.monitor_jobs>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.monitor_jobs
          :summary:
   * - :py:obj:`list_files <fragalysis.requests.squonk.list_files>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.list_files
          :summary:
   * - :py:obj:`get_file <fragalysis.requests.squonk.get_file>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.get_file
          :summary:
   * - :py:obj:`human_timedelta <fragalysis.requests.squonk.human_timedelta>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.human_timedelta
          :summary:

Data
~~~~

.. list-table::
   :class: autosummary longtable
   :align: left

   * - :py:obj:`DATA_MANAGERS <fragalysis.requests.squonk.DATA_MANAGERS>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.DATA_MANAGERS
          :summary:
   * - :py:obj:`DM_API_URLS <fragalysis.requests.squonk.DM_API_URLS>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.DM_API_URLS
          :summary:
   * - :py:obj:`SQUONK_DM_TASK_URL <fragalysis.requests.squonk.SQUONK_DM_TASK_URL>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.SQUONK_DM_TASK_URL
          :summary:
   * - :py:obj:`SQUONK_DM_INSTANCE_URL <fragalysis.requests.squonk.SQUONK_DM_INSTANCE_URL>`
     - .. autodoc2-docstring:: fragalysis.requests.squonk.SQUONK_DM_INSTANCE_URL
          :summary:

API
~~~

.. py:data:: DATA_MANAGERS
   :canonical: fragalysis.requests.squonk.DATA_MANAGERS
   :value: None

   .. autodoc2-docstring:: fragalysis.requests.squonk.DATA_MANAGERS

.. py:data:: DM_API_URLS
   :canonical: fragalysis.requests.squonk.DM_API_URLS
   :value: None

   .. autodoc2-docstring:: fragalysis.requests.squonk.DM_API_URLS

.. py:data:: SQUONK_DM_TASK_URL
   :canonical: fragalysis.requests.squonk.SQUONK_DM_TASK_URL
   :value: '/data-manager-ui/api/dm-api/task/'

   .. autodoc2-docstring:: fragalysis.requests.squonk.SQUONK_DM_TASK_URL

.. py:data:: SQUONK_DM_INSTANCE_URL
   :canonical: fragalysis.requests.squonk.SQUONK_DM_INSTANCE_URL
   :value: '/data-manager-ui/api/dm-api/instance/'

   .. autodoc2-docstring:: fragalysis.requests.squonk.SQUONK_DM_INSTANCE_URL

.. py:function:: projects(token: str, stack: str = 'production') -> pandas.DataFrame
   :canonical: fragalysis.requests.squonk.projects

   .. autodoc2-docstring:: fragalysis.requests.squonk.projects

.. py:function:: instances(token: str, stack: str = 'production') -> pandas.DataFrame
   :canonical: fragalysis.requests.squonk.instances

   .. autodoc2-docstring:: fragalysis.requests.squonk.instances

.. py:function:: monitor_jobs(token: str, stack: str = 'production', instance_ids: str | list[str] | None = None, applications: bool = False, pending: bool = False)
   :canonical: fragalysis.requests.squonk.monitor_jobs

   .. autodoc2-docstring:: fragalysis.requests.squonk.monitor_jobs

.. py:function:: list_files(instance: str, token: str, stack: str = 'production', root: str = '/')
   :canonical: fragalysis.requests.squonk.list_files

   .. autodoc2-docstring:: fragalysis.requests.squonk.list_files

.. py:function:: get_file(instance: str, path: str, token: str, stack: str = 'production', destination: str = None)
   :canonical: fragalysis.requests.squonk.get_file

   .. autodoc2-docstring:: fragalysis.requests.squonk.get_file

.. py:function:: human_timedelta(delta)
   :canonical: fragalysis.requests.squonk.human_timedelta

   .. autodoc2-docstring:: fragalysis.requests.squonk.human_timedelta
