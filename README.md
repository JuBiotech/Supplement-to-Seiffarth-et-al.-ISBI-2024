# Customizable and interactive visualizations to investigate spatio-temporal single-cell information

This repository contains the code for the paper `Customizable and interactive visualizations for investigating spatio-temporal single-cell informatio` by `Seiffarth et al.`. The paper introduces the construction of highly customizable and interactive visualizations for single-cell information in live-cell imaging. Interconnected visualization components provide an in-depth view into live-cell experiments at different information layers and level of detail. We utilize the html visualization capabilities of [plotly](https://pypi.org/project/plotly/) and [dash](https://pypi.org/project/dash/) libraries to implement three customizable visuailzations in python jupyter notebooks. These three visualizations notebooks serve as templates to gain insights in future live-cell experiments.

Have a look for yourself, execute the notebooks and dive in to the joy of interactive and interconnected visualizations. We provide the three notebook examples, they can be execute locally or in [colab](https://colab.research.google.com/) and [Binder](https://mybinder.org/) without a single installation instruction. Just click at the respective badges.

## 01 Lineage view

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/HEAD?labpath=View01_LineageCentric.ipynb)

<a target="_blank" href="https://colab.research.google.com/github/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/blob/release/View01_LineageCentric.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

The lineage view combines lineage tree, microscope image, single-cell area development and cell trajectory video components into a single and interconnected visualization.

[![Preview](https://github.com/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/blob/image-data/LineageView.gif)](https://youtu.be/8D7AMjg1yLE)

## 02 Descendants view

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/HEAD?labpath=View02_DescendantsView.ipynb)

<a target="_blank" href="https://colab.research.google.com/github/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/blob/release/View02_DescendantsView.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

The descendants view allows to explore the progeny (offspring) of individual cells using overlay visualizations on microscope images and interconnects the information with the temporal development of selected population sizes (area & and count).

[![Preview](https://github.com/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/blob/image-data/DescendantsView.gif)](http://www.youtube.com/watch?v=KZP5OoHpMVw)


## 03 Distribution view

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/HEAD?labpath=View03_DistributionView.ipynb)

<a target="_blank" href="https://colab.research.google.com/github/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/blob/release/View03_DistributionView.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

The distribution view allows to filter large amounts of single-cell data for rare or extreme events of cell size, cell lenght and cell age. These filters are combined with the microscopy images and the temporal visualization of the developmente filtered cell amounts.

[![Preview](https://github.com/JuBiotech/Supplement-to-Seiffarth-et-al.-ISBI-2024/blob/image-data/DistributionView.gif)](http://www.youtube.com/watch?v=qScXv45kyOU)


## Installation instructions

### Binder

You can use the buttons (open in binder) to launch the visualization notebooks in a binder environment.

### Colab

You can use the buttons `Open in colab` to launch the visualization notebooks in a colab environment.

**Note**: Rendered videos cannot be displayed in Colab.

### Local

You can also run the interactive data visualizations in your local jupyter notebook lab. For this, please install the conda environment and start the jupyter server using the following command:

```bash
conda env create -f environment.yml
conda activate viz-lab
jupyter lab
```

**Note**: Rendered videos **CAN** be displayed in the local jupyter lab instance.

