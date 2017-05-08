# Introduction to Computer Science - Fall 2017
## Lab 1 - You need to Git

**Purpose:** This purpose of this lab is to get some practice with basic _HTML_ and the basics of the _Git Version Control System (VCS)_. The assignment has two parts. The HTML part and the git part.

**Assumptions:** This assignment assumes that you have already set up a Cloud9 account using the class link and linked it to your GitHub account.

**Part 1 - Cloning the Repository:** Clone this repository into a new workspace in your [Cloud9](https://c9.io/) account. Once you are in your workspace, continue on to the next part.

**Part 2 - Instructions:** Create a basic HTML file called `index.html`. It should be an informative page about an animal of your choice (real or fictional). The HTML file must include the most important structural elements, including:

* Doctype declaration
* &lt;html&gt; angle tags
* &lt;head&gt; tags with typical title and meta-data tags
* &lt;body&gt; tags with content using appropriate markup.

Look at the [HTML Demos](itech190.erickuha.com) and their source code (Ctrl-U) for ideas of how this should look.

Other tags that the page should demonstrate:
* &lt;h1&gt; at least one heading tag
* &lt;ol&gt; or &lt;ul&gt;, ordered or unordered list
* &lt;p&gt; paragraph tags where appropriate
* &lt;img&gt; tag and an image (the actual image file can be a link to another page, or a local file in the same folder)

Once you are finished, if you are in your Cloud9 workspace, you can push your changes to the repository by entering the following commands into the terminal at the bottom of the workspace:

`````
    $ git add --all
    $ git commit -m "Some commit message."
    $ git push -u origin master
`````

If you have trouble with these commands, ask the instructor or refer to the provided course resources.
