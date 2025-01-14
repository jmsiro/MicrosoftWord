



# Microsoft Word
  
Module to work with text files using Microsoft Word. Create and edit word documents, work with tables, format your texts and more.  

*Read this in other languages: [English](README.md), [Português](README.pr.md), [Español](README.es.md)*

## How to install this module
  
To install the module in Rocketbot Studio, it can be done in two ways:
1. Manual: __Download__ the .zip file and unzip it in the modules folder. The folder name must be the same as the module and inside it must have the following files and folders: \__init__.py, package.json, docs, example and libs. If you have the application open, refresh your browser to be able to use the new module.
2. Automatic: When entering Rocketbot Studio on the right margin you will find the **Addons** section, select **Install Mods**, search for the desired module and press install.  


## Overview


1. New Document  
Create a new word document

2. Open Document  
Open a Word document.

3. Read Document  
Extract text from a Word document

4. Get paragraphs  
Get the list of paragraphs that make up a Word document in dictionary format {number: text}.

5. Get text range  
Find text in a document and get its position range.

6. Write in Document  
Write in a Word document.

7. Copy and paste text  
Copy and paste text between ranges in a Word document and paste it in another document

8. No clipboard copy/paste  
Copy and paste text between ranges in a Word document and paste it in another document without using OS clipboard.

9. Copy text  
Copy text to clipboard between ranges in a Word document

10. Paste text  
Paste text from clipboard in a Word document

11. Count characters  
Count characters in a specific paragraph

12. Add table  
Add table in a Word document.

13. Read Tables  
Extract data from the Tables in the document

14. Edit table  
Edit table from a Word document.

15. Copy and Paste table  
Select a table from a word document, copy and paste it into the same document or another one.

16. Update linked fields  
Update linked fields (e.i. Excel spreadsheets)

17. Add Page  
Add a new page to the document

18. Add Picture  
Add an image to the document.

19. Convert to PDF  
Convert Word document to PDF.

20. Locate Text in Paragraph  
Locate in which paragraph there is an indicated text.

21. Count Paragraphs  
Count the number of paragraphs in the document. Includes table fields.

22. Replace text in paragraph  
Replace the text of a paragraph.

23. Delete paragraph  
Delete a paragraph from the document. If tables are included, the Find Text in Paragraph command should be used to locate the paragraph to be deleted. Returns the deleted text.

24. Add text at the end of bookmark  
Add text at the end of bookmark.

25. Save document  
Extract text from file.

26. Close Document  
Close the document that is running  



### Changes
Thu Jul 21 01:32:22 2022  Merge branch qa into branch-nico

----
### OS

- windows

### Dependencies
- [**pywin32**](https://pypi.org/project/pywin32/)
### License
  
![MIT](https://camo.githubusercontent.com/107590fac8cbd65071396bb4d04040f76cde5bde/687474703a2f2f696d672e736869656c64732e696f2f3a6c6963656e73652d6d69742d626c75652e7376673f7374796c653d666c61742d737175617265)  
[MIT](http://opensource.org/licenses/mit-license.ph)