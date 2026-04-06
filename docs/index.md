# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
I used the provided system metrics time-series dataset with timestamps, requests, errors, and latency.

### Signals
I used rolling mean signals and added a rolling maximum signal for requests.

### Experiments
I increased the window size from 3 to 5 and added a rolling max to compare trends vs peaks.

### Results
The larger window smoothed the data more, while the rolling max highlighted high request spikes.

### Interpretation
This helps show both overall trends and peak activity, which could help monitor system load and detect spikes.
