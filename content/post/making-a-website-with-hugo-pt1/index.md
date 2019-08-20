---
title: Building your own website with Hugo - Part 1
subtitle: Learn how to quickly and easily build a website like this using Hugo in just 5 steps.
summary: Learn how to quickly and easily build a website like this using Hugo in just 5 steps.
authors:
- admin
tags: []
categories: []
date: "2019-07-01T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

### Step 1: Install Homebrew and Go
<div class=text-justify>
Homebrew and Go are both required to build a website with Hugo. Homebrew is a free and open-source software package management system that simplifies the installation of software on macOS. Go is a programming language created by Google that Hugo will leverage to create your website framework. If you don't have Homebrew or Go installed on your computer, run the following in the terminal:
</div>
```python

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install go

```


![png](./academic_0_0.png)


```python
print("Welcome to Academic!")
```

    Welcome to Academic!


## Install Python and Jupyter

[Install Anaconda](https://www.anaconda.com/distribution/#download-section) which includes Python 3 and Jupyter notebook.

Otherwise, for advanced users, install Jupyter notebook with `pip3 install jupyter`.

## Create a new blog post [as usual](https://sourcethemes.com/academic/docs/managing-content/#create-a-blog-post)

Run the following commands in your Terminal, substituting `<MY_WEBSITE_FOLDER>` and `my-post` with the file path to your Academic website folder and a name for your blog post (without spaces), respectively:  

```bash
cd <MY_WEBSITE_FOLDER>
hugo new  --kind post post/my-post
cd <MY_WEBSITE_FOLDER>/content/post/my-post/
```

## Create or upload a Jupyter notebook

Run the following command to start Jupyter within your new blog post folder. Then create a new Jupyter notebook (*New > Python Notebook*) or upload a notebook.

```bash
jupyter notebook
```

## Convert notebook to Markdown

```bash
jupyter nbconvert Untitled.ipynb --to markdown --NbConvertApp.output_files_dir=.

# Copy the contents of Untitled.md and append it to index.md:
cat Untitled.md | tee -a index.md

# Remove the temporary file:
rm Untitled.md
```

## Edit your post metadata

Open `index.md` in your text editor and edit the title etc. in the [front matter](https://sourcethemes.com/academic/docs/front-matter/) according to your preference.

To set a [featured image](https://sourcethemes.com/academic/docs/managing-content/#featured-image), place an image named `featured` into your post's folder.

For other tips, such as using math, see the guide on [writing content with Academic](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
