# Tensor Visualizer

An interactive tool for visualizing multidimensional tensors as expandable/collapsible trees.

**[Live Demo](https://snie2012.github.io/tensor_visualization/)**

## Features

- **Interactive tree** — each node represents an index in a dimension; click to expand/collapse on demand
- **Lazy rendering** — children are only rendered when expanded, keeping large tensors responsive
- **Color-coded dimensions** — each depth level has a distinct color with a legend
- **Collapsed previews** — see a summary of values without expanding
- **Random tensor generation** — type a shape (e.g. `2,3,4`) and generate a random tensor instantly
- **Custom input** — paste any nested JSON array to visualize your own data
- **Presets** — sample 2D through 5D tensors
- **Bulk controls** — expand all, collapse all, or expand to a specific depth

## Usage

Open `index.html` in a browser — no build step or dependencies required.

To generate a random tensor, enter a shape in the header input field (e.g. `3,4,5` or `2x3x4`) and press Enter.
