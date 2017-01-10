# WLA Curriculum

## Courses
\[The HTML and PDF links are the same content just in different file formats\]
- English Language Arts I [\[HTML\]](https://stemlyorg.github.io/curriculum/courses/EnglishLanguageArts1/) [\[PDF\]](https://stemlyorg.github.io/curriculum/courses/EnglishLanguageArts1/index.pdf)
- Algebra I [\[HTML\]](https://stemlyorg.github.io/curriculum/courses/Algebra1/) [\[PDF\]](https://stemlyorg.github.io/curriculum/courses/Algebra1/index.pdf)
- Advanced Math I [\[HTML\]](https://stemlyorg.github.io/curriculum/courses/AdvancedMath1/) [\[PDF\]](https://stemlyorg.github.io/curriculum/courses/AdvancedMath1/index.pdf)
- Advanced Math II [\[HTML\]](https://stemlyorg.github.io/curriculum/courses/AdvancedMath2/) [\[PDF\]](https://stemlyorg.github.io/curriculum/courses/AdvancedMath2/index.pdf)
- Integrated and Experimental Sciences I [\[HTML\]](https://stemlyorg.github.io/curriculum/courses/IESciences1/) [\[PDF\]](https://stemlyorg.github.io/curriculum/courses/IESciences1/index.pdf)
- Computer Science and Technology I [\[HTML\]](https://stemlyorg.github.io/curriculum/courses/CS1/) [\[PDF\]](https://stemlyorg.github.io/curriculum/courses/CS1/index.pdf)
- Leadership Education and Development I [\[HTML\]](https://stemlyorg.github.io/curriculum/courses/Lead1/) [\[PDF\]](https://stemlyorg.github.io/curriculum/courses/Lead1/index.pdf)
- World History I (Pre-AP) [\[HTML\]](https://stemlyorg.github.io/curriculum/courses/WH1/) [\[PDF\]](https://stemlyorg.github.io/curriculum/courses/WH1/index.pdf)

## Workflow

### Uploading Documents

- For the example, we are using this [document](https://docs.google.com/document/d/1c1XubX4diXcQmJHfrPOZzlITQ9MZR8dclSo_v7J-JAw/edit?usp=sharing), which is named `WLAEnglishLanguageArtsCourseMap`
- Download the document from Google docs as `.HTML` and `.PDF`.
- Create a course inside the `courses` folder.
  - Example: `mkdir -p courses/EnglishLanguageArtsI` 
- Move the HTML files and PDF file into that course folder
  - Example:
    - Move PDF: `mv ~/Downloads/WLAEnglishLanguageArtsCourseMap.pdf courses/EnglishLanguageArtsI`
    - Rename PDF `mv courses/EnglishLanguageArtsI/WLAEnglishLanguageArtsCourseMap.pdf courses/EnglishLanguageArtsI/index.pdf`
    - Move HTML: `mv ~/Downloads/WLAEnglishLanguageArtsCourseMap/* courses/EnglishLanguageArtsI`
    - Renamed HTML: `mv courses/EnglishLanguageArtsI/WLAEnglishLanguageArtsCourseMap.html courses/EnglishLanguageArtsI/index.html`



#### License
Creative Common License
