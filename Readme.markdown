These are the articles that appear on my blog, http://paradox.gd.

If you see a spelling mistake or a correction that needs to be made, please fork it, edit it in, and make a pull request. I love any help I can get

The syntax is mostly pure markdown, but with a few special exceptions.

# Images
You can add images using markdown's image syntax, although this isn't optimal. I've provided a better image syntax for use.

```
{% img [class] url [width] [height] '[title]' '[alt] %}
```

# Blockquotes
Quotes are another thing that markdown provides for, but their implementation is…lacking. To do a quote, you can do the following:

```
  {% blockquote [author, source] [link] [link-title]%}
  This is inside a blockquote
  {% endblockquote %}
```

If you know the author, but not the source, just end Author with a comma, like so: `Mark Twain,`

# Pullquotes
Pullquotes are the quotes that appear in larger text off to the side. They add typographic flourishes, and break up long blocks of text. They are a little tricky to use, however

```
{% pullquote [left|right] %}
This is a paragraph. It has text that isnt in a pullquote, and {" text that is in a pullquote. "}
{% endpullquote %}
```

Thanks!
