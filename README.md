# CrashPlan Dark Icon

CrashPlan icons for people who uses dark menubar on macOS.

# Installation

```bash
$ git clone git@github.com:ivanwhm/crashplan-dark-icon.git
$ cp dark-version/*.png /Applications/CrashPlan.app/Contents/Helpers/CrashPlan\ menu\ bar.app/Contents/Resources/
$ killall "CrashPlan menu bar"
$ open -a "CrashPlan menu bar"
```

To restore the original icons, reinstall the entire application or run the following command:

```bash
$ cp original-version/*.png /Applications/CrashPlan.app/Contents/Helpers/CrashPlan\ menu\ bar.app/Contents/Resources/
$ killall "CrashPlan menu bar"
$ open -a "CrashPlan menu bar"
```

Please open an issue if you have any problem with it.