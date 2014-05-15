wd_s
====

A new project boilerplate.

### Includes

* _s (Sass fork)     [automattic](https://github.com/Automattic/_s), [gregrickaby](github.com/gregrickaby/_s/tree/sass)
* CMB                [webdevstudios](https://github.com/WebDevStudios/Custom-Metaboxes-and-Fields-for-WordPress)
* Taxonomy Core      [jtsternberg](https://github.com/jtsternberg/Taxonomy_core)
* CPT Core           [jtsternberg](https://github.com/jtsternberg/CPT_Core)
* Basic MU Plugin

### Installation

You'll need to clone recursive this repo, not download the zip! (It includes other Github submodules and they won't be included in the zip)

`git clone --recursive https://github.com/WebDevStudios/wd_s.git`

Via SourceTree:

![Alt text](https://www.dropbox.com/s/tx1boq1fgl6myg2/Screenshot%202014-05-14%2020.30.44.png "SourceTree")

### Getting Started

You'll need to change all instances of the names: _s and "project".

* Search for: `'_s'` and replace with: `'your theme name'`
* Search for: `_s_` and replace with: `your theme name_`
* Search for: <code>&nbsp;_s</code> and replace with: <code>&nbsp;Megatherium</code>
* Search for: `_s-` and replace with: `your theme name-`
* Search for: `Text Domain: _s` and replace with: `Text Domain: your theme name` in style.css.
* Search for: `'project'` and replace with: `'your theme name'`
