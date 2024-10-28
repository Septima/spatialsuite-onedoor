# spatialsuite-onedoor
Søg i OneDoor i Spatial Suite

### 1 Download modulet spatialsuite-onedoor:
Seneste version  
      0.2.1: https://github.com/Septima/spatialsuite-onedoor/archive/0.2.1.zip

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
