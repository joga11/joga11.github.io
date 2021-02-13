---
layout: default
title: Introduction
nav_order: 1
description: "My Docs"
permalink: /
---

![image](/assets/images/bitmatrix-code.jpg)

# Introduction

Author: Joanna Gajewska (joga11)  

**Instructions for students who were not in attendance**

# Why do I need Visual Studio Code and Markdown?

**Visual Studio Code** and **Markdown** are the tools for easy and quick creating and publishing documentation.

Various popular formats, such as PDF, HTML, WORD, are used for this purpose, but they have some limitations.

PDF - [see for more details](./pdf.md)  
HTML - [see for more details](./html.md)  
WORD - [see for more details](./word)  

Most of the limitations are not present in **Markdown**. The tool allows you to write using an easy-to-read, easy-to-write plain text format, then convert it, for example, to structurally valid XHTML or HTML.  
* The standard for quick documentation in IT and related fields  
* The format is simple and readable without editing  
* Documentation can be expanded to any size  
* It is easy to manage a large number of documents and reuse of content  
* A free tool with preview  
* Visual issues are separated from the content
* Other input and output formats can be generated from .md file
* The file can be modified or content can be extracted from it
* A simple tool for simple things, but more difficult for complex things (e.g. tables, formulas)
* It is a text format, so when moving between environments, you have to remember about the end of line character and character encoding

**Visual Studio Code** is a source code editor which is available for Windows, macOS and Linux.
* VSC supports and facilitates documentation writing
* It shows the output preview while typing
* It works with Git tool
* VSC is free and widely used

For more information, see:  
[Visual Studio Code](./vsc.md)  
[Markdown](./markdown.md)

# How to use GitHub?
1. Create a GitHub account at https://github.com/join
2. Install GitHub Desktop from the site https://desktop.github.com/
3. Verify and confirm your GitHub account and GitHub Desktop Client.
4. Create a local git repository.
5. Add a new file to the repo.
6. Make changes to your repo (for example, adding a file or modifying one).
7. Create a commit.
8. Push the repo to GitHub.
9. Invite collaborators: Setings > Your repo > Settings > Manage access > Invite a collaborator

For more information, see:  
[GitHub account](./github_account.md)  
[GitHub Desktop Client](./github_desktop_client.md/)  
[Authentication of GitHub account and GitHub Desktop Client](./authentication_github_account.md)  
[Creating a repository](./creating_repository.md)  
[Commit](./commit.md)  
Or visit [GitHub Desktop Documentation](https://docs.github.com/en/desktop)

# How to create diagrams in app.diagrams.net?

For easy creation of diagrams, graphics, etc. you can use app.diagrams.net (formely draw.io), a very useful tool.

1. Go to https://app.diagrams.net/
2. Select the location where the diagrams should be saved: Google Drive, Device, GitHab, etc.
3. Next, select **Create New Diagram**.
4. In the next window, type the filename in **.svg** format, select the template you need and click **Create**.
5. Now select where the diagrams should be saved in the target location. Click **Create** and the working window is displayed.
6. Create diagrams or graphics, using various features of app.diagrams.net tool.
7. Save the file and open it by **Visual Studio Code**.
8. In **VSC** window, press **Ctrl+Shift+P** and select **Toogle Word Wrap** and **Format Document**. The code becomes more readable.

**VSC** shows the code created while drawing the graphics. 
The code can be changed using **VSC**. You may need to install **SVG** extension to preview **.svg** files.  

[See the diagram graphics](little_diagram.svg)

Using app.diagrams.net, you can also work with screenshots.  
[See for details](diagram_with_screenshot.md)

Using app.diagrams.net, you can also create diagrams with SVG hyperlinks.  
[See for details](diagrams_SVG_hyperlinks.md)