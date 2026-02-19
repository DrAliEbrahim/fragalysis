:py:mod:`fragalysis.requests.common`
====================================

.. py:module:: fragalysis.requests.common

.. autodoc2-docstring:: fragalysis.requests.common
   :allowtitles:

Module Contents
---------------

Functions
~~~~~~~~~

.. list-table::
   :class: autosummary longtable
   :align: left

   * - :py:obj:`user_info <fragalysis.requests.common.user_info>`
     - .. autodoc2-docstring:: fragalysis.requests.common.user_info
          :summary:
   * - :py:obj:`site_observations <fragalysis.requests.common.site_observations>`
     - .. autodoc2-docstring:: fragalysis.requests.common.site_observations
          :summary:

API
~~~

.. py:function:: user_info(stack: str = 'production', token: str | None = None) -> dict
   :canonical: fragalysis.requests.common.user_info

   .. autodoc2-docstring:: fragalysis.requests.common.user_info

.. py:function:: site_observations(target_id: int | None = None, stack: str = 'production', token: str | None = None) -> dict
   :canonical: fragalysis.requests.common.site_observations

   .. autodoc2-docstring:: fragalysis.requests.common.site_observations
