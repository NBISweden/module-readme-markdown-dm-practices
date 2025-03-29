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

## Part 1: Understanding README files

### What is a README file?

A README file is a text file that introduces and explains a project. It provides the basic information needed to understand the project and how to use it.

*Why is the README important?* A README helps team members and collaborators quickly understand the project, reducing the learning curve and improving efficiency. For software or datasets, a README provides necessary instructions on how to install, configure, and use the resources, making it easier for others to utilize your work.

### What different kinds of README files are there?

First out is the **project README** which provides a general overview of the project. The project README should be put in the root folder of the project and it typically includes:

* **Purpose:** A brief description of what the project is about.
* **Installation instructions:** Step-by-step guidance on how to set up the project.
* **Usage:** Information on how to use the project, including examples if applicable.
* [Study level README example](https://rdmkit.elixir-europe.org/metadata_management#:~:text=Study/project%20level%20README) from [RDMkit](https://rdmkit.elixir-europe.org/about).

A **data README** is specific to datasets and includes detailed information about the data. This README should be put in the subfolders holding different types of data and it usually covers:

* **Data collection methods:** How the data was collected.
* **Structure:** The organization and format of the data.
* **Preprocessing steps:** Any steps taken to preprocess the data before analysis.
* [Data level README example](https://rdmkit.elixir-europe.org/metadata_management#:~:text=this%20study/project%3E-,Data%20level%20README,-This%20README%20file) from [RDMkit](https://rdmkit.elixir-europe.org/about).

A **code README** focuses on software or scripts. It provides information on how to run the code and includes:
 
* **Purpose:** The main function or goal of the code.
* **Dependencies:** Any software or libraries required to run the code.
* **Examples:** Sample commands or scripts to demonstrate usage.
* [Code level README example](https://www.makeareadme.com/#suggestions-for-a-good-readme:~:text=Suggestions%20for%20a%20good%20README) from [makeareadme.com](https://www.makeareadme.com/).

## Part 2: Introduction to Markdown

### What is Markdown?

Markdown is a lightweight markup language with plain-text formatting syntax. It is used to create formatted text using a plain-text editor. Using Markdown is different from using an editor like Microsoft Word. In Word, you click buttons to format text and see the changes instantly. With Markdown, you add special syntax to your text to indicate formatting, but you won't see the changes until you preview or render the file.

*What are the benefits of Markdown?* Markdown is a versatile tool used for creating e.g. documents, emails, websites, and presentations. It is portable, allowing Markdown-formatted text to be opened with virtually any application, unlike proprietary formats like Microsoft Word. Markdown is platform-independent, enabling text creation on any device or operating system. Additionally, it is future-proof, ensuring readability with any text editor even if the original application becomes obsolete. Read more on [www.markdownguide.org](https://www.markdownguide.org/).

### How do you write Markdown?

There are many online tools and editors available that let you live code your Markdown, meaning you can see the formatted output as you type. If you want to try out live coding your Markdown, here is an example: 

* [markdownlivepreview.com](https://markdownlivepreview.com/)

If you have [Visual Studio Code (VS Code)](https://code.visualstudio.com/) installed on your computer, you can open it and create a new text file. Select Markdown as the language and start typing. VS Code can also auto-detect the language, and it allows you to preview and render the output.

For an overview of the basic Markdown syntax, please go to the [Markdown elements outlined in the original design document](https://www.markdownguide.org/basic-syntax/). 





{% include links.md %}
