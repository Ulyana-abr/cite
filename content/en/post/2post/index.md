---
 title: Lightweight markup languages
 date: 2025-04-04
---
 A lightweight markup language is a markup language designed to have a minimal syntax and to be easier for humans to read than traditional markup languages. Some, like asciidoc and the language of this very wiki, have comparatively many features, while others, e.g., that of the Thunderbird email client, which interprets email messages following a convention, are more rudimentary.

  What is the use of a lightweight markup language
- As software document format 
   Many other development community, like python, already uses a lightweight markup language for software documents. Typical uses are

    - for developers to author help files
    - to use in comment in source code to be later extracted to form code reference document.

In former case, there should be a widget to display the markup. In latter case, the document should be able to be translated to HTML.

- A WYSIWYG editor widget's content format 
   A WYSIWYG editor can save its content in a lightweight markup language. In this case lightweight markup language is transparent to the users. This case is seen as GUI bbcode editor that is sometimes used on the web, but no implementation in tcl yet have been seen.
- Directly usable to the end users 
   This case is frequently seen on online forums, like BBcode, and in wiki, like in tclerswiki. End user is supposed to learn and compose using this wiki language.

  Which lightweight markup languages have tcl tools supporting them? 
So far, most TCL lightweight markup language tools either require users define their own markup language, like the library included in tkoutline, or uses a markup language defined by the tool author, like "put-text" used in tkcvs, which defined a few tags including "<h1>", "<cmp>" and so forth. There isn't a tool that uses a well-recognized lightweight markup language, like asciidoc or Textile .

A well-recognized lightweight markup language usually has many tools designed to process it, thus it is easier to compose a document in the language and re-use it, e.g. in both "Help" menu and in Unix man page. Thanks to a lack of such tools in tcl, at the moment, documents already written in a well-recognized markup language cannot be displayed in tcl widgets directly.

   What features are there in lightweight markup language tools? 
   - Can represent / recognize bold and italic. This is a basic feature of markup language, thus not mentioned in feature table. Every tool supports this.
   - Display in rich text format as in htext
   - Translate to HTML, as in tclerswiki
   - WYSIWYG editing, not seen in any tcl markup language tool
   - Support of Images (I), Links (L), Tables (T) and Headings (H)
   
   List of Languages 
   - asciidoc
   - Creole , an attempt to create a common wiki markup
   - htext
   - kiwi
   - Markdown
    -   MultiMarkdown (MMD): a superset of Markdown
   - Textile
   - tkoutline



