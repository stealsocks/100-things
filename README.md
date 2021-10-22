# 100-things

A grid theme with a pop-up iframe and [blocks.css](https://thesephist.github.io/blocks.css/) design. Intended to showcase the progress of your "Do 100 thing" project. 

![image](https://user-images.githubusercontent.com/73769521/138274660-19bb26e2-aaf8-401a-bdb2-859d5e9c982d.png)

The config.toml file provides access to a variety of CSS properties, allowing for personal customisation of your site's background, font, block elements and button design.


## Features:
-Responsive\
-Single-page\
-Easily customizable CSS\
-90/100 Google Lighthouse speed score
-"Special" blocks to highlight the creations you think are decent 

## Installation:

### Option 1: Direct download 

Click on the green "Code" button, and choose the "Download ZIP" option. Extract the contents of the .zip file into the themes folder of your site.

### Option 2: Clone using github URL

In your terminal, navigate to your website folder and run the following:

```

cd themes
git clone https://github.com/liuzc/LeaveIt.git

```


## Getting Started:

After installation, you need to copy the config.toml file from the exampleSite folder into your the root folder of your site. Edit the values to your preffered settings.

You also need to copy the items.toml file from exampleSite => data into your site's data file. You will need to add an entry to this file for every post you add. The structure of each entry is as follows:

```toml

[[items]]
title = "Introduction"  
special = "false"
description = "Setting up your site."
url = "/posts/1"

```
Tese values will be shown on the corresponding "block" on your main page. The "special" value can be toggled between true or false depending on if you want it to be differently coloured than the others. Like most display settings in this theme, the particular color for these special blocks can be configured in your config.toml file. 


The url setting should be "posts/YOUR_POST_NAME"


## Editing the site's CSS:
Open the config.toml file and edit the values of the properties like you would a regular CSS file.\

e.g.
```
# Body background color
    bgcolor= "black"

# Text color
    textcolor =  "#FFFFFF"
```

## Adding a new post:

Create a posts folder inside your site's content folder and add a new markdown file. Then open data => items.toml and add a new entry for that post to make sure it's displayed on the home page grid.


## Using the < content > shortcode:
If you want to make sure your image, video or audio player are centered, add them inside a content shortcode like below:
```
{{< content >}}
<img src="/mage.jpeg" />
{{< /content >}}

```



