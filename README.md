### Build installation package for java application on MacOS, Windows

### On MacOS
javapackager -deploy -native -outdir . -outfile Jpatchaca.app -srcfiles jpatchaca.jar -appclass main.Main  -name  "Jpatacha" -title "Jpatchaca" -Bicon=ShowTime.icns

### On Windows
javapackager -deploy -native msi -outdir . -srcfiles jpatchaca.jar -appclass main.Main -name  "Jpatacha" -title "Jpatchaca" -BshortcutHint=true -Bicon=ShowTime.ico