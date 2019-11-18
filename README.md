# DLRG-Wettkampfpunkte

## Features

Two html snippets, which create graphs (user's swimming time vs. awarded points) based on the current German national records in Life saving swimming.

All computations are done client side. Plotting is done via [D3.js](https://www.d3-graph-gallery.com/).

## Installation

Insert the html snippets into your web page. Install D3.js on your web page and load it in your page header via `<script type="text/javascript" src="d3/d3.v2.min.js"></script>`.

## Update records

To update the records used to compute the awarded points, you need to update the variable `rekorde` in the script.
