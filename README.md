# Zippora Cahn
#Student in Computer Science and Animation at UMBC seeking position where I can grow my skills.

# CONTACT:
zcahn1@gmail.com


# EDUCATION 
University of Maryland Baltimore County (UMBC), Baltimore, MD —Computer Science & Animation B.S. & B.A.
2017 - Present (Expected date of graduation Fall 2020) 

Community College of Baltimore County (CCBC), Baltimore, MD —Computer Science A.S.
 2015 -  2017

# PROJECTS

Skate — Stop Motion Project for Introduction to Animation
Group stop motion project
https://www.youtube.com/watch?v=-18phq05nPk

Buzzword — Project for Special Effects and Motion Graphics
Created in AfterEffects.  The word that the video represents is Contrast
https://drive.google.com/file/d/1Om0TbuVz7Hh_E9l-wgcutVDgfSaQwr29/view?usp=sharing

Mask — Project for Advanced 3D
Created in Maya. Tasked with modeling a mask and lipsyncing to music.
https://drive.google.com/file/d/1KhC8sv2i455_wyOGWtkM_psEhjE0HN0p/view?usp=sharing 


Untied — Final Project for Introduction to Animation
Fully hand drawn 2D  animation
https://drive.google.com/file/d/1vRQKy9QcmwEDAUjw8-5wKUw3KaJRaCz2/view?usp=sharing


The Three Billy Goats — Final Project for Visual Concepts IV
Mix of live action and stop motion
https://drive.google.com/file/d/1Rglh8nf1GECFEz_sXGj4SlE1ZytWRnbW/view?usp=sharing


# OTHER EXPERIENCE

Law Offices of Frank B. Cahn, Pikesville, MD —Legal Clerk
 2017 - 2018
Responsibilities included: filing legal reports, office management and reception duties. 

Gan Yaffa, Pikesville, MD — Teacher
 2015 - 2017
Coordinated preschool children ages 2-8 and managed general business upkeep for day-to-day operations.




[![Build Status](https://travis-ci.org/pages-themes/architect.svg?branch=master)](https://travis-ci.org/pages-themes/architect) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-architect.svg)](https://badge.fury.io/rb/jekyll-theme-architect)

*Architect is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/architect), or even [use it today](#usage).*

![Thumbnail of Architect](thumbnail.png)

## Usage

To use the Architect theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-architect
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

Architect will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/architect/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

### Overriding GitHub-generated URLs

Templates often rely on URLs supplied by GitHub such as links to your repository or links to download your project. If you'd like to override one or more default URLs:

1. Look at [the template source](https://github.com/pages-themes/architect/blob/master/_layouts/default.html) to determine the name of the variable. It will be in the form of `{{ site.github.zip_url }}`.
2. Specify the URL that you'd like the template to use in your site's `_config.yml`. For example, if the variable was `site.github.url`, you'd add the following:
    ```yml
    github:
      zip_url: http://example.com/download.zip
      another_url: another value
    ```
3. When your site is built, Jekyll will use the URL you specified, rather than the default one provided by GitHub.

*Note: You must remove the `site.` prefix, and each variable name (after the `github.`) should be indent with two space below `github:`.*

For more information, see [the Jekyll variables documentation](https://jekyllrb.com/docs/variables/).

## Roadmap

See the [open issues](https://github.com/pages-themes/architect/issues) for a list of proposed features (and known issues).

## Project philosophy

The Architect theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Architect? We'd love your help. Architect is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](docs/CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/architect`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.
