Online Markdown Editor (OME)
============================

The [Online Markdown Editor](http://www.onlinemarkdowneditor.com) is an easy way to publish software documentation right from your GitHub repository.  Any Markdown file on Github can be published right to the Online Markdown Editor. It was created by @tbrianjones for an internal company project.  Contributions by @leleu and @ccdpowell.

Example Docs
------------
*Markdown files rendered on the OME*

- [Our Company's API Docs](http://www.onlinemarkdowneditor.com/docs/tbrianjones/cortex-api-docs/DOCUMENTATION.md)
	- This project developed from wanting an easy way to maintain and display these.
	- They exist as a [single markdown file](https://github.com/tbrianjones/cortex-api-docs/blob/master/DOCUMENTATION.md) on Github

*add some more examples*


Live Hackathon 10/17-10/19
==========================

We (@leleu, @tbrianjones, @ccdpowell) are doing a hobby hackathon to develop this internal project so it can be released publicly.  [please visit out our chat room](http://tlk.io/ii_hackathon) to let us know your thoughts.

We want to make it easy to create Great Documentation.  Our philosophy is as follows:

* Zero installation.  No packages, modules, web servers.
* Zero configuration.  Simply write your documentation in markdown and point the OME to it.
* Attractive results.  Sections are parsed and linked automatically, making it easy to consume.

Chat with Us Live
-----------------
- [Chat with us during the hackathon](http://tlk.io/ii_hackathon)
- Please visit the [Live Hackathon Chat](http://tlk.io/ii_hackathon) to discuss, collaborate, or offer feedback.


Feature Ideas
===============

We want it to do more than just viewing documentation, so we're doing a hackathon.  Please let us know your feedback -- what would be most useful?

Some ideas:

* Public collaboration - documentation userscan update and fix your documentation by submitting pull requests through the OME interface (forking handled automatically).
* Documentation / Code maintenance - monitors your repository, when you update code but not the corresponding documentation, the OME automatically notifies you.
* Reporting - make your documentation your status reports automatically sent to your team.


FAQ
===
### What is the OME?
The Online Markdown Editor ( currently only supports reading the documentation -- editing is one of our features under consideration ) renders any Markdown File on Github as a live website.

### How do I use the OME?

Visit [The OME's Website](http://www.onlinemarkdowneditor.com) and input the URL of your markdown documentation file.  Note - it should be the Github URL of the .md file, not the URL of the repo.  E.g., enter "https://github.com/tbrianjones/ome-docs/blob/master/DOCUMENTATION.md" in the input box and submit to view this documentation file.

Your documentation file must be in markdown.  The OME parses h1 tags (denoted in markdown by a line of === beneath the tag) to create the index.  h2 and h3 tags are also parsed and included as submenu items in the left hand navigation.

### How does the OME work?
The OME renders markdown in a manner that is best suited for Documentation ( originally built for API Documentation ). While rendering, `h1`, `h2`, and `h3` headers are pulled and rendered as a mobile friendly index to the left of the original rendered markdown.

### How do I view the original documents on Github?
To view the originals on Github, please use the links at the top right.

### How do I view a different documentation file or repository?
If you'd like to load a different Markdown File from Github, visit the [Online Markdown Editor homepage](http://www.onlinemarkdowneditor.com).

### Why was it built?
The OME grew from an internal project where we were rendering our company's API Documentation from a Markdown File.  We realized how simple this was to maintain, and saw it allow us to effortlessly maintain Great Documentation.

We found that we simply didn't update our Docs frequently enough when trying to maintain documentation outside our project, in multiple linked files within Github, or any number of proprietary SaaS apps.

WIth the OME, you can maintain even very large documentation files ( our API Docs are over 50 pages now ) within the project rep, using your favorite text editor.

This is the easiest way we can imagine maintaining Great Documentation.

### Are private files secure?
- Security on Github is maintained with the OME.
- Public Files can be viewed by anyone, and without logging into a Github account.
- Viewing Private Files require users to Login with their Github account.  Their account must have access to Pull the File they are trying to view.


Public Projects Used
====================

We are planning to open-source the Online Markdown Editor project as part of our Hackathon.  We need to do a security audit before hand, however, to ensure we aren't sharing any private information.  In the mean time, you can view the public and open-source projects that we are currently using as part of the Online Markdown Editor.

- [GitHub API Client](https://github.com/KnpLabs/php-github-api)
- Markdown Parsers:
	- [PHP Markdown Extra Extended](https://github.com/egil/php-markdown-extra-extended)
		- This is the markdown parser currently implemented in the Online Markdown Editor.
	- [Sublime Markdown Extended](https://github.com/jonschlinkert/sublime-markdown-extended)
		- Another markdown parser we've tried.
- Markdown Index Generator
	- We've developed this as part of the project, and will open source it tomorrow.
- [Javascript Index Generator](http://mmenu.frebsite.nl/)
- Web Framework: [Codeigniter](http://ellislab.com/codeigniter)
- Database: [MySQL](http://www.mysql.com/)
