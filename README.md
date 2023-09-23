# Latex template to create a sushi order sheet
[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5386565587824f159238f15e7043687c)](https://app.codacy.com/gh/R0mb0/Sushi_Order_Sheet/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Compilation_Test](https://github.com/R0mb0/Sushi_Order_Sheet/actions/workflows/Compilation_Test.yml/badge.svg)](https://github.com/R0mb0/Sushi_Order_Sheet/actions/workflows/Compilation_Test.yml)

### Demo images:
-   ![With_annotation_column](https://github.com/R0mb0/Sushi_Order_Sheet/blob/main/ReadMe_Images/With_annotation_column.png)  
-   ![Without_annotation_column](https://github.com/R0mb0/Sushi_Order_Sheet/blob/main/ReadMe_Images/Without_annotation_column.png)  

---
## How to create your personal sushi order sheet online for free! 
1.  Fork this repository.
2.  Rename the repository as you want and change the description then Fork it!
3.  Upload your images using GitHub into the images folder!
   1.  Access the folder from main page.
   2.  "Add file" -> "Upload files" -> drag and drop your images here.
   3.  At the end, "Commit changes".
4.  Overwrite demo images with yours into the LaTeX document (if necessary change the parameters down the images names to center its).
   1.  Access the "Order_Sheet" folder from main page and click on "Order_Sheet.tex".
   2.  Now click on "Edit this file" (the pencil on top right).
   3.  Overwrite demo backgrund image with your own (around code line 61).
   4.  Do the same with the circular logo (around code line 65).
   5.  If you want the "annotation column" in document, set "annotationColumn" variable (around code line 58) to "true".
   6.  Now "Commit chages".
5.  Wait 2 minutes, got to "Actions" -> "Compile" -> click on the last one (look at the date on right) -> scroll down the page and click on "artifact file".  
6.  Done! now you have your suhi order sheet.

---

# License
Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
