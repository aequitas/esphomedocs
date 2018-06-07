Changelog
=========

Version 1.7.0
-------------

- The :doc:`/esphomeyaml/components/deep_sleep` now has a ``wakeup_pin_mode`` option for the ESP32. This option
  can be used to tell esphomelib what to do if the wakeup pin is already in the wakeup level when attempting
  to enter deep sleep.

Breaking Changes
~~~~~~~~~~~~~~~~

- Fixed the :doc:`SHT3x-D </esphomeyaml/component/sensor/sht3xd>` component and removed the ``accuracy``
  parameter. The accuracy now defaults to ``HIGH``.

