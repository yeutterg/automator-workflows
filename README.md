# MacOS Automator Workflows

Updated 2018-01-17

## Overview

[Automator](https://macosxautomation.com/automator/) is an application bundled with MacOS that allows you to save time by automating repetitive, time-consuming tasks. 

Some examples include:
* Splitting and combining PDFs
* Batch resizing images
* Converting a PDF into images
* Looking up a highlighted word using the Dictionary app
* Counting highlighted words

![Example Workflow](./Images/Resize.png)

You can perform all these actions without even opening applications. Just right-click (control-click) a file or folder, and valid operations will be found in the Services menu. The services work system-wide, including in Finder and text areas.

This page details services I've developed that you can install and use on your own Mac.

## Table of Contents
* [Installation and Use](#installation)
* [Image Services](#image)
* [PDF Services](#pdf)
* [File Services](#file)
* [Text Services](#text)

## Installation and Use

1. From this page, download the workflows by clicking Clone or Download > Download ZIP.

![GitHub Download](./Images/Install_DownloadGitHub.png)

2. Find the zip file you just downloaded. Extract it by double-clicking.

3. Within the extracted zip folder, navigate to the Workflows folder. Select all the workflows you want to install. Command-C to copy those workflows.

![Workflows in Finder](./Images/Install_FinderWorkflows.png)

4. From Finder, hold down the option (alt) key and click the Go menu at the top of your screen. Click Library. 

![Installation Go Menu](./Images/Install_GoMenu.png)

5. In the Library folder, navigate to Services. Command-V to paste the workflows into the Services folder.

![Installation Services Folder](./Images/Install_Services.png)

You should be all set. See the descriptions and videos below for more info on how to use these workflows

If you find a bug or need help, please [contact me](https://gregyeutter.com/contact/) or report an issue on this page.

## Image Services

### Resize Image

### Rotate Clockwise

### Rotate Counterclockwise

### Duplicate as PNG

### Duplicate as JPG

## PDF Services

### Split PDF

### Split PDF into Images

### Combine PDFs

Combines multiple selected PDF files into one.

### Extract PDF Text

Extracts the text from a PDF and saves it to a text file of the same name. Note that the PDF must have OCR enabled for this to work.

## File Services

### New File

This creates an empty file in the current directory. You specify the filename, including extension, in the dialog box that appears. Note that this only works for Unicode text file formats like .txt, .md, and .html. It will not work for something like .xlsx or .docx.

### Add YYYY-MM-DD Prefix

This adds today's date in YYYY-MM-DD format as a prefix to the selected filename(s).

## Text Services

### Count Words

Counts the number of highlighted words.

### Get Definition

Opens Dictionary.app with the highlighted text as the query. This gives you more options that force-clicking or right-clicking and selecting Look Up.