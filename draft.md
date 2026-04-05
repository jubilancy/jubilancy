Since you're setting up your profile README to display these metrics, here is a clean `README.md` template. It includes all the variations you mentioned, organized with descriptions so you can choose the one that fits your layout best.

* * *

# My GitHub Metrics

This repository uses [lowlighter/metrics](https://github.com/lowlighter/metrics) to generate dynamic statistics about my open-source activity. Below are the different ways to embed the generated `github-metrics.svg` into a profile README.

## 1\. Standard Markdown

The simplest way to display the image. It scales automatically to the width of the container.

Markdown


![Metrics](/github-metrics.svg)


## 2\. Centered with HTML

Use this if you want to control the alignment and the specific width of the image (e.g., to keep it from looking too large on desktop).

HTML


<p align="center">
  <img src="/github-metrics.svg" alt="Metrics" width="400">
</p>


## 3\. Prevent Auto-Linking

GitHub often automatically turns images into clickable links that lead to the raw file. Wrapping the image in a `<picture>` tag prevents this behavior, keeping the UI cleaner.

HTML


<picture>
  <img src="/github-metrics.svg" alt="Metrics">
</picture>


## 4\. Full-Width (Column Display)

If you have configured your metrics to display in multiple columns (using `config_display: columns`), use this code to ensure the SVG stretches to fill the entire horizontal space of your profile.

HTML


<img src="/github-metrics.svg" alt="Metrics" width="100%">


* * *

### 💡 Implementation Note for @jubilancy

Since your workflow generates the file and saves it to your repository, ensure the path `/github-metrics.svg` is correct. If the action saves it to a specific folder (like `output/`), you would change the path to `/output/github-metrics.svg`.
