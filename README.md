# gitbook-plugin-section

This plugin will add table of content to the page and provide navigation function inside a page.

Add `<!-- toc -->` to the markdown files. When you build the book, it will insert a table of content where you insert `<!-- toc -->`


`book.json` Config:


```
{
	"plugins": ["section"],
	"pluginsConfig": {
		"section": {
			"addClass": true,
			"className": "tsection"
		}
	}
}
```

You can add this config to add a HTML ClassName to the Section `ul` element

<img src="https://gw.alicdn.com/tps/TB1YiC4LFXXXXcrXFXXXXXXXXXX-1908-1126.jpg" width="640px">