Configuration XML to remove of Microsoft Office 2013 products. 
## Uninstall-VisioStd2013-MSI
### Manual instructions
1. Add the XML file to ```C:\Program Files (x86)\Common Files\Microsoft Shared\OFFICE15\Office Setup Controller```
2. Open an elevated command prompt and change directory to the directory from step 1. ```CD C:\Program Files (x86)\Common Files\Microsoft Shared\OFFICE15\Office Setup Controller```
3. Use the below command to uninstall Visio Professional 2013 MSI
```setup.exe /uninstall VISPRO /dll OSETUP.DLL /config Uninstall-VisioPro2013-MSI.xml```
