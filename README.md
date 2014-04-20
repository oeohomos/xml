xml
===

Lifting/unlifting support for XML literals in quasiquotes

Example
=======
[https://github.com/scalamacros/xml-example](https://github.com/scalamacros/xml-example)

Known issues
============

* `xml.Atom[T]` where `T` is not `String` is not fully supported
* `xml.Group` node is not supported
* doesn't yet build on 2.10 with paradise 
