# augmented-edition
a companion application for reading books

### Overview
Augmented Edition (tentatively named "Relativity") is a mobile application designed to be used while reading a book. Endnotes, footnotes, commentary, variants and textual notes (for a scholarly edition) can be accessed on the mobile device just by pointing the device's camera at the relevant page of the book, obviating the need to thumb back and forth through different sections of the book while reading.

### Design Ideas
- at its most basic level or for prototyping, QR codes could be added to pages and bring up a relevant web page with the appropriate notes / apparatus
- eventually, object recognition (perhaps Tensorflow Object Detection API) or automated OCR could be used to scan the pages without the need for a QR code or unique identifier

4/17/2018 Decided to make this repo a prototype QR-based project. Object/image recognition to scan pre-existing book pages will be incorporated in a later and separate repo
