**Date**: Oct 02, 2025 15:59
**Status**: #working-on
**Links**: [[To Organize]] 

Project Goal**  
Convert Radiology textbooks to Anki flashcards efficiently to reclaim study time, prioritizing family and meaningful activities.  

**Initial Approach**  
Leveraged custom GPTs to extract text/images from PDF textbooks into Anki, but encountered inefficiencies: manual image pasting, slow processing (1-3 cases at a time), and inability to achieve a one-click solution.  

**Python Solution**  
Shifted focus to Python using PyMuPDF library for data extraction. Developed image and text extractor scripts, with ChatGPT assisting as a coding guide for a non-programmer.  

**Key Challenges**  
- Image extraction failures due to inconsistent case-number formatting.  
- Random color inversion in extracted images.  
- Text isolation using regular expressions (targeting questions, answers, diagnoses).  
- Automating image count per case for accurate HTML link generation in flashcards.  

**Anki Note Type Design**  
Created a custom note type featuring:  
- Image galleries for multi-image cases.  
- Dropdown menus for questions/answers to reduce clutter.  
- Cloze deletions for diagnoses.  
- Color inversion toggle for radiology-specific use.  

**Script Evolution**  
- **Image Extractor**: Named images, generated JSON inventory per diagnosis.  
- **Text Extractor**: Applied regex to isolate content, formatted HTML links based on image counts.  
- **CSV Converter**: Integrated outputs for seamless Anki upload.  

**Limitations**  
- Struggled with multiple cases per page.  
- Inflexible across textbook series due to formatting variations (e.g., missing "diagnosis" labels).  

**Streamlined Solution**  
Redesigned approach by:  
- Identifying universal textbook elements for consistent regex targeting.  
- Implementing uniform tagging and simplified image naming.  
- Adding logic to separate multi-case images.  
- Packaging scripts into a one-click app for broader applicability.  

**Final Outcome**  
Successfully converted entire textbooks into Anki flashcards with minimal manual effort, significantly enhancing study efficiency for medical trainees.  

**Title**  
Automated Textbook-to-Anki Conversion for Medical Training  

**Tags**  
AI automation, Python programming, Anki flashcards, medical education, data extraction, PyMuPDF, regular expressions, radiology, study efficiency

## References: [YouTube](https://www.youtube.com/watch?v=miq9z2Nkngo)
