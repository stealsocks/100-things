# 100-things

A grid theme with a pop-up iframe and [blocks.css](https://thesephist.github.io/blocks.css/) design. Intended to showcase the progress of your "Do 100 thing" project. 
/
The config.toml file provides access to a variety of CSS properties, allowing for personal customisation of your site's background, font, block elements and 

## Features
Responsive
Single-page
Easily customizable CSS
90/100 Google Lighthouse speed score 


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
/
/
You also need to copy the items.toml file from exampleSite => data into your site's data file. You will need to add an entry to this file for every post you add. The structure of each entry is as follows:

```toml

[[items]]
title = "Introduction"  
special = "false"
description = "Setting up your site."
url = "/posts/1"

```
Tese values will be shown on the corresponding "block" on your main page. The "special" value can be toggled between true or false depending on if you want it to be differently coloured than the others. Like most display settings in this theme, the particular color for these special blocks can be configured in your config.toml file. 
/
/
The url setting should be "posts/YOUR_POST_NAME"

## Editing the site's CSS:


