#in steam Forged Alliance run args paste:
 
PROTON_NO_ESYNC=1, PROTON_USE_WINED3D=1, PROTON_DUMP_DEBUG_COMMANDS=1 %command%
 
#in the console run:  
 
protontricks 9420 dlls d3dx9
protontricks 9420 dlls xact
 
 
#desktop file contents:
 
#!/usr/bin/env xdg-open
[Desktop Entry]
Version=1.5.0
Type=Application
Exec=bash -c "cd /home/t/faf; export INSTALL4J_JAVA_HOME=/usr/lib/jvm/java-15-openjdk-amd64/; ./downlords-faf-client"
Name=FAF
Comment=Forged Alliance Forever Client
Icon=/home/t/.local/share/icons/faf.png


copy by https://pastebin.com/n39m8bZ7


how to start in steam

I also forced the proton version to : 3.16-4
