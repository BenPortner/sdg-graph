# SDG Graph 

## Introduction

This project visualizes the Sustainable Development Goals (SDGs) as a graph in your browser.
- nodes are goals, targets, and indicators
- edges show associations of targets to goals, and indicators to targets

See interactive [demo on nbviewer](https://nbviewer.jupyter.org/github/BenPortner/sdg-graph/blob/main/index.html).


## Features

Features:
- concentric layout with goals at the center and indicators at the edge
- user can zoom and pan via gestures or UI widget (thanks to [panzoom](https://github.com/cytoscape/cytoscape.js-panzoom) and [Font Awesome](https://fontawesome.com/))
- user can hover over nodes to show tooltips with further information (thanks to [cy-popper](https://github.com/cytoscape/cytoscape.js-popper) and [popper](https://popper.js.org/))
- user can click on a node to collapse / expand parts of the graph for better overview
- user can double-click on a node to zoom in on it
- user can search for nodes based on their description or id


## Acknowledgements
This project relies on [datapopalliance's SDG data](https://github.com/datapopalliance/SDGs), which offers SDG data in a machine-readable format and on [Cytoscape.js](https://js.cytoscape.org/) for the graph visualization.