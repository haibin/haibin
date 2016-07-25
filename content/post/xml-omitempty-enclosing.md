+++
date = "2016-07-25T23:09:02+08:00"
draft = false
title = "XML omitempty with enclosed elements"

+++

omitempty is only used in marshalling. But it does not work with enclosed elements.

https://play.golang.org/p/DEgzD3rwhw

http://stackoverflow.com/questions/27246275/golang-hide-xml-parent-tag-if-empty