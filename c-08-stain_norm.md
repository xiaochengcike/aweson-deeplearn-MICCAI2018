## A Nonlinear Mapping Approach to Stain Normalization in Digital Histopathology Images Using Image-Specific Color Deconvolution(2014)

a novel approach to stain normalization in histopathology images, stain matrix estimation and stain normalization methods

### Background
Color variation is a problem in histopathology based on light microscopy due
to a range of factors such as the use of different scanners,
variable chemical coloring/reactivity from different manufacturers batches of stains, coloring being dependent on staining
procedure (timing, concentrations, etc.), and light transmission being a function of section thickness.

color variation in histopathology has become more of an issue.

We, stain normalization can improve the performance of histopathology image analysis algorithms, especially when data come 
from different scanners.

Tumor segmentation is also vital for automated scoring of IHC-stained slides to restrict the scoring or analysis to areas containing
tumor cells only and avoid potentially misleading results from analysis of stromal(基质的) regions.

Color inconsistency between tissue sections within and between laboratories, or between different scanners is a significant 
issue in histopathology.

CD-based approaches come out the best.

### Past methods
Reinhard et al. \[7] proposed a method of color normalization where the mean and standard deviation of each channel of
the image are matched to that of the target by means of a set of linear transforms in Lab colorspace.

### Method
each image Ii is color quantized using Qct-tree quantization to generate a set of histograms of 255 color protypes
H = {H1, H2, ..., Hk}

Pixels assigned a probability greater than some threshold Tp are used to calculate the examplar color for each stain.
