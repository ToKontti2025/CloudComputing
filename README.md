# Task 01 - Deploying a static file with GitHub Pages

## Project overview

This task focuses on deploying a static HTML file using GitHub Pages.

The purpose of the task is to publish the practical implementation created earlier with Google Teachable Machine as a working static web page. The application is hosted from a GitHub repository and made accessible through a public GitHub Pages link.

## Objective

The objective of this task is to:

- deploy a static `index.html` file
- use GitHub Pages as the hosting platform
- create a working public GitHub repository
- produce a functioning GitHub Pages link

If the machine learning implementation is not available, the task can also be completed by hosting a simplified version of `index.html` without the ML functionality.

## Deployment target

The deployment target for this task is:

- GitHub Pages

## Key requirements

The task requirements are:

- functioning GitHub Pages link
- GitHub repository
- hosted `index.html`
- task addressed in the report

## Implementation

The deployed application is based on a static HTML file.

In this project:

- `index.html` is placed in the repository root
- the site is published through GitHub Pages
- the repository contains the required files for the page
- the application can be opened through a public browser link

If the Teachable Machine model is included, the repository also contains the required model files inside the `tm` folder.

## Repository structure

```text
CloudComputing/
├── index.html
└── tm/
    ├── metadata.json
    ├── model.json
    └── weights.bin