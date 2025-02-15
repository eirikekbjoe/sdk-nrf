.. _ug_wifi_mem_req_scan_mode:

Memory requirements for Wi-Fi applications in Scan mode
#######################################################

Code and RAM memory footprint requirements differ depending on the selected platform and the application example.

The following tables list memory requirement values for selected Wi-Fi® samples supporting Scan mode.

Footprint values are provided in kilobytes (KB).

.. tabs::

   .. tab:: nRF52840 DK

      The following table lists memory requirements for samples running on the :ref:`nRF52840 DK <programming_board_names>` (:ref:`nrf52840dk/nrf52840 <zephyr:nrf52840dk_nrf52840>`).

      +--------------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | Sample                               |   Total ROM |   Wi-Fi driver ROM                        |         nRF70 FW patch ROM |   WPA supplicant ROM |   Total RAM (incl. static heap) |   Wi-Fi driver RAM |   WPA supplicant RAM |
      +======================================+=============+===========================================+============================+======================+=================================+====================+======================+
      | :ref:`Scan <wifi_scan_sample>`       |         150 |                                         1 |                         28 |                    0 |                              64 |                 34 |                    0 |
      +--------------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+

   .. tab:: nRF7002 DK

      The following table lists memory requirements for samples running on the :ref:`nRF7002 DK <programming_board_names>` (:ref:`nrf7002dk/nrf5340/cpuapp <nrf7002dk_nrf5340>`).

      +--------------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | Sample                               |   Total ROM |   Wi-Fi driver ROM                        |         nRF70 FW patch ROM |   WPA supplicant ROM |   Total RAM (incl. static heap) |   Wi-Fi driver RAM |   WPA supplicant RAM |
      +======================================+=============+===========================================+============================+======================+=================================+====================+======================+
      | :ref:`Scan <wifi_scan_sample>`       |         150 |                                        26 |                         25 |                    0 |                              76 |                 45 |                    0 |
      +--------------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+

   .. tab:: nRF9160 DK

      The following table lists memory requirements for samples running on the :ref:`nRF9160 DK <programming_board_names>` (:ref:`nrf9160dk/nrf9160/ns <zephyr:nrf9160dk_nrf9160>`).

      +-----------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | Sample                            |   Total ROM |   Wi-Fi driver ROM                        |         nRF70 FW patch ROM |   WPA supplicant ROM |   Total RAM (incl. static heap) |   Wi-Fi driver RAM |   WPA supplicant RAM |
      +===================================+=============+===========================================+============================+======================+=================================+====================+======================+
      | :ref:`Location <location_sample>` |         247 |                                         3 |                         74 |                    0 |                             112 |                 48 |                    0 |
      +-----------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | :ref:`Scan <wifi_scan_sample>`    |         144 |                                         1 |                         28 |                    0 |                              61 |                 34 |                    0 |
      +-----------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+

   .. tab:: nRF9161 DK

      The following table lists memory requirements for samples running on the :ref:`nRF9161 DK <programming_board_names>` (:ref:`nrf9161dk/nrf9161/ns <zephyr:nrf9161dk_nrf9161>`).

      +-----------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | Sample                            |   Total ROM |   Wi-Fi driver ROM                        |         nRF70 FW patch ROM |   WPA supplicant ROM |   Total RAM (incl. static heap) |   Wi-Fi driver RAM |   WPA supplicant RAM |
      +===================================+=============+===========================================+============================+======================+=================================+====================+======================+
      | :ref:`Location <location_sample>` |         254 |                                         3 |                         74 |                    0 |                             113 |                 48 |                    0 |
      +-----------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | :ref:`Scan <wifi_scan_sample>`    |         154 |                                         1 |                         28 |                    0 |                              61 |                 34 |                    0 |
      +-----------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
