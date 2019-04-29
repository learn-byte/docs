# Folder Structure and Images

### In order for the course to presented correctly on learn-byte.com a few folder structure rules should be followed

Here is what a good folder structure looks like for a `learn-byte.com` course:

```
assets
├── images
│   ├── star.png
│   └── lightning-bolt.png
├── other
│   └── some-other-asset.txt
course
├── 01-Welcome-to-the-Course
│   ├── 01-welcome.md
│   └── 02-in-this-course.md
├── 02-Getting-Started
│   ├── 01-create-file.md
│   ├── 02-import-libs.md
│   └── 03-write-script.md
├── 03-Deploying-Project
│   ├── 01-provision-infrastructure.md
│   └── 02-celebrate.md
└── README.md

```
You will likely want to prefix the names of your files and folders with numbers so that they stay in proper order.  The files and folders are sorted and presented alpha numerically, so the order can be easily controlled with number prefixes.

### You can add images or other resources to your course files in an assets folder at the root level of the repository.

Images can be in any common web file format and are easy to include in markdown. If you follow the above file structure then linking to images can be accomplished like so:

`https://raw.githubusercontent.com/learn-byte/YOUR-REPOSITORY-NAME/master/assets/images/YOUR-IMAGE-NAME.png`

Refer to markdown cheatsheet for [instructions on how to link images](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images) in markdown.