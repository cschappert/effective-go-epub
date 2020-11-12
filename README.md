# Effective Go (EPUB)

[Effective Go](https://golang.org/doc/effective_go.html), converted from HTML to EPUB
using [calibre](https://calibre-ebook.com/) and then touched up by hand.

Content is from golang.org and licensed under the Creative Commons Attribution 3.0 License as detailed [here](https://golang.org/doc/copyright.html).

# Building

Just zip the contents of `src` (not including the `src` directory itself) and change the extension from
`.zip` to `.epub`.  If required, it should then be possible to convert the EPUB to MOBI using any popular tool including 
[calibre](https://calibre-ebook.com/).

# TODO

## Automation

* Automate the process of retrieving the source content and producing an EPUB
* Automate stripping (for example) `<script>` tags and other superfluous content from the ebook