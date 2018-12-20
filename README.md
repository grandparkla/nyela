# Grand Park LA, New Year’s Eve

A website for the New Year’s Eve event at Grand Park, Los Angeles

https://nyela.grandparkla.org

* [How to make changes](#how-to-make-changes)
* [How to add an image](#how-to-add-an-image)
* [How to develop locally](#how-to-work-locally)
* [Handy guides](#handy-guides)

## How to make changes

The website is published with [GitHub Pages](https://pages.github.com) and the files are generated with [Jekyll](https://jekyllrb.com).

As you make changes and commit/push them to GitHub, the [website](https://nyela.grandparkla.org) will automatically update.

For example, if you [edit the home page](https://github.com/grandparkla/nyela/edit/master/index.markdown) on GitHub, and then press the “Commit changes” button–you should see your changes on the [home page](https://https://nyela.grandparkla.org) of the website within a few minutes.

## How to add an image

If you want to add an image (or any file) to the website, you can upload it to one of the folders on GitHub.

The [uploads folder](https://github.com/grandparkla/nyela/tree/master/_uploads) is generally a good choice, if you’re unsure where to put a file.

Once you’ve chosen a folder, follow these steps:

1. Press the `Upload files` button

2. Use the uploader to upload your files

3. Press the `Commit changes` button

It’s best to use lowercase letters and dashes instead of spaces for your filename. For example: `aloe-blacc.jpg`.

Once your file has been uploaded it be available at a web address that corresponds to the folder and filename that you chose. For example:

```
/uploads/aloe-blacc.jpg
```

To use this on the website, you can create an image with [markdown](https://guides.github.com/features/mastering-markdown/):

```
![Aloe Blacc](/uploads/aloe-blacc.jpg)
```

You can also create an image with [HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

```
<img src="/uploads/aloe-blacc.jpg" alt="Aloe Blacc" />
```

## How to work locally

If you want to see a preview of your changes while you work, you can [run Jekyll](https://jekyllrb.com) on your computer. [Installing Ruby and Jekyll](https://jekyllrb.com/docs/installation/) is a good place to start.

After you have Jekyll installed, you can clone this project with [GitHub Desktop](https://desktop.github.com).

And then start running Jekyll by entering this command into your [terminal](https://en.wikipedia.org/wiki/Terminal)..

```
jekyll serve
```

## Handy guides

* [Markdown](https://guides.github.com/features/mastering-markdown/)
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [Jekyll](https://jekyllrb.com/docs/home/)
* [GitHub Pages](https://pages.github.com)

