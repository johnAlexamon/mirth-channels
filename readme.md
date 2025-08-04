# wrapPdf2DCM v1.0.0

`wrapPdf2DCM` is a simple Mirth Connect channel that reads PDF and metadata from a specified folder, wraps the PDF into a DICOM file using the metadata, and writes the result back to the folder structure.

---


# readDCMfromDiskAndSend v1.0.0

This Mirth Connect channel reads `.dcm` files from disk and sends them to a configured DICOM endpoint using the C-STORE protocol.


### You can use these two channels together to wrap pdf files and send them to a PACS

Place Your JAR File in the Right Location
Recommended: MIRTH_HOME/custom-lib/ (e.g., /opt/mirth-connect/custom-lib/ or C:\Program Files\Mirth Connect\custom-lib\)
Restart the Mirth Connect service (not just the Administrator UI).
