# Code Refactor Challenge

In this project, we were given a codebase for a company website that requires improvement. The company (our client) would like their webpage to meet accessibility standards so that it is optimized for search engines. Throughout this task, we will also be looking for ways to improve the quality of the codebase by making it "cleaner".

The first step of this project was cloning the starter code locally and creating a GitHub repository. This is an important step because it allows me to share my work with others who may need to review or collaborate with me. The link to that repository is: https://github.com/randiferous/code-refactor-challenge.git.

Next, we get into the coding. The following is a list of changes I made as required by the "Acceptance Criteria" or that I deemed necessary for the improvement of the codebase:

- Changed all "div" and "span" tags to more descriptive elements, such as "nav", "aside", and "article" (among others).

- In order to complement the previous changes, I had to correct an element in the stylesheet from "div" to "nav" so that its properties are still applied.

- Created a website title, "Explore Your Horiseon".

- Included an alt attribute for all body images. Those in the main section received detailed descriptions.

- Added an id element to the Search Engine article so that the navigation button now directs users to it.

- I renamed the classes of the "benefits" section articles so that they are all the same, and then consolidated the style selectors for those articles. This was done to avoid repetition of identical styling properties.

- I did the same thing with the classes of the "content" section, renaming those to "services", and consolidating the appropriate selectors.

- The style selectors for the "content" section was also moved up in the stylesheet so that it aligns with the structure of the corresponding html in relation to other elements.

- Added comments to both html and css files in order to identify the purpose of each part of the codebase.

In reflection of this project, I realize the important of having a careful eye for proper coding practice. Even codebases that "work" may not be ideal. I also gained more familiarity with various html and css terminology, and the relationship between these two languages.

Screenshot of website top half with new title: ![Alt text](https://raw.githubusercontent.com/randiferous/code-refactor-challenge/main/assets/images/screenshot-top-half.PNG)

Screenshot of website bottom half (using Search Engine navigation button): ![Alt text](https://raw.githubusercontent.com/randiferous/code-refactor-challenge/main/assets/images/screenshot-bottom-half.PNG)