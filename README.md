# CNC for Rhino 8 — Downloads
Created October 20, 2026 (America/Chicago)

This repository contains compiled Windows plug-in downloads. No GitHub account is needed. The source code is maintained privately.

Download the latest package from [Releases](https://github.com/asher-netizen/RhinoCncPlugin-Releases/releases/latest). Save and close all Rhino windows, extract the complete ZIP, then double-click **Install-CncPlugin.cmd**. Open Rhino 8 and run **CNC**. The ZIP includes plain installation instructions and checksums.

You need your own licensed Rhino 8 for Windows x64. Simulation also requires the [Microsoft .NET 8 x64 runtime](https://dotnet.microsoft.com/download/dotnet/8.0), version 8.0.14 or a later .NET 8 patch. No developer tools or GitHub credentials are needed.

Automatic stable updates are on by default. CNC checks shortly after Rhino starts and every six hours while it is running. Verified updates are kept in a separate folder and load after the next full Rhino restart. It never forces a restart or closes your files. The Updates tab has the running/next-start versions, status, an off switch and cancel controls. Rollback retains earlier builds and switches automatic downloads off to preserve your choice.

The [stable update feed](https://raw.githubusercontent.com/asher-netizen/RhinoCncPlugin-Releases/main/latest.json) records the exact version, package checksum and source revision. Versioned package bytes are preserved. Source commits alone do not replace downloads; publication follows software checks and package review.

Current qualification limits: background update, package checks and isolated staging tests are distinct from native Rhino panel/restart checks and physical machining. Check each release's notes. Review toolpaths, cutter and work setup before machining.
