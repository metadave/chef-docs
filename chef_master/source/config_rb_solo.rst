=====================================================
|solo rb|
=====================================================

.. warning:: The |chef client| now `includes an option called local mode <http://docs.opscode.com/ctl_chef_client.html#run-in-local-mode>`_ (``--local-mode`` or ``-z``), which runs the |chef client| against the |chef repo| on the local machine as if it were running against a |chef server|. Local mode was added to the |chef client| in the 11.8 release. If you are running that version of the |chef client| (or later), you should consider using local mode instead of using |chef solo|.

.. include:: ../../includes_config/includes_config_rb_solo.rst

Settings
==========================================================================

.. include:: ../../includes_config/includes_config_rb_11-12_solo_settings.rst

Example
=====================================================
.. include:: ../../includes_config/includes_config_rb_solo_example.rst

