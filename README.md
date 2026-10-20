# HPC Local Impact Dashboard

An interactive learning dashboard that shows how High-Performance Computing (HPC) can tackle real local problems by crunching large datasets and running simulations.

**Author:** Juan Agraprana Putra
**Student ID (NPM):** G1A023085

## Included scenarios

- **Flood modelling:** see how terrain, rainfall, and river-flow data can feed into flood scenario analysis.
- **Forest monitoring:** look at how large volumes of satellite imagery can be processed to detect changes in land cover.
- **Energy planning:** try out computational scenarios for local electricity demand and grid planning.

## Key features

- A selector for switching between local challenges.
- A workload simulator with adjustable compute nodes and workload sizes.
- Illustrative estimates of runtime, speedup, and time saved.
- Runtime comparison and scaling charts built with Chart.js.
- Responsive design with a mobile menu and a dark mode.
- A walkthrough of the typical path from raw data to a decision.

## Built with

- HTML5
- CSS3
- Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/)

## Running it locally

There is no build step.

1. Download or clone this repository.
2. Open `index.html` in a browser, or serve it with the VS Code Live Server extension.
3. Stay online, since Chart.js and Google Fonts are loaded from CDNs.

## Deploying with GitHub Pages

1. Create a GitHub repository and place all four project files in its root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, pick **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then save.
5. Give GitHub Pages a moment to publish the site.

## About the simulator

The simulator relies on a simplified model that combines a serial fraction with an assumed parallel efficiency. It approximates how runtime might shrink as more compute nodes are added. These figures are for illustration only; they are neither measured benchmarks nor claims about any real HPC cluster.

In practice, performance is shaped by the processor and accelerator design, memory, interconnect, storage, how well the workload can be parallelized, the software implementation, and the cost of moving data.

## Disclaimer

Every value shown is a synthetic example made for learning and portfolio purposes. The dashboard does not connect to an actual HPC cluster, run a scientific model, process live satellite data, or produce genuine flood, forest, or energy forecasts.