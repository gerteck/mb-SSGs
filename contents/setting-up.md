<frontmatter>
  title: Setting up your site
</frontmatter>

<br>

As you set up your site, you need to make some decisions that will help determine which SSG to use.

### Setting Up the Project

With no server or database to configure, a JAMstack project is largely a simple folder structure full of text files. The contents of your JAMstack project will usually include the following:

* A source folder to store your content files
* A folder for layouts and templates
* A configuration file containing the settings for the build process
* A static site generator, usually added as a dependency
* A destination folder to save the final output

You can manage your entire project locally, directly on your computer, but it’s always best to begin by setting up a hosted Git repository. 

Rarely would you set up your entire project folder from scratch because most site generators have sample projects that you can download from GitHub as a starting point. But before we talk about site generators, let’s cover the various ways to manage content on the JAMstack.

### Managing Content on your Site

Every website begins with content. On Content Management System (CMS) systems like Drupal or WordPress, sites manage content in a database, and editors use an admin interface to write and save the content to the database.

On the JAMstack, there are actually a few content approaches.

#### Text Files

For many JAMstack sites, content couldn’t be more straightforward: it’s simply a folder full of files that lives directly within the project with the templates, plug-ins, and other assets. Creating a new file in the content directory will create a new page after the site is published, and changes are made by editing the content files in a text editor and then committing the changes to the Git repository. The name of each file and the folder it is in will determine its URL path after the site is generated.

#### What Does One of These Content Files Look Like?

It can be straight HTML—though usually pared down to only the unique parts of the page. Common elements like headers and footers are added by the site generator during the build step.

Authoring site content in pure HTML can still be tedious, however. This is why Markdown, a much-simplified syntax, has become the most popular option for writing content.

### Metadata

Most common CMSs have additional settings for each page; for example, which layout to use or which category and tags the page should be assigned. To store details such as these, static site generators have standardized on a top section of each file called the metadata. Often written in YAML, it’s a simple key/value collection of settings and other data that apply to the page.
