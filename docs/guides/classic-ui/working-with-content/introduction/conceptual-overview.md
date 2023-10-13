---
myst:
  html_meta:
    "description": "Conceptual overview"
    "property=og:description": "Conceptual overview"
    "property=og:title": "Conceptual overview"
    "keywords": "Plone 6, Classic UI, overview"
---

# Conceptual overview

This section of the documentation explains Plone as a content management system.

## What is Plone?

Plone is a content management system (CMS) which you can use to build a website.
With Plone, non-experts can contribute to and manage content on a website without the help of a technical specialist.

There is no need to install special software on your computer or mobile device to do this.

We use the general word *content* to cover the many types of information you can publish, including:

- text (web pages)
- photos and images
- documents
- news and events
- videos
- audio files

A Plone website can contain these kinds of content and more.

You create *folders* on a Plone website to hold content, and those folders automatically define the website's navigation structure.

You can nest folders in a Plone website just as you would on a computer. By creating folders within folders, you can organize your website's content as finely as you need.

- Folder 1
- Folder 2
  - Folder 3
    - Folder 4
- Folder 5

## You love butterflies

For example, to add content about butterflies, you might add a folder named "Butterflies," then add some text to a web page in the folder:

```{figure} butterflies_folder_text.png
:align: center
:alt: true
```

And then you might add some butterfly photos to the folder:

```{figure} butterflies_folder.png
:align: center
:alt: true
```

You can add many types of content to a folder, including sub-folders.
After adding a few reports and videos to the Butterflies folder, the content would be organized like this, with two sub-folders within the Butterflies folder:

```{figure} folders_within_folders.png
:align: center
:alt: true
```

## What goes on behind the scenes

A typical Plone website exists as an installation of Plone software on a web server.
The web server may be anywhere on the internet, such as on a virtual machine from a cloud provider.

Your Plone site is a combination of software and storage running on one or more servers.

This simplified diagram shows your interaction with Plone:

```{figure} client_to_server_simple.png
:align: center
:alt: true
```

You use your web browser to view and edit your Plone website, and the changes are stored by the Plone software into its storage.

For example, imagine your butterfly Plone website is located at mysite.com.
You type `mysite.com` into your web browser.
After you press Enter, the following sequence of events happens as your browser talks to the web server at mysite.com:

```{figure} client_request.png
:align: center
:alt: true
```

The Plone software responds:

```{figure} server_response.png
:align: center
:alt: true
```

Plone reads its storage to look for information stored in mysite.com.
It then sends back the web page to your computer, in formats called HTML and CSS.
Together, HTML and CSS are computer languages that describe what a web page contains and how it looks.
This includes text, graphics, fonts, the color of the background, and the layout of the page.
There are many online resources that can teach you HTML and CSS, but one of Plone's advantages is that you don't need to know either.
That's one of main reasons for using Plone: to let you focus on your content (butterfly text and graphics, in this case) instead of having to understand the technical underpinnings.

But back to our overview.
Your web browser "renders" (translates) this HTML and CSS, and you see the resulting web page:

```{figure} my_site_served.png
:align: center
:alt: true
```

As you view your butterfly web page, you can choose to change it or add to it.
You can also upload photos, documents, and other types of content:

```{figure} plone_donut.png
:align: center
:alt: true
```

After you make your edits and save your changes, the new version of the web page will be immediately available to anyone viewing your site:

```{figure} plone_donut_full.png
:align: center
:alt: true
```
