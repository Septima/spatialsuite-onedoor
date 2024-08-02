Søg i OneDoor i Spatial Suite

Udpak modulet
  Udpak modulet i `modules/thirdparty/septima/onedoor`

Opdatér cbinfo.xml
    <!-- ****************************************** --> 
    <!--  Septima                                   --> 
    <!-- ****************************************** --> 
    <module name="onedoor" dir="thirdparty/septima/onedoor" permissionlevel="public"/>

Inkludér i en profil - Husk at udfylde [XXX] med korrekt info  
    <tool module="onedoor" name="onedoor-plugin">
        <jsonconfig>
            {
                "host": "[API Host]",
                "organisation": "[Organisation]",
                "configuration": "[Konfiguration]"
            }
        </jsonconfig>
    </tool>

