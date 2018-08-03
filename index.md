---
layout: toppage
lang: en
title: top
---
<div class="jumbotron">
  <div class="container-fluid">
	<h1 class="display-4">Gura Programming Language</h1>
	<p class="lead">
	  A programming language that comes with powerful operation on iterators.
	</p>
	<p>
	  <a class="btn btn-primary" href="/download/"><i class="fas fa-download"></i> Download</a>
	  <a class="btn btn-primary" href="https://github.com/gura-lang/gura"><i class="fab fa-github"></i>
		View on GitHub</a>
	</p>
  </div>
</div>

<div class="container-fluid">
  <div class="card-deck">

<!-- card -->
	<div class="card">
<div class="card-body" markdown="1">
<h5 class="card-title">What's This?</h5>
**Gura** is an **iterator-oriented** programming language
that focuses on iterators with improved functions for calculation and data processing.
It gives you a new possibility to write more elegant codes than ever,
but with a familiar appearance.

Take a look at a simple example.
The following code prints content of a text file along with line numbers.

    printf('%d %s', 1.., readlines('foo.txt'))

Apparently, there seems to be no special trick with this program.
But a new feature called **Implicit Mapping** is working internally,
which automatically repeats evaluation of `printf` function
after it's given with iterators, `1..` and `readlines('foo.txt')`, as its arguments.
</div>
	</div>
<!-- card -->

<!-- card -->
	<div class="card">
	  <div class="card-body">
		<h5 class="card-title">Latest News</h5>
		<dl class="row">
		  <dt class="col-sm-3">2017-07-04</dt>
		  <dd class="col-sm-9"><a href="Download.html">Gura v0.7.0</a> was released.</dd>

		  <dt class="col-sm-3">2015-06-30</dt>
		  <dd class="col-sm-9"><a href="Documents.html">Documents</a> in PDF format were published.</dd>

		  <dt class="col-sm-3">2015-06-24</dt>
		  <dd class="col-sm-9"><a href="Download.html">Gura v0.6.2</a> was released.</dd>

		  <dt class="col-sm-3">2015-04-10</dt>
		  <dd class="col-sm-9"><a href="library-reference/index.html">Gura Library Reference</a> was published.</dd>

		  <dt class="col-sm-3">2015-01-07</dt>
		  <dd class="col-sm-9"><a href="Download.html">Gura v0.6.1</a> was released.</dd>
		</dl>
	  </div>
	</div>
<!-- card -->

  </div>

  <div class="card-deck mt-3">

<!-- card -->
	<div class="card">
<div class="card-body" markdown="1">
<h5 class="card-title">Features</h5>
* It provides a variety of iterator operations including mapping process
  such as **Implicit Mapping** and **Member Mapping**.
* It supports object oriented programming with class and instance mechanism.
* It's being shipped with various modules including powerful GUI toolkits
  that enable you to develop practical applications.
  The site [http://app.gura-lang.org/](http://app.gura-lang.org/) introduces you
  some applications that makes use of Gura.
</div>
	</div>
<!-- card -->

<!-- card -->
	<div class="card">
	  <div class="card-body">
		<h5 class="card-title">Resources</h5>
		<dl class="row">
		  <dt class="col-sm-3">
			<a class="btn btn-outline-secondary btn-sm" href="/document/"><i class="fas fa-book"></i> Document</a>
		  </dt>
		  <dd class="col-sm-9">Get detailed specification and other information of this language.</dd>

		  <dt class="col-sm-3">
			<a class="btn btn-outline-secondary btn-sm" href="/download/"><i class="fas fa-download"></i> Download</a>
		  </dt>
		  <dd class="col-sm-9">Get binary installer/packages and source tar-balls.</dd>

		  <dt class="col-sm-3">
			<a class="btn btn-outline-secondary btn-sm" href="/gallery/"><i class="fas fa-image"></i> Gallery</a>
		  </dt>
		  <dd class="col-sm-9">View screen snapshots of sample programs.</dd>
		</dl>
	  </div>
	</div>
<!-- card -->

  </div>
</div>
