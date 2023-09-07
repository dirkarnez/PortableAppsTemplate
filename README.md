PortableAppsTemplate
====================
### Prerequisites
- [NSIS Portable](https://portableapps.com/apps/development/nsis_portable)
- [PortableApps.com Launcher](https://portableapps.com/apps/development/portableapps.com_launcher)
- Knowing what registry / IO operations target apps need to be hooked

### How to make Portable Apps
1. Create a new repo base on this
2. Rename and edit `App/AppInfo/Launcher/StaticServerPortable.ini`, named it with same name as `AppID` is fine
3. Edit `App/AppInfo/appinfo.ini`
4. Optional / custom / advanced scripting on `App/AppInfo/Launcher/Custom.nsh`, leave it as it is if nothing to do
5. Run PortableApps.com Launcher wizard and follow the wizard GUI
