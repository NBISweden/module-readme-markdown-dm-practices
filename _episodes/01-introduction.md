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

A README file introduces and explains a project, helping others (and your future self) understand it. Depending on its scope, it might give an overview of the project, explain the folder structure, or provide usage examples. It can also cover things like contribution guidelines and licensing. Whether you're a researcher, PhD student, a developer, or just revisiting your own work, a good README makes it easier to navigate and use the contents of the project.

*Why is the README important?* A README helps team members and collaborators quickly understand the project, reducing the learning curve and improving efficiency. For software or datasets, a README provides necessary instructions on how to install, configure, and use the resources, making it easier for others to utilize your work.

### What different kinds of README files are there?

First out is the **project README** which provides a general overview and how the data within the project is structured. This README should be put in the root folder of the project and it typically includes:

* **General information:** A project title, scope and purpose, project members names, roles and contact info. It is also good practice to include a link to the Data management plan.
* **Organisation:** Folder structure, file naming conventions and file formats included in the project.
* **Usage:** Information on how to use the project, including examples if applicable.
* [Study level README example](https://rdmkit.elixir-europe.org/metadata_management#:~:text=Study/project%20level%20README) from [RDMkit](https://rdmkit.elixir-europe.org/about).

A **data README** is specific to datasets and includes information about the data. This README should be put in the subfolders of the data it describes and it usually covers:

* **General information:** Dataset title and description (including e.g. delivery reports from the facility that generated the data).
* **Organization:** Folder structure, file naming conventions, file formats.
* **Data re-use:** Accession number (if the dataset is published), license, and use restrictions (if any).
* [Data level README example](https://rdmkit.elixir-europe.org/metadata_management#:~:text=this%20study/project%3E-,Data%20level%20README,-This%20README%20file) from [RDMkit](https://rdmkit.elixir-europe.org/about).

A **code README** focuses on software or scripts. It provides information on how to run the code and includes:
 
* **Purpose:** The main function or goal of the code.
* **Dependencies:** Any software or libraries required to run the code.
* **Examples:** Sample commands or scripts to demonstrate usage.
* [Code level README example](https://www.makeareadme.com/#suggestions-for-a-good-readme:~:text=Suggestions%20for%20a%20good%20README) from [makeareadme.com](https://www.makeareadme.com/).

## Part 2: Introduction to Markdown

### What is Markdown?

Markdown is a lightweight markup language with plain-text formatting syntax. It is used to create formatted text using a plain-text editor. Using Markdown is different from using an editor like Microsoft Word. In Word, you click buttons to format text and see the changes instantly (what you see is what you get). With Markdown, you add special syntax to your text to indicate formatting, but you won't see the changes until you preview or render the file.

*What are the benefits of Markdown?* Markdown is a versatile language used for creating e.g. documents, emails, websites, and presentations. It is portable, allowing Markdown-formatted text to be opened with virtually any application, unlike proprietary formats like Microsoft Word. Markdown is platform-independent, enabling text creation on any device or operating system. Additionally, it is future-proof, ensuring readability with any text editor even if the original application becomes obsolete. Read more on [www.markdownguide.org](https://www.markdownguide.org/).

### How do you write Markdown?

There are many online tools and editors available that let you live code your Markdown directly in the web browser, meaning you can see the formatted output as you type. If you want to try out live coding your Markdown, here is an example: 

* [markdownlivepreview.com](https://markdownlivepreview.com/)

If you have [Visual Studio Code (VS Code)](https://code.visualstudio.com/) installed on your computer, you can open it and create a new text file. Select Markdown as the language and start typing. VS Code can also auto-detect the language, and it allows you to preview and render the output.

For an overview of the basic Markdown syntax, please go to the **[Markdown elements outlined in the original design document](https://www.markdownguide.org/basic-syntax/)**. 

{% include links.md %}
