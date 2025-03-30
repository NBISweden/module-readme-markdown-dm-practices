---
title: "Introduction to README files and Markdown in Life Science Research"
teaching: 15
exercises: 45
questions:
- "What different kinds of READMEs are there?"
- "What should you write in a README, based on the different kinds of READMEs?"
- "What are the benefits of Markdown?"
- "How do you write Markdown?"

objectives:
- "Understand the purpose and importance of README files in research projects."
- "Learn the main sections to include in various types of READMEs."
- "Apply Markdown syntax to create and format README files."
---

## Part 1: Understanding README files in Life Science Research

### What is a README file?

A README file is usually a text file and serves as an introduction and guide to a project. The README makes it easier for others (and your future self) to understand the project's purpose and structure. Depending on its scope, a README might provide a project overview, explain the folder organization, or offer usage examples. It can also include details such as contribution guidelines and licensing information. Whether you're a researcher, PhD student, developer, or simply revisiting your own work, a good README simplifies navigating and using the project's contents.

*Why is the README important?* A README helps team members and collaborators quickly understand the project, reducing the learning curve and improving efficiency. For software or datasets, a README provides necessary instructions on how to install, configure, and use the resources, making it easier for others to access your work.

### What different kinds of README files are there?

First out is the **project README** which provides a general overview and how the data within the project is structured. This README should be put in the root folder of the project and it typically includes:

* **General information:** A project title, scope and purpose, project members' names, roles and contact info. It is also good practice to include a link to the Data management plan.
* **Organisation:** Folder structure, file naming conventions, and file formats included in the project.
* **Usage:** Information on how to use the project, including examples if applicable.
* [Study level README example](https://rdmkit.elixir-europe.org/metadata_management#:~:text=Study/project%20level%20README) from [RDMkit](https://rdmkit.elixir-europe.org/about).

A **data README** is specific to datasets and includes information about the data. This README should be put in the subfolders of the data it describes and it usually covers:

* **General information:** Dataset title and description (including e.g. delivery reports from the facility that generated the data).
* **Organization:** Folder structure, file naming conventions, file formats.
* **Data reuse:** Accession number (if the dataset is published), license, and use restrictions (if any).
* [Data level README example](https://rdmkit.elixir-europe.org/metadata_management#:~:text=this%20study/project%3E-,Data%20level%20README,-This%20README%20file) from [RDMkit](https://rdmkit.elixir-europe.org/about).

A **code README** focuses on software or scripts. It provides information on how to run the code and includes:
 
* **Purpose:** The main function or goal of the code.
* **Dependencies:** Any software or libraries required to run the code.
* **Examples:** Sample commands or scripts to demonstrate usage.
* [Code level README example](https://www.makeareadme.com/#suggestions-for-a-good-readme:~:text=Suggestions%20for%20a%20good%20README) from [makeareadme.com](https://www.makeareadme.com/).

## Part 2: Introduction to Markdown

### What is Markdown?

Markdown is a lightweight markup language with plain-text formatting syntax. It allows you to create formatted text using a plain-text editor. Markdown is different from an editor like Microsoft Word. In Word, you click buttons to format text and see the changes instantly (what you see is what you get). With Markdown, you add special syntax to your text to indicate formatting, but you won't see the changes until you preview or render the file.

### What are the benefits of Markdown?

1. Markdown is a **versatile language** used for creating e.g. documents, emails, websites, and presentations.
2. It is **portable**, allowing Markdown-formatted text to be opened with virtually any application, unlike proprietary formats like Microsoft Word.
3. Markdown is **platform-independent**, enabling text creation on any device or operating system.
4. It is **future-proof**, ensuring readability with any text editor even if the original application becomes obsolete.

Read more at [www.markdownguide.org](https://www.markdownguide.org/getting-started/).

### How do you write Markdown?

There are many online tools and editors available that let you live code your Markdown directly in the web browser, meaning you can see the formatted output as you type. If you want to try out live coding your Markdown, here are some examples: 

* [markdownlivepreview.com](https://markdownlivepreview.com/) - a simple, web-based Markdown editor that provides a live preview of your Markdown text as you type.
* [dillinger.io](https://dillinger.io/) - is an online Markdown editor that also offers a live preview. Dillinger supports importing and exporting files from various sources like GitHub, Dropbox, and Google Drive, making it useful for more integrated workflows
* [stackedit.io](https://stackedit.io/app#) - is a more advanced, web-based Markdown editor that supports offline editing, synchronization with cloud services (Google Drive, Dropbox, GitHub). It also offers collaboration features, allowing multiple users to work on the same document simultaneously.
  
If you have [Visual Studio Code (VS Code)](https://code.visualstudio.com/) installed on your computer, you can open it and create a new text file. Select Markdown as the language and start typing. VS Code can also auto-detect the language, and it allows you to preview and render the output locally on your computer.

For an overview of the basic Markdown syntax, please go to markdownguide.org and its representation of the **[Markdown elements outlined in the original design document](https://www.markdownguide.org/basic-syntax/)**. 

## Part 3: Exercises

**Welcome to the exercises section!** These exercises are designed to help you practice creating and formatting README files using Markdown. If you want to begin with an interactive Markdown tutorial, you can visit [Commonmark's tutorial](https://commonmark.org/help/tutorial/). Otherwise, you can go directly to the exercises and come back for the tutorial at a later stage. 

If this is the first time you write in Markdown, [markdownlivepreview.com](https://markdownlivepreview.com/) could be a good choice to get started but you are free to use any other tool as well. For additional help and examples, make use of the [Cheat Sheet](https://www.markdownguide.org/cheat-sheet/) from markdownguide.com.

### Exercise 1: Basic Structure
**Task**: Create a basic README file for a hypothetical project. Include sections for the project title and description.
<details>
  <summary>Hint</summary>
 
  Use headings for each section and try different levels. Do not forget a space after the #, and the blank lines before and after the headings.
</details>

### Exercise 2: Detailed Project Information
**Task**: Expand the README file from Exercise 1 to include information about the project members, their roles, and contact information. Also, add a section for the project's data management plan.
<details>
  <summary>Hint</summary>
 
  Include a table with the project members, their roles, and contact information. Add a link to the data management plan.
</details>

### Exercise 3: Folder Structure and File Naming
**Task**: Add a section to your README file that describes the folder structure and file naming conventions used in your project. Use Markdown to create a visual representation of the folder hierarchy.
<details>
  <summary>Hint</summary>
 
  Use bullet points or `code syntax` to represent the folder structure and file naming conventions.
</details>

### Exercise 4: Explore published READMEs on GitHub
**Task**: Go to the GitHub repository [**awesome-readme**](https://github.com/matiassingers/awesome-readme) and find an example README of your interest. Write down some features that you find useful and try to add them to your README from exercise 3, or create a new README.
<details>
  <summary>Hint</summary>
 
  Experiment with different Markdown elements to see how they affect the formatting. If you need examples you can take a look at the [basic syntax](https://www.markdownguide.org/basic-syntax/) or the [extended syntax](https://www.markdownguide.org/extended-syntax/) from the [markdownguide.com](https://www.markdownguide.org/).
</details>
 
{% include links.md %}
