**Click-Docbook** provides a modified [Velocity Docbook Framework](http://velocity.apache.org/docbook/) as well as a set of starting templates, generating tasks and best practices, _(initially developed to generate the [Apache Click](http://click.apache.org) documentation)_ allowing the quick and trouble-free start of producing [Docbook](http://en.wikipedia.org/wiki/DocBook) based documentation for any project.

## How to use it ##
Just run the generator to the desired destination directory, and everything will be automatically set up and ready to produce your documentation. For details see the (TBD..) .

## Changes made to Velocity Docbook Framework ##
Since this project is based on Velocity Docbook Framework, the following changes were made to it:
  * Upgraded to Apache FOP v0.95 (this version supports soft page breaks)
  * Upgraded to Docbook XLS v1.75.0 (this version supports syntax highlighting)
  * Includes XSLTHL syntax highlighter version 2.0.1

## Who is using Click-Docbook ##
The following projects are using this framework:
  * [Click Framework](http://click.apache.org)
  * jMailForm
  * ???


---

**Note:** the framework itself is not to be downloaded, but by using the ANT tasks from here, your project will download the required files automatically.