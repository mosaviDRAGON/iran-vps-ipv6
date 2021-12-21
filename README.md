# Sanny Builder Help
[![Release](https://img.shields.io/github/v/release/MatiDragon-YT/help-system?style=for-the-badge)](https://github.com/MatiDragon-YT/help-system/releases)

Based on the original that brings the [`help.chm`](https://github.com/sannybuilder/help-system), GitBook and my own [`help3082.chm`](https://github.com/MatiDragon-YT/doc-chm).
This is the first offline version of [docs.sannybuilder.com](https://docs.sannybuilder.com/), worked together, to understand much of the GitBook site Markdown and highlight SB3 code easy and quickly.

![image](https://user-images.githubusercontent.com/43966706/146701538-c03bc730-51bc-414e-8253-f33cf0d591d9.png)
 
##### Table of content
* [Install](#install)
* [Collaborations](#collaborations)
  * [Creating pages](#creating-pages)
  * [Reporting issues](#creating-pages)
* [Compiling CHM files](#compiling-chm-files)
* [Thanks](#thanks)

## Install
Just download the chm corresponding to your language:

| file | language | state |
| --- | --- | --- |
| help | English | main |
| help3082 | Español | before long |

And optionally, move the file to directory.
```
<sanny builder foldes>\help\<here>
```

## Collaborations
The world is very welcome to collaborate in what you want with the documentation.\
Providing information, bug reports or optimizing the main script, which brings Markdown to life.

### Creating pages
After create a fork (cloning or downloading) of the repository. Just go to the folder that contains the section you want to collaborate on.\
For example to `help-system\<lang>\scm-documentation\sa\` and create any file with the extension `.HTML` with the following inside.

```html
<!DOCTYPE html>
<html>
<head>
  <title>Example Page</title>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" type="text/css" href="../../../style/style.css">
</head>
<body>

This is a template

<script src="../../../js/main.min.js"></script>
```
After, create your pull request and ready.

### Reporting issues
Just create a [ticket](https://github.com/MatiDragon-YT/help-system/issues/new) and describe in detail.

## Thanks
| Contributor | by |
| --- | --- |
| [Seemann](https://github.com/x87) | critics and error reports from early stages |
| yushae raza (darksavage) | Aggrege to SA the Vehicle ID List  |

## Compiling CHM files
Use HTML Help Workshop v4.
