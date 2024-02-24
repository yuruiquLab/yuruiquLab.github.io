---
permalink: /
title: "Micro-Nano Optoelectronic Devices and Computing Lab"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Research
------
Manipulation of micro- and nanoscale structures can give rise to many new material systems photonic crystals, metamaterials, and metasurfaces, and give rise to many novel physical phenomena such as negative refraction and cloaks of invisibility, which cannot be realized with any natural material. Our research interest lies in exploring the exciting new physical phenomena arising from such novel materials with applications in many fields such as optical computing, infrared camouflage, computational imaging, and optical sensing. Our work is both theoretical and experimental. Our research is divided into three main parts：

**Photonic Neural Networks**

Optical computing has advantages and potential over electronic computing due to its massively parallel processing capability and almost no power consumption in some tasks. Our group has been working on developing different photonic neural network architectures, such as [photonic convolutional neural network (CNN)](https://www.sciencedirect.com/science/article/pii/S2095927320302115), [photonic recurrent neural network (RNN) and photonic long short-term memory (LSTM) networks](https://pubs.acs.org/doi/abs/10.1021/acsphotonics.1c02016), using inverse design algorithms to encode optical signals through the temporal and spatial domains.
![Editing a markdown file for a talk](/images/Research direction-1.png)

**Smart optoelectronic Devices**
Advanced intelligent algorithms can help optoelectronic functional devices break through the traditional spatial and temporal limitations, realize miniaturization and intelligence of optoelectronic devices, and improve device resolution and response speed. For example, we have developed [an ultra-fast millisecond mid-infrared material identification spectrometer based on compressed sensing algorithms](https://arxiv.org/abs/2212.13122), where traditional Fourier transform spectrometers require tens of seconds to minutes of measurement time.
![Editing a markdown file for a talk](/images/Research direction-2.png)

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
