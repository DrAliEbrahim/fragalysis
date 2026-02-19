:py:mod:`fragalysis.requests.fragmenstein`
==========================================

.. py:module:: fragalysis.requests.fragmenstein

.. autodoc2-docstring:: fragalysis.requests.fragmenstein
   :allowtitles:

Module Contents
---------------

Functions
~~~~~~~~~

.. list-table::
   :class: autosummary longtable
   :align: left

   * - :py:obj:`fragmenstein_place <fragalysis.requests.fragmenstein.fragmenstein_place>`
     - .. autodoc2-docstring:: fragalysis.requests.fragmenstein.fragmenstein_place
          :summary:
   * - :py:obj:`fragmenstein_combine <fragalysis.requests.fragmenstein.fragmenstein_combine>`
     - .. autodoc2-docstring:: fragalysis.requests.fragmenstein.fragmenstein_combine
          :summary:

API
~~~

.. py:function:: fragmenstein_place(placements: list[dict], target_name: str, tas: str, stack: str = 'production', token: str | None = None, num_repeats: int = 1)
   :canonical: fragalysis.requests.fragmenstein.fragmenstein_place

   .. autodoc2-docstring:: fragalysis.requests.fragmenstein.fragmenstein_place

.. py:function:: fragmenstein_combine(observations: list[str], protein: str, target_name: str, tas: str, stack: str = 'production', token: str | None = None, num_repeats: int = 1, multi: bool = True, min_combine: int = 2, max_combine: int = 3, max_distance: float = 1.5)
   :canonical: fragalysis.requests.fragmenstein.fragmenstein_combine

   .. autodoc2-docstring:: fragalysis.requests.fragmenstein.fragmenstein_combine
