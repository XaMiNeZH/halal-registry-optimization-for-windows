# halal-registry-optimization-for-windows
### This is a registry optimization pack made by me that can improve your Windows performance.
Please make a *restore point* and *take ownership* of `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\BackgroundModel\BackgroundAudioPolicy before applying.`

-**Here is a list of tweaks I have done:**
Improves shutdown speed (Does not allow Windows to clean page file at shutdown, app and service timeout has been decreased)
Disables the delay when launching apps on start-up
Disables Power Throttling (not recommended on laptops)
Changes SvcHostSplitThresholdInKB to reduce processes
Enables Hardware accelerated GPU scheduling
Improves GPU and USB latency
Re-enables start-up app support if messed up by something else
Partially disables Windows Hibernation (You may still have to use powercfg /h off if nothing changed)
Changes memory related stuff like Non Paged Pool Quota, Paged Pool Size, etc
Improves touch latency (Not 100% sure, in HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\TouchPrediction)
Allows the operating system to handle 65536 GDI elements
Disables Multi Plane Overlay (MPO)
Reduces Menu delay
Partially disables Windows' fast startup feature (that apparently uses Hibernation)
Improves overall system responsiveness
Changes Lazy Mode Timeout (only happens when idling doing nothing)
Changes GPU/CPU priority for certain tasks (like games, videos, etc)
Does not allow Windows to block downloaded items (SaveZoneInformation)
Re-enables the Windows Network Data Usage Monitoring Driver (Ndu) because task manager takes forever to close if it's disabled
