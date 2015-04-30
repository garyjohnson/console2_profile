Symlink console.xml to %APPDATA%/Console/console.xml

```
fsutil hardlink create %APPDATA%\Console\console.xml console.xml
```
