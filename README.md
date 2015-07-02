# application-like

[![XWiki labs logo](https://raw.githubusercontent.com/xwiki-labs/xwiki-labs-logo/master/projects/xwikilabs/xlabs-project.png "XWiki labs")](https://labs.xwiki.com/xwiki/bin/view/Main/WebHome)

Display a like button in a wiki page to make a rating on usefulness of the page for the current user.

## Building and installing from source

In order to build you'll need [maven](http://maven.apache.org). Make sure you have a suitable `settings.xml` in your `.m2` directory as described [here](http://dev.xwiki.org/xwiki/bin/view/Community/Building).

* run `mvn install`
* Import the generated XAR under `application-like/target/` to an XWiki instance.

## Integrate the like button in wiki pages

In order to integrate the like button in a wiki page you just need to insert `{{likeButton/}}` macro in the page content.
