# Pinta Website

This repository contains the layout and content of the Pinta website (<http://pinta-project.com>).

#### Structure

There are 2 directories that are used to serve the website:

- **Content** - Contains content that is served
- **Theme** - Contains the skin (template, css, images, etc.) that presents the content

#### Technical Details

Content is preferred to be written in [CommonMark][1] (a Markdown derivitive), but can also
be written in HTML if advanced features are needed.

New URLs are created simply by adding a new .md or .html file to the Content directory.

For example, to create **pinta-project.com/new-page**, add a file called
***new-page.md*** or ***new-page.html*** to the Content directory.  

You can also create hierarchy by adding directories to the Content directory.  

For example, adding **Content/AwesomePages/new-page.md** will create **pinta-project.com/awesomepages/new-page**.

##### Content Order of Precedence

Given a URL like **pinta-project.com/releases**, content will be searched for in the following order:

- Content/releases.md
- Content/releases.html
- Content/Releases/index.md
- Content/Releases/index.html
- 404 (Not Found) returned

#### Contributing

If you would like to propose changes to the Pinta website, simply send a GitHub
pull request on this repository for Pinta admins to process!

Once accepted, the web server updates its cache from GitHub every 30 minutes, so there
will be a slight delay before changes go live.

[1]: http://commonmark.org/
