# Windows-installer-for-OSGeoServer-2.16.1
# Process
1.	For the first step I downloaded and installed NSIS along with  NSIS Access Control Plugin.
2.	Then I extracted the plugin zip file.
3.	I copied the AccessControl.dll file that is present in the Plugins directory to C:\Program Files (x86)\NSIS\Plugins\x86-ansi and the AccessControl.dll that was present under the Unicode/Plugin to C:\Program Files (x86)\NSIS\Plugins\x86-unicode. It is important to place the right file in the right place.
4.	Then I downloaded the Nightly Development Build and the GeoServer 2.16.1 from https://build.geoserver.org/geoserver/master/geoserver-master-latest-bin.zip and https://github.com/geoserver/geoserver/archive/2.16.1.zip and extracted them.
5.	Then I copied all the files from the extracted folder of GeoServer 2.16.1 under src/release/installer/win to the extracted folder of Nightly Development Build at the same level where start.java file is located.
![alt text](https://raw.githubusercontent.com/TanvirSingh007/Windows-installer-for-OSGeoServer-2.16.1/master/images/1.png)
![alt text](https://raw.githubusercontent.com/TanvirSingh007/Windows-installer-for-OSGeoServer-2.16.1/master/images/2.png)







6.	Once everything was copied, I right clicked on the GeoServerEXE.nsi file and clicked on Compile NSIS Script.
![alt text](https://raw.githubusercontent.com/TanvirSingh007/Windows-installer-for-OSGeoServer-2.16.1/master/images/3.png)
7.	At this time, the program started to compile.
8.	After the compilation was finished, the final geoserver-2.16.1.exe file is created and is ready to be used.
![alt text](https://raw.githubusercontent.com/TanvirSingh007/Windows-installer-for-OSGeoServer-2.16.1/master/images/4.jpg)
