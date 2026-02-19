:py:mod:`fragalysis.requests.download`
======================================

.. py:module:: fragalysis.requests.download

.. autodoc2-docstring:: fragalysis.requests.download
   :allowtitles:

Module Contents
---------------

Functions
~~~~~~~~~

.. list-table::
   :class: autosummary longtable
   :align: left

   * - :py:obj:`target_list <fragalysis.requests.download.target_list>`
     - .. autodoc2-docstring:: fragalysis.requests.download.target_list
          :summary:
   * - :py:obj:`download_target <fragalysis.requests.download.download_target>`
     - .. autodoc2-docstring:: fragalysis.requests.download.download_target
          :summary:
   * - :py:obj:`target_uploads <fragalysis.requests.download.target_uploads>`
     - .. autodoc2-docstring:: fragalysis.requests.download.target_uploads
          :summary:

API
~~~

.. py:function:: target_list(stack: str = 'production', token: str | None = None, return_project_data: bool = False) -> list[dict]
   :canonical: fragalysis.requests.download.target_list

   .. autodoc2-docstring:: fragalysis.requests.download.target_list

.. py:function:: download_target(name: str, tas: str, stack: str = 'production', token: str | None = None, destination: str = '.', metadata_file: bool = True, combined_sdf: bool = True, compound_set_sdfs: bool = True, soakdb_files: bool = True, unaligned_pdbs: bool = False, ligand_cifs: bool = False, event_maps: bool = False, inspection_maps: bool = False, residual_maps: bool = False, real_space_maps: bool = False, transformation_files: bool = False, reflections_files: bool = False, extract: bool = True) -> None
   :canonical: fragalysis.requests.download.download_target

   .. autodoc2-docstring:: fragalysis.requests.download.download_target

.. py:function:: target_uploads(stack: str = 'production', token: str | None = None, statistics_only: bool = False) -> dict[(str, str), list]
   :canonical: fragalysis.requests.download.target_uploads

   .. autodoc2-docstring:: fragalysis.requests.download.target_uploads
