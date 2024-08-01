# spatialsuite-onedoor
Søg i OneDoor i Spatial Suite

### Download modulet spatialsuite-onedoor:
Seneste version  
      0.1.0: https://github.com/Septima/spatialsuite-onedoor/archive/0.1.0.zip

### Udpak modulet

Udpak modulet i `modules/thirdparty/septima/onedoor`

### Opdatér cbinfo.xml
```xml
    <!-- ****************************************** --> 
    <!--  Septima                                   --> 
    <!-- ****************************************** --> 
    <module name="onedoor" dir="thirdparty/septima/onedoor" permissionlevel="public"/>
```

### Inkludér i en profil  
Husk at udfylde [XXX] med korrekt info  
```xml
        <tool module="onedoor" name="onedoor-plugin">
            <jsonconfig>
                {
                    "host": "[API Host]",
                    "organisation": "[Organisation]",
                    "configuration": "[Konfiguration]"
                }
            </jsonconfig>
        </tool>
```
