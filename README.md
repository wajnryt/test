## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/wajnryt/test/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<head><script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@0.12.0"> </script>\n
  
\
<script>\n\
          async function loadModel(){ \n\
              model = await tf.loadModel(\'web_model/model.json\') \n\
              y = model.predict(tf.zeros([1,2])) \n\
              document.getElementById(\'out\').innerHTML = y.dataSync()[0] \n\
          } \n\
          loadModel() \n\
</script>\n\
</head> \n

\
<body>\n\
        <p id =\'out\'></p> \n\
</body>


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/wajnryt/test/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
