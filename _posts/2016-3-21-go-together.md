---
layout:     post
title:      "Going Together with OER"
subtitle:   "The Message, Not the Medium"
date:       2016-3-21 12:00:00
author:     "Billy Meinke"
header-img: "img/blueprints.jpg"
readtime: 5
comments: true
---

When discussing the idea of collaborative OER development with folks lately, a disappointing topic continues to surface: if it wasn't invented here, we won't be able to use it. On many levels, the open source software community has moved past this blocking concept, but they've been aided by a specific aspect of software that the OER community has yet to tackle. Software code is easy to quantify and judge objectively. If you wanted to, say, find out how many lines of code a specific software contributor made, the version control (git, subversion, or otherwise) system would be able to tell you. What changed about a piece of software from the last version? Yep, you can pull that up as a report instantly. Don't like the style in which some code was written? If it's free software, you can rewrite the code to work more efficiently, or do something in a way you prefer.



This isn't to say that there's no finesse involved with writing good code, because there is. If you've ever read through software coded that has been commented well, you'll see that developers are some of the more creative, witty folks you'll bump into. Instead, what I mean is that I appreciate the value of being (more) objective about individual contributions and entire codebases. I think we need something that can do this for instructional content, and I think it'll make people let go of the above-mentioned notion, and move towards the idea of "proudly borrowing content from there."

When developers work on codebase as distributed teams, they rely on transparency in their contributions to keep things going. It's typical for open source software projects to include a roadmap of features, modifications, and milestones and show who's working on what. A contributor makes a pull request and asks the team to check out code they're committing to the project, and folks can review it. Because code basically just comes down to simple text files that can be created and changed with any number of editors, there's less distraction. The code is judged in terms of it's value to other users, or to a community. Does it do what it's expected to do? You're not worrying about whether or not you have the latest version of Office to be able to open the file, and not turning your head or squinting trying to read a strange font face. The code is clear, and when you view it with your editor of choice, there's little to distract you.

### The OER We Actually Make

Now we can argue about the current swath of editors and file formats used for instructional content, but most of the OER I've seen in my career have been Word (.doc) files, or Word files exported to PDF. Microsoft has done well to put powerful word processors in front of millions of people, but the truth is that most of us use very few of the features MS has baked into every new version. Most of what you pay for has been integration with a newer operating system (think Windows 8, 10, OSX, etc), and less of it having to do with you being able to manipulate text more efficiently. Of the few features you've found to streamline your process of content creation, you'd also probably have a hard time finding anyone else who uses those features, too. When I write instructional content, I rely on only the most basic text styling:

 - bolds
 - italics
 - lists (ordered, unordered)
 - heading levels
 - links

With few exceptions, anything beyond this list is left up to the graphic designer on my course development team. The designers handle the styling of courses we build in Wordpress, contructing the CSS and Javascript to help my content take shape in the delivery format. If the designer changes the styling for the entire course by changing the CSS, my content plays nicely and does the dance because I haven't forced any styling on it. Internally, this means that my course pages can be moved between Wordpress themes without too much of a struggle. But because not everyone that would potentially reuse my OER develops content using Wordpress, a WP database file would only be sort of useful, at least as an off-the-shelf option.

There are efforts to make the export of full courses more simple, and consumable by another course management system. Standards like IMS Common Cartridge and LTI allow rich, interactive content to do this, but I would wager than much of the "rich" features are what potential reusers would changes most, or simply leave out of their own iteration of the course. When it comes down to it, the written text content is the OER we want, and it's what it should be easier to collaborate on.

### So, I'm announcing a request for something like Git for content.

The OER most people work with are text files, anyway, with formatting that isn't going to work for other users. Google Docs are closer to the ideal than anything I've seen, and offer detailed revision histories for documents. But we don't publish our courses in Google docs, so that's really only for drafting content before finishing and publishing to the Web with Wordpress. If instructional content were developed by distributed teams like software code is, and the content's value objectively looked at in a way that's not attached to any flashy styling, I guarantee that more individuals and organizations would collaborate on OER together.

Let's be sure to keep in mind that the subject-matter experts creating the content, and the instructional designers massaging it into lessons and modules are not developers. Git doesn't make sense to most. The command line is that scary thing they opened on accident a while back. But I think they're ready to check their fancy fonts and distracting formatting at the door, and create content that's been designed for reuse. And maybe, just maybe, be willing to take a deep look at someone else's style-agnostic content.

I'm realizing that these ideas may not be fully gelled in my own head, but it's better to get it down on paper than let it be lost while I wait for it to happen. We're going to crack this nut, and make collaborative OER development happen soon. I can feel it.


##### Header image [Blueprints for Willborough Home](https://www.flickr.com/photos/btobin/4456582998/0) by Brian Tobin / [CC BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/2.0/)