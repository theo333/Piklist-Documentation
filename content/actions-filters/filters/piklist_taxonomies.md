---
title: "piklist_taxonomies"
description: "Extends the standard WordPress function register_taxonomy with additional features and parameters."
hidden: "true"
---

#### `apply_filters('piklist_taxonomies', self::$taxonomies);`

Extends the standard WordPress function [register_taxonomy()](https://codex.wordpress.org/Function_Reference/register_taxonomy) with additional features and parameters.

## Parameters
`piklist_taxonomies` supports all parameters from `register_taxonomy()` as well as these custom parameters:

### `object_type`

Set this parameter to use this Piklist taxonomy for users

* Input:  Array

Example:

`'object_type' => 'user`

### `hide_meta_box`

Hide the meta box created by this taxonomy

* Input:  Array

Example:

`"hide_meta_box" => true`

### `meta_box_filter`

Add a filter to this meta box to make it easier to search for terms.

* Input:  Array

Example:

`"meta_box_filter" => true`
