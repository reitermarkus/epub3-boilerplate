EPUB 3 Boilerplate
==================
An EPUB 3.0 template to help you get started with your ebook. (Includes iBooks display options.)  
http://git.io/epub3-boilerplate

---


# Structure of an EPUB file

    ▾ /
      ▾ META-INF/
        ▪ container.xml
      ▪ mimetype
      ▾ OPS/ (Open Publishing Structure)
        ▾ book/
          ▪ content.html
          ▪ cover.html
          ▪ title.html
          ▪ table-of-contents.html
          ▪ table-of-contents.ncx
        ▾ css/
          ▪ style.css
        ▾ fonts/
          ▪ fonts.css
          ▪ someawesomefont.woff
        ▾ images/
          ▪ cover.jpg
        ▪ package.opf


# How To Use

As the author of this template I myself have used it a lot already and everytime I find something new I need in a book, I add it to this template. So, what I suggest you do is you really start fresh, creating a new folder and adding only what you need, otherwise I find it tough to keep track of what you have changed, added or deleted. Have fun coding!


# Helpful Resources

- [Accessibility Guidelines](http://idpf.org/accessibility/guidelines/nav.php)
  - [Quality Assurance Checklist](http://idpf.org/accessibility/guidelines/content/qa/qa-checklist.php)
  - [XHTML Accessibility Guidlines](http://idpf.org/accessibility/guidelines/content/xhtml/nav.php)
    - [Sectioning your Book (Parts, Chapters, etc.)](http://idpf.org/accessibility/guidelines/content/xhtml/sections.php)
    - [Creating the Table of Contents Files](http://idpf.org/accessibility/guidelines/content/xhtml/toc.php)
- [Creating a Read-Aloud iBook with Text-Highlightning](http://futurejones.com/easyepub/tutorials/read-aloud-text-highlighting/)