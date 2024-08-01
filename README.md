# spatialsuite-onedoor
Søg i OneDoor i Spatial Suite

### 1 Download modulet spatialsuite-onedoor:
Seneste version  
      0.1.0: https://github.com/Septima/spatialsuite-onedoor/archive/0.1.0.zip

### 2 Udpak modulet
Udpak modulet i `modules/thirdparty/septima/onedoor`

### 3 Opdatér cbinfo.xml
```xml
    <!-- ****************************************** --> 
    <!--  Septima                                   --> 
    <!-- ****************************************** --> 
    <module name="onedoor" dir="thirdparty/septima/onedoor" permissionlevel="public"/>
```

### 4 Inkludér i en profil  
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
