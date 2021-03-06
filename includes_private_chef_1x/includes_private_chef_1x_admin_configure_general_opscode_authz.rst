.. The contents of this file may be included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


This configuration file has the following settings for opscode-authz:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Setting
     - Description
   * - ``opscode_authz['caching']``
     - Default value: ``"enabled"``. For example:
       ::

          opscode_authz['caching'] = "enabled"

   * - ``opscode_authz['dir']``
     - Default value: ``"/var/opt/opscode/opscode-authz"``. For example:
       ::

          opscode_authz['dir'] = "/var/opt/opscode/opscode-authz"

   * - ``opscode_authz['enable']``
     - Default value: ``true``. For example:
       ::

          opscode_authz['enable'] = true

   * - ``opscode_authz['ha']``
     - Default value: ``false``. For example:
       ::

          opscode_authz['ha'] = false

   * - ``opscode_authz['log_directory']``
     - Default value: ``"/var/log/opscode/opscode-authz"``. For example:
       ::

          opscode_authz['log_directory'] = "/var/log/opscode/opscode-authz"

   * - ``opscode_authz['svlogd_size']``
     - For the svlogd-managed 'current' log set a rotation policy based on the size, in bytes, of the logfile.Default value: ``1000000``. For example:
       ::

          opscode_authz['svlogd_size'] = 1000000

   * - ``opscode_authz['svlogd_num']``
     - For the svlogd-managed 'current' log set a retention policy based on the number of logfiles retained. Default value: ``10``. For example:
       ::

          opscode_authz['svlogd_num'] = 10

   * - ``opscode_authz['port']``
     - Default value: ``9463``. For example:
       ::

          opscode_authz['port'] = 9463

   * - ``opscode_authz['vip']``
     - Default value: ``127.0.0.1"``. For example:
       ::

          opscode_authz['vip'] = "127.0.0.1"

