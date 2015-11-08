## jargon

To publish on [jargon](jargon.io), just fork this repo and check your Markdown articles into the `/articles` directory.

### Extended Markdown

Jargon supports an extended version of [GitHub-flavored Markdown](https://help.github.com/articles/github-flavored-markdown/). In addition to normal fenced code blocks, you can also reference code files stored in your `/snipets` directory.

This will embed the file `foo.rb` stored in the `/snippets` folder.

```
[snippet: foo.rb]
```

This will embed lines 18-24 from the file `foo.rb` stored in the `/snippets` folder.

```
[snippet: foo.rb:18,24]
```
