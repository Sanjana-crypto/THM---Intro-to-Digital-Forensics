# Intro to Digital Forensics - TryHackMe

## Overview

Completed the **Intro to Digital Forensics** room on TryHackMe. This room introduced the fundamentals of digital forensics, the forensic investigation process, and basic evidence analysis techniques using real forensic tools.

## Objectives

* Understand the concept of Digital Forensics
* Learn the Digital Forensics Investigation Process
* Analyze metadata from PDF documents
* Extract EXIF data from image files
* Perform GPS-based geolocation analysis

## Tools Used

* ExifTool
* PDFInfo
* Linux Terminal
* Google Maps

## Practical Activities

### PDF Metadata Analysis

Used `pdfinfo` to analyze a PDF ransom letter and extract metadata such as:

* Author
* Creator
* Producer
* Creation Date

Example Command:

```bash
pdfinfo ransom-letter.pdf
```

### Image EXIF Analysis

Used `exiftool` to extract metadata from an image file.

Information identified:

* Camera Model
* GPS Coordinates
* Date and Time Taken
* Image Metadata

Example Command:

```bash
exiftool letter-image.jpg
```

### GPS Geolocation Investigation

Extracted GPS coordinates from image metadata and used mapping services to identify the location where the image was taken.

## Skills Learned

* Digital Forensics Fundamentals
* Evidence Collection and Preservation
* Chain of Custody
* Metadata Analysis
* PDF Forensics
* EXIF Analysis
* GPS Geolocation
* Digital Evidence Investigation

## Key Takeaway

Digital Forensics focuses on collecting, preserving, analyzing, and reporting digital evidence while maintaining the integrity of the original data. This room provided hands-on experience with forensic tools and metadata analysis techniques used in real-world investigations.


