# Ppt_to_pdf_applescript

Project was created in macOS big sur environment.

Use Automator to attach a folder action to a folder you want to save .ppt or .pptx
files to. The files will be automatically opened in PowerPoint and saved as pdfs of the same name in a destination folder. 

**Automator actions:
  -pause (for 5 seconds) 
  -filter finder items
    where any of the following are true:
      file extension contains pptx
       file extension contains ppt
  -Run applescript
