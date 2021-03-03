# SDG Graph 

## Introduction

This project visualizes the Sustainable Development Goals (SDGs) as a graph in your browser.
- nodes are goals, targets, and indicators
- edges show associations of targets to goals, and indicators to targets


## Features

Features:
- concentric layout
- zoom and pan via gestures or UI widget (thanks to [panzoom](https://github.com/cytoscape/cytoscape.js-panzoom) and [Font Awesome](https://fontawesome.com/))
- tooltips show node information on hover (thanks to [cy-popper](https://github.com/cytoscape/cytoscape.js-popper) and [popper](https://popper.js.org/))
- collapse / expand parts of the graph for better overview
- search for nodes based on their text content


## Acknowledgements
This project relies on [datapopalliance's SDG data](https://github.com/datapopalliance/SDGs), which offers SDG data in a machine-readable format and on [Cytoscape.js](https://js.cytoscape.org/) for the graph visualization.