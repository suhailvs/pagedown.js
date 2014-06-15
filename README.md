pagedown.js
===========

http://code.google.com/p/pagedown/wiki/PageDown

Introduction
------------

PageDown is the JavaScript Markdown previewer used on Stack Overflow and the rest of the Stack Exchange network. It includes a Markdown-to-HTML converter and an in-page Markdown editor with live preview.

Usage
-----

	<script type="text/javascript" src="Markdown.Converter.js"></script>
	<script type="text/javascript">
		var converter = new Markdown.Converter();
		document.write(converter.makeHtml("**I am bold!**"));
	</script>