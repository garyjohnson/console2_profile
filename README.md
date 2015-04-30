Symlink console.xml to %APPDATA%/Console/console.xml. 

From git project root:

```
fsutil hardlink create %APPDATA%\Console\console.xml console.xml
```
