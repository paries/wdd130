<!DOCTYPE html> what version of HTML 
This is a development checklist item. The development checklist is a list of required components that must be included in every assignment that you submit in this course.

<html lang="en">
This element wraps all the content on the entire page, meaning that everything else should be inside it. It is sometimes known as the root element, because it is like the root of a tree that everything grows from. It has a lang attribute to specify the primary language of the page.

✔ This element, including the language, is also a development checklist item.

<head>
The head element contains information about the page. The content from this section is not displayed on the page itself, but instead, it is made to be read by the computer to provide information information (metadata) about the document, such as the character set, viewport size, title, scripts, and style sheets.

✔ This is a development checklist item.

    <meta charset="UTF-8">
    Located within the <head> element, the meta charset attribute defines the character encoding for the document, which means the way that the text is represented in the underlying binary data that the computer stores. In the past, various character encodings may be used for different languages, such as those that have accent marks or Chinese characters. HTML 5 (the current standard) requires "utf-8" for all HTML documents.

    ✔ This is a development checklist item.

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    Located within the <head> element, the meta viewpoint attribute makes sure the page renders at correct width to prevent mobile browsers from rendering the page wider than they should and then shrinking them down.

    ✔ This is a development checklist item.

    <title>My First Page</title>
    Located within the <head> element, the title element defines the title of your page, which will be displayed in the browser tab or when you bookmark a page.

    This title does not show up directly on the page itself, but it should closely match the content you include in the heading 1 <h1> element in the document <body>.

    ✔ A title element with a meaningful title is a development checklist item.


 The <body> element contains the main content of the HTML document. There can be only one body element in a document. It contains all the content that you want to show to web users when they visit your page, including text, images, videos, and anything else you want the user to see.

✔ This is a development checklist item.

------------------------------------------------------------------------------------------------------------------------------------------
In this course, all images must be optimized in order to reduce overall page weight (the download size of the page). 
The standard is that all images need to be less than 125kB in memory size. 
If you have an image that is larger than 125kB, you will need to reduce its size by optimizing it.

------------------------------------------------------------------------------------------------------------------------------------------

Naming Convention Rules
Use all lowercase syntax.
Some platforms and systems handle case sensitivity differently. Case sensitivity is an important concept to understand when managing files and folders.

❌ Invalid example: Products.html
✅ Valid example: products.html
Do NOT use spaces in file and folder names. Instead, use hyphens -.
Spaces may be handled inconsistently by browsers or other tools so do not use them. The Hypertext Transfer Protocol (HTTP) ignores spaces, except in file names. In file names, it replaces a space with this syntax: "%20" which syntax is confusing. Avoid using spaces and instead, if you want to create visual space, use hyphens.

❌ Invalid example: design documents.html
✅ Valid example: design-document.html
Do NOT use special characters. Special characters often mean specific things to computers, so do not use them in the naming of files and folders.

Special character examples (avoid these): <,>, \, /, #, ?, !, _
File and folder names should be as short and meaningful (semantic) as possible.
Short names save you, other developers, and site visitors from having to remember long complicated names for files and folders. When meaningful, names can also help predict the purpose or nature of the file or folder contents.

❌ Invalid example: image13-v123523brokenbranchlifeimagery w200x200.png
✅ Valid example: winter-scene-small.png
Use standard names for folders. In this class, the standard folder names for sub-folders are:
styles – Folders with this name contain CSS files.
images – Folders with this name contain images.

------------------------------------------------------------------------------------------------------------------------------------------
