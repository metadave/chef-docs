.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

|description resource_attributes_intro|

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``backup``
     - |backups_kept| Default value: ``5``.
   * - ``cookbook``
     - |cookbook file_location| The default value is the current cookbook.
   * - ``group``
     - |windows group_identifier|
   * - ``inherits``
     - |windows| only. |inherits windows security| Default value: ``true``.
   * - ``mode``
     - |mode resource_file_11-4|
       
       The behavior is different depending on the platform.
       
       |unix|- and |linux|-based systems: |mode *nix|
       
       |windows|: |mode windows security|
   * - ``owner``
     - |owner windows security|
   * - ``path``
     - |path file_cookbook| |path_fully_qualified|
   * - ``provider``
     - Optional. |provider resource_parameter|
   * - ``rights``
     - |windows| only. |rights windows security|
   * - ``source``
     - |source file_location chef_11-4| Can be used to distribute specific files to specific platforms (see the section "File Specificity", below). Default value: the ``name`` of the resource block (see Syntax section above).

.. note:: Use the ``owner`` and ``right`` attributes and avoid the ``group`` and ``mode`` attributes whenever possible. The ``group`` and ``mode`` attributes are not true |windows| concepts and are provided more for backward compatibility than for best practice.
