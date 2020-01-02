# dms
Personal Document Managment Sytetem

This project is for a simple personal document managment system...the active code will run on a pi4 (or possibly older but I will be working on a pi4)...and storage for documents will be on cloud....this is all still a work in progress and at the moment there is nothing working to see!

Some aims are:-

1. All documents stored encrypted.
2. Encryption keys not available to system unless user logged in....and user has chosen to share keys for the session/action.
3. Content to be pdf file format.
4. Content to be creatable searchable and retrievable via Web front end.

So far I have tested tesseract OCR and that seems to be capable of doing a good job so for mow that is my choice.
I am also using django to build web front end and templates from bootstrap4.
