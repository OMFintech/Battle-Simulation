If your machine is failing to compile TrackWhileScan.uproject due to missing modules:

+Install Visual Studio 2019 *(2022 will not work)*
+From the Visual Studio installer, make sure you have these components installed:
++Windows 10 SDK (10.0.18362.0)
++MSVC v142 - VS2019 C++ x64/x86 build tools (v14.29-16.11)
+ Install UnrealVS extension from *C:\Program Files\Epic Games\UE_5.0\Engine\Extras\UnrealVS\VS2019*

Once you've completed those steps, try opening the TrackWhileScan.uproject file.

If it still fails, right click on TrackWhileScan.uproject and click "generate Visual Studio project files". 

TrackWhileScan.sln will appear. Run that file, make sure Visual Studio is set to "release" mode *(not debug)*, and hit "build". 

Now you should be able to run the TrackWhileScan.uproject file.