# LOADZ Apk publish instruction
```
- Make sure to use the right branch if you're making a new version for the big display use the /mainBigDisplay if it's for the small one use the /main
  ```
## Build an apk with android studio

```
- First you need to build a release apk after you change the build name and version like this example :
  "versionCode 15"
  versionName "1.0.15"
  
- After you generate a new build that have this format like a name "loadz-release-V{versionName}-display.apk"
  ```

## Upload an Apk to Github 

```
- Upload tha apk generated to Github Repos :
"https://github.com/souissihaythem/loadz_totem/releases "
- You need to click in "Draft a new release" and upload the apk 

![](https://github.com/souissihaythem/loadz_totem/blob/main/screenshot/screenshot_1.png?raw=true)
- Fill all instruction and attach your apk in this release :  

![](https://github.com/souissihaythem/loadz_totem/blob/main/screenshot/screenshot_4.png?raw=true)
```

## Change  ChangeLog file

```
- Update the change log file with the last apk Info : 

latestVersion
latestVersionCode
FolderName  (here we have : v1.0.15)
apk name (here we have : loadz-release-V1.0.15.apk)
and save all change

![](https://github.com/souissihaythem/loadz_totem/blob/main/screenshot/screenshot_3.png?raw=true)
```
