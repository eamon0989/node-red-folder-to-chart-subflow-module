# Usage

This is a custom subflow module that takes a filepath as input via the UI (it should be the path to a directory containing valid JSON certificates) as well as the element you want extracted, as well as max and min values, and plots them to a Scatter Chart.

# Installation

Until this module is published, it needs to be installed locally. Go to the directory containing your node-red files and run `npm install <path-to-this-module>`. Installing local modules does not appear to correctly install dependencies, so you may have to manually install the [`node-red-chartjs`](https://github.com/eamon0989/node-red-chartjs) dependency in your node-red directory which allows access to the chartjs code.

