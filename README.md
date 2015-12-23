enmime [![Build Status](https://travis-ci.org/jhillyerd/go.enmime.png?branch=master)](https://travis-ci.org/jhillyerd/go.enmime) [![GoDoc](https://godoc.org/github.com/jhillyerd/go.enmime?status.png)](https://godoc.org/github.com/jhillyerd/go.enmime)
======

enmime is a MIME parsing library for Go.  It's built ontop of Go's included mime/multipart
support, but is geared towards parsing MIME encoded emails.

It is being developed in tandem with the Inbucket email service.

API documentation can be found here:
http://godoc.org/github.com/jhillyerd/go.enmime

Note : this version has a patch from Harrison Teng at Fusemail which addresses issues in the multipart message.
       The patch is is based on master branch of this commit: "Latest commit 957809c  on 25 Aug 2015".

Development Status
------------------
enmime is alpha quality: it works but has not been tested with a wide variety of source data,
and it's likely the API will evolve some before an official release.

About
-----
enmime is written in [Google Go][1].

enmime is open source software released under the MIT License.  The latest
version can be found at https://github.com/jhillyerd/go.enmime

Note
-----

[1]: http://golang.org/
