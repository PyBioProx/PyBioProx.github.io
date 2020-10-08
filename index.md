# An Introduction to PyBioProx

PyBioProx is a simple tool built in Python to analyze the relative proximity between fluorescent biomarkers in 2D or 3D microscopy images. 
For example, this can be used to analyse whether the distance between fluorescently labelled organelles or proteins (e.g. the distance
between mitochondria and the nucleus) changes according to experimental parameters. PyBioProx generates perimeter distance (PD) measurments (defined [here](url))
which represent the shortest distance between a perimeter pixel of an object in one fluorescent channel (e.g. Channel X) to the nearest fluorescent signal 
in another channel (e.g Channel Y). Each object detected in Channel X may have thousands of perimeter pixels and therefore has
perimeter distance (PD) measurements (as described ). As shown in the figure below, a PD measurment is 
thousands of PD measurments. We show in our [preprint](url), that taking the mean of these measurements (PD<sub>mean</sub>) describes the position of the 
object in Channel X relative to objects in Channel Y. Taking the maximum (Hausdorff Distance) and the minimum (PD<sub>min</sub>) PD
measurement *can* also provide useful information, the PD<sub>mean</sub> measurement performed 
most effectively in our [tests](url) and is our recommended statistic.

![](images/pybioprox-explanation.png) 
**Figure 1**  - An illustrative example in which a 3D (blue) object contains 12 perimeter voxels. The PD measurement for each perimeter voxel
is represented within each box. The smallest PD measurment represents the PD<sub>min</sub>, the largest PD measurment represents
the Hausdorff Distance, the mean PD measurement represents the PD<sub>mean</sub>

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/PyBioProx/PyBioProx.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
