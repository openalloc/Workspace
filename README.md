# Workspace

Pre-fab Xcode workspace for `openalloc` projects.

<img src="https://github.com/openalloc/Workspace/blob/main/Images/xcode.png" width="800" height="512"/>

This is _optional_. You can always set up your own Xcode workspace
independently.

# Setup

Clone all the repositories (including `Workspace`) at the same level in
your project directory.  It should then look something like this:

```bash
$ ls -a1

AllocData
DetailerDemo
FINporter
FINporterAllocSmart
FINporterCLI
FINporterChuck
FINporterFido
FINporterTabular
FlowAllocHigh
FlowAllocLow
FlowAllocatorApp
FlowBase
FlowStats
FlowUI
FlowViz
FlowWorthApp
FlowWorthLib
FlowXCT
SwiftCompactor
SwiftDetailer
SwiftDetailerMenu
SwiftModifiedDietz
SwiftNiceScale
SwiftNumberPad
SwiftRegressor
SwiftSeriesResampler
SwiftSideways
SwiftSimpleTree
SwiftTabler
SwiftTextFieldPreset
TablerCoreDemo
TablerDemo
Workspace
openalloc.github.io
.github
```

Then you can open the workspace with: 

```bash
$ open Workspace/openalloc.xcworkspace
```

## See also

This repository is a member of the _OpenAlloc Project_.

* [_OpenAlloc_](https://openalloc.github.io) - product website for all the _OpenAlloc_ apps and libraries
* [_OpenAlloc Project_](https://github.com/openalloc) - Github site for the development project, including full source code

## License

Copyright 2023 OpenAlloc LLC

All application code is licensed under the [Mozilla Public License 2](https://www.mozilla.org/en-US/MPL/2.0/), except where noted in individual modules.
