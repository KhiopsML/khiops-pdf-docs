# Khiops PDF Documentation
This repository contains the source files (`docx` and `pptx`) of the Khiops PDF documentation. They
are mainly focused on the desktop applications.

# How to update to a new version
- Edit the files with the Microsoft Office suite.
- Commit and tag.
  - A release will be created.
- Create PDFs renderings PPT tutorial and upload it to the created release.
  - Beware of exporting documents in pdf format without Microsoft Purview protection
- Create a release for the tag in the Github repository.

## Why not automate ?
The only way to do this on the Github runners is with LibreOffice. And its rendering is off in
various pages.
