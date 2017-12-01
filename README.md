# AndroidTV-AOSP
Definitions for generic x86 Android TV device target
```
  <remove-project name="bootable/newinstaller" />
  <remove-project name="platform/packages/apps/BasicSmsReceiver" />
  <remove-project name="platform/packages/apps/Browser2" />
  <remove-project name="platform/packages/apps/Calendar" />
  <remove-project name="platform/packages/apps/Camera2" />
  <remove-project name="platform/packages/apps/Contacts" />
  <remove-project name="platform/packages/apps/DeskClock" />
  <remove-project name="platform/packages/apps/DevCamera" />
  <remove-project name="platform/packages/apps/Dialer" />
  <remove-project name="platform/packages/apps/DocumentsUI" />
  <remove-project name="platform/packages/apps/Eleven" />
  <remove-project name="platform/packages/apps/Email" />
  <remove-project name="platform/packages/apps/ExactCalculator" />
  <remove-project name="platform/packages/apps/Gallery2" />
  <remove-project name="platform/packages/apps/HTMLViewer" />
  <remove-project name="platform/packages/apps/Launcher3" />
  <remove-project name="platform/packages/apps/Messaging" />
  <remove-project name="platform/packages/apps/Phone" />
  <remove-project name="platform/packages/apps/Settings" />
  <remove-project name="platform/packages/apps/Taskbar" />
  <remove-project name="platform/packages/providers/UserDictionaryProvider" />
  <remove-project name="platform/packages/screensavers/Basic" />
  <remove-project name="platform/packages/screensavers/PhotoTable" />
  <remove-project name="platform/packages/services/Analytics" />

  <remote name="kyvaith" fetch="https://github.com/kyvaith/"  />
  <project path="bootable/newinstaller" name="bootable/newinstaller" clone-depth="1" revision="oreo-x86" remote="kyvaith" />
  <project path="vendor/intel/houdini" name="vendor/intel/houdini" clone-depth="1" revision="oreo-x86" remote="kyvaith" />
  <project path="vendor/opengapps/build" name="aosp_build" clone-depth="1" revision="oreo" remote="kyvaith" />
  <project path="vendor/opengapps/sources/all" name="all" clone-depth="1" revision="master" remote="kyvaith" />
  <project path="vendor/opengapps/sources/x86" name="x86" clone-depth="1" revision="master" remote="kyvaith" />
  <project path="device/generic/atv" name="device/generic/atv" clone-depth="1" revision="oreo-x86" remote="kyvaith" />
  ```
