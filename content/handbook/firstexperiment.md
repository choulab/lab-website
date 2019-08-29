---
title: Your first experiment
linktitle: Your first experiment
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu: 
  handbook:
    parent: Getting Started
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 70
---

Always generate a complete protocol before starting an expperiment. You can base yours on this [template](/), which has the following elements:

- Experiment Number (e.g. LC001)
- Experiment Title (e.g. protein expression)
- Date
- A hypothesis (for investigative experiments) or objective (for preparative experiments)
- A complete list of reagents
- A complete list of steps

You can write this out in a Word-based editor or Google Doc. When do you do the experiment, document any changes so that your protocol reflects what you *did*, not what you *intended*. You can use the common computer at the lab bench to make these changes in real-time.

{{% alert note %}}
Tips

1. If you have never done this experiment before, chances are you will be missing reagents. Use the protocol to help you gather them.
2. Use tables instead of text whenever possible. For example, present buffer compositions and reagent preparations in tabular format. Use an Excel template to populate them and copy paste ovder to your text editor.
{{% /alert %}}

Once you have completed your experiment, store the raw data and the protocol in the same folder. This folder should be placed in a centralized lab server, within the corresponding project's `Experiments` folder. 

Finally, any analyses, e.g. generating plots from data, should be placed in the same folder. We advocate using software such as [Python](https://www.python.org) for all of your data analysis. The easiest way to obtain Python is via the [Anaconda](https://www.anaconda.com/distribution/) distribution, which comes with most if not all of the most common data analysis packages pre-installed. When your've completely finished an experiment, the folder should have the following contents:

- protocol
- raw data
- analysis
- plots generated from analysis

A collection of these items will then serve as a starting point for preparing deliverables, e.g. reports, manuscripts, talks...etc.





