# js-parseMultipartRelated
The DICOMweb RESTFul API of WADO-RS response Multipart/related data that browser cannot download
the DICOM object directly.
This example demos how to download DICOM file from Orthanc with DICOMweb WADO-RS API.

## postman retrieve DICOM object
![postman-wado-rs](./pictures/postman-wado-rs.jpg)

## DEMO
![demo](./pictures/demo.gif)

## Note
### CORS
![CORSERROR](./pictures/cors-error.jpg)
Disable chrome web security to use this example.
![diable-chrome-web-security](./pictures/disable-chrome-web-security.jpg)
```
Add command after chrome path.

"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-web-security --user-data-dir="C:/ChromeDevSession"
```