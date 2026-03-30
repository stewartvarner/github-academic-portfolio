# Getting Started with GitHub
## Digital Humanist's Help Desk

##  https://bit.ly/DreamLabBlog

This repository (aka. a repo; a central storage for your project's files, folders, and version history) has all the files and instructions to build a basic academic portfolio website with a home page, a teaching page, a research page, and a link to a CV [PDF].

>I recommend using Google Chrome for this exercise so you can easily use the Developer tools like "View Source" and "Inspect Elements".

## What is GitHub?

GitHub is a platform for sharing code that combines many useful tools: git (version control), Codespaces (virtual coding environment), and Pages (free web hosting). 

## Why would I use GitHub?

If you’re thinking about ways to 
1) code collaboratively, or 
2) share your code with an online community, or 
3) create your own website,
   
this introduction is for you.

## How can I use GitHub?

In this workshop, we will create GitHub accounts, learn the terms used to build foundational understanding, navigate the interface, create a simple static website using GitHub, and discuss the benefits and drawbacks of this platform.

## Create GitHub account

1. Navigate to https://github.com/.
2. Click Sign up.
3. Follow the prompts to create your personal account.
-Email
-Password (Password should be at least 15 characters OR at least 8 characters including a number and a lowercase letter.) 
-Username* (Username may only contain alphanumeric characters or single hyphens, and cannot begin or end with a hyphen. (NOTE: You will want to pick a professional username because it will be in all of your URLs))

4. Create Account>

(During sign up, you'll be asked to verify your email address. Without a verified email address, you won't be able to complete some basic GitHub tasks, such as creating a repository.)


## GitHub Pages

GitHub is a company that was acquired by Microsoft that hosts git (version control) projects online. GitHub created [GitHub Pages](https://pages.github.com/), a way to host static sites for free, usually hosted at https://_username_.github.io/_repository_. This means that they are providing free _hosting_, meaning the server space to hold all your files and a free _domain_, the address/URL where others can navigate to your content. 

## GitHub Codespaces

Based on Microsoft’s Visual Studio Code, GitHub also developed [GitHub Codespaces](https://github.com/features/codespaces), a staging area that combines the functionality of a file **Explorer**, allowing you to visualize your folder structure, a code **Editor**, allowing you to make updates, a **Source Control**, allowing you to push and pull changes from your local to remote repository, and a **Terminal**, allowing you to run actions like previewing a demo of your site on a locally hosted address.

>Typically coders using GitHub use their favorite text editor like [Sublime Text](https://www.sublimetext.com/), [Atom](https://atom-editor.cc/), or [Visual Studio Code](https://code.visualstudio.com/), and then use a graphical user interface (GUI) like [GitHub Desktop](https://github.com/apps/desktop) or their command-line interface (CLI) like **Terminal** to push and pull changes to their project. GitHub created Codespaces to allow you to do both of those things right in the browser without having to download software applications (so you can do all of this on your iPad if you want!) 


## Fork GitHub Repository

1. Either search for github-academic-portfolio in the search bar 
OR
Navigate to this URL in your web browser
[https://github.com/Makeademic/github-academic-portfolio](https://github.com/Makeademic/github-academic-portfolio) 
2. Find and select the "Fork" button near the top right
OPTIONAL: You can rename the repository for your own account
3. Select the green 🟩 "Create fork" button

## Create GitHub Pages

1. Navigate to ⚙️Settings in the top menu bar
2. Find and select the Pages button in the left sidebar
3. Click on the Branch dropdown menu that says None and change it to main
4. Select the Save button
5. This will build your GitHub pages site

## Create GitHub Codespace

1. Navigate to <>Code in the top menu bar
2. Find and select the green <>Code dropdown menu
3. Toggle from Local to Codespaces 
4. Select the green Create codespace on main button
5. This will open up a new tab in your browser and will take some time, so be patient with it. [NOTE: As of authoring this document, GitHub provides 60 free hours of Codespaces every month]
6. You should see the **Explorer** on the left (this helps you see folder hierarchy), the **Editor** on the right (this is where you can edit the code), and the **Terminal** at the bottom (this is where you can provide instructions for building a more advanced project). The far left toolbar will let you switch between options: **Explorer**, **Search**, **Source Control**, **Run and Debug**, **Extensions**, and **GitHub**.

## Edit GitHub Code

1. In the Explorer left sidebar, find and double-click index.html
2. Note the color coding: the HTML tags and CSS are in colors and the text to edit is in black
3. Scroll down to lines 138-139 in the code and edit First and LastName, PhD candidate, and Digital Humanities to match your own info

## Push GitHub Changes

1. In the far left menu, go to Source Control
2. Type the commit description “renamed homepage”
3. Select the blue Commit button
4. Select the blue Yes button in the pop up modal
5. Select the blue Sync Changes button
6. Select the blue OK button in the pop up modal
7. Exit out of GitHub Codespaces and return to your GitHub Dashboard

## View GitHub Site

1. Select the Actions button in top menu
2. This will show your pages build and deployment
3. Select the <>Code in the top menu bar
4. Select the ⚙️ gear icon next to About in the right sidebar
5. Check the Use your GitHub Pages website checkbox
6. Select the green Save changes button
7. Click on the blue link to open your site in a new tab in your browser

# CONGRATULATIONS!

### Editing Code
>Some file extensions you will want to know are: 
>- .html (Hypertext Markup Language (HTML) is the standard markup language for **documents** designed to be displayed in a **web** browser)
>- .css (Cascading Style Sheets (CSS) is a style sheet language used for specifying the presentation and **styling** of a document written in a markup language such as HTML)
>- .js (JavaScript (JS) is the programming language for creating interactive, dynamic websites)
>- .md (Markdown is a lightweight markup language for creating formatted text using a **plain-text** editor)
>- .njk (Nunjucks is a templating language for JavaScript)
>- .svg (Scalable Vector Graphics (SVG) is an XML-based vector graphics format for defining two-dimensional graphics, having support for interactivity and animation)
>- .jpg (jpg or jpeg, short for Joint Photographic Experts Group, is a compressed image format used for photos)
>- .ico (short for icon, this file format is for square icons like the favicon in your browser tab, can be based on a transparent .png (Portable Network Graphics))  

---

### Adding Files

1. Create your own CV as a .pdf and navigate to + Add File, Upload Files, to replace your own CV with the sample CV


### Editing Styles

> To find and replace, type Command+F for find, and then click the drop down arrow to the left of "Find" to show the option for "Replace".

#### Colors
>Hexcode is a color system on a scale from 0-9,A-F that designates a color RRGGBB. You can calculate a color using this [HTML Color Picker](https://www.w3schools.com/colors/colors_picker.asp) or you can type in a [HTML color](https://www.w3schools.com/colors/colors_names.asp)

#### Fonts 

14. To add Google Fonts, go to [https://fonts.google.com/](https://fonts.google.com/), browse/search for fonts, select as many fonts as you want, click the blue 🟦 "Get font" button, click the blue 🟦 "<>Get embed code" button, and in the <link> option, copy the code from "Embed code in the <head> of your html"

### Editing Assets
1. Rename the files on your local machine to CV.pdf for your CV and profile.jpg for your About photo
2. You can drag-and-drop files in **Explorer**, or in the main repository

## GitHub Glossary

>- **Git**- an open source program for tracking changes in text files (written by the author of the Linux operating system)
>- **repo**- repository for project storage
>- **branch**- a parallel version of a repository
>- **local**- this is your personal computer
>- **remote**- this is the version of a repository or branch that is hosted on a server, most likely GitHub.com
>- **clone**- a clone is a copy of a repository that lives on your computer
>- **fork**- a fork is a personal copy of another user's repository that lives on your account
>- **commit**- a saved change or revision
>- **commit message**- short, descriptive text that communicates the change the commit is introducing
>- **pull**- fetch changes from remote and merge them
>- **push**- send your committed changes to a remote repository on GitHub.com
>- **collaborator**- someone with read and write access

## GitHub Statistics

GitHub is a company that was acquired by Microsoft that hosts git (version control) projects online.
 
100 million + accounts
400 million + repositories
More than 90% of Fortune 100 companies now use GitHub in their development workflows.



