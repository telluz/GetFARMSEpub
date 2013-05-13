# gobook.go
Maxwell Institute Book to ePub Converter
Based on GetBook.py by Matt Turner (http://guavaduck.com/)
Converted to Go

## Why?
I found GetBook.py in my search for F.A.R.M.S. books in epub format. But, I use Mac OS X, and tinylib is a nightmare situation.

I like Go, but haven't had much call to use it. This seemed like a great opportunity, so I embarked what is essentially a straight port from Python to Go.

## What works
* content fetching appears to work correctly including title, author, and chapter parsing
* creating the directory and file layout (and populating the data)

## What doesn't work
* it's not zipped up into a .epub file, just left as a directory
* epubcheck reveals various warnings (and errors) that could be fixed with some html validation
