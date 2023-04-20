# Workspace

Pre-fab Xcode workspace for `open-trackers` projects.

<img src="https://github.com/open-trackers/Workspace/blob/main/Images/xcode.png" width="800" height="512"/>

This is _optional_. You can always set up your own Xcode workspace
independently.

# Setup

Clone all the repositories (including `Workspace`) at the same level in
your project directory.  It should then look something like this:

```bash
$ ls -a

.github
Daily-Calorie-Tracker-Plus-App
Daily-Calorie-Tracker-Watch-App
DcaltLib
DcaltUI
GroutLib
GroutUI
Gym-Routine-Tracker-Plus-App
Gym-Routine-Tracker-Watch-App
Task-Routine-Tracker-Plus-App
Task-Routine-Tracker-Watch-App
TrackerLib
TrackerUI
TroutLib
TroutUI
Workspace
open-trackers.github.io
```

Then you can open the workspace with: 

```bash
$ open Workspace/open_trackers.xcworkspace
```

## License

Copyright 2023 OpenAlloc LLC

All application code is licensed under the [Mozilla Public License 2](https://www.mozilla.org/en-US/MPL/2.0/), except where noted in individual modules.
