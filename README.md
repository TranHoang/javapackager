### Build installation package for java application on MacOS, Windows

### On MacOS

```
javapackager -deploy -native -outdir . \
    -outfile Jpatchaca.app -srcfiles jpatchaca.jar -appclass main.Main \
    -name  "Jpatacha" -title "Jpatchaca" -Bicon=ShowTime.icns \
```

### On Windows

```
javapackager -deploy -native msi \
    -outdir . -srcfiles jpatchaca.jar -appclass main.Main \
    -name  "Jpatacha" -title "Jpatchaca" \
    -BshortcutHint=true -Bicon=ShowTime.ico
```

### Reference link
http://include.aorcsik.com/2014/09/19/installing-java-on-mac-os-10-10-yosemite-beta/
https://docs.oracle.com/javase/8/docs/technotes/tools/windows/javapackager.html