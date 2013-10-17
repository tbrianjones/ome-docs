Online Markdown Editor (OME)
============================
The Online Markdown Editor is an easy way to publish software documentation right from your GitHub repository.

It was created by @tbrianjones for an internal project.  Contributions by @leleu and @ccdpowell.


Live Hackathon 10/17-10/19
==========================

[Chat with us during the hackathon](http://tlk.io/ii_hackathon)
---

We (@leleu, @tbrianjones, @ccdpowell) are doing a hobby hackathon to develop this internal project so it can be released publicly.  [please visit out our chat room](http://tlk.io/ii_hackathon) to let us know your thoughts.

We want to make it easy to create Great Documentation.  Our philosophy is as follows:

* Zero installation.  No packages, modules, web servers.
* Zero configuration.  Simply write your documentation in markdown and point the OME to it.
* Attractive results.  Sections are parsed and linked automatically, making it easy to consume.



Feature Ideas
===============

We want it to do more than just viewing documentation, so we're doing a hackathon.  Please let us know your feedback -- what would be most useful?

Some ideas:

* Public collaboration - documentation userscan update and fix your documentation by submitting pull requests through the OME interface (forking handled automatically).
* Documentation / Code maintenance - monitors your repository, when you update code but not the corresponding documentation, the OME automatically notifies you.
* Reporting - make your documentation your status reports automatically sent to your team.



Creating Great Documentation with OME
=====================================

To use the OME, (visit http://www.onlinemarkdowneditor.com) and input the URL of your markdown documentation file.  Note - it should be the Github URL of the .md file, not the URL of the repo.  E.g., enter "https://github.com/tbrianjones/ome-docs/blob/master/DOCUMENTATION.md" in the input box and submit to view this documentation file.

Your documentation file must be in markdown.  The OME parses h1 tags (denoted in markdown by a line of === beneath the tag) to create the index.  h2-h6 tags are parsed and included as submenu items in the left hand navigation.


FAQ
===
### What is the OME?
The Online Markdown Editor ( currently only supports reading the documentation -- editing is one of our features under consideration ) renders any Markdown File on Github as a live website.

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
Yes. Learn more in the Security section below.

Security
========
Security on Github is maintained with the OME.
- Public Files can be viewed by anyone and without logging into a github account.
- Viewing Private Files require users to Login with their Github account.  Their account must have access to Pull the File they are trying to view.
