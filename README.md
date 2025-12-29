# MetaE-former
A surrogate electromagnetic solver
## Dataset of MetaE-former
Here, we present typical examples from the pre-training and fine-tuning datasets. For ease of visualization, we only display the Ex component of the electric field, which is the most relevant for our problem.

**Data Structure:**\
In each `.mat` file within the `.rar` archives, the first three columns of the **E** array correspond to the Ex, Ey, and Ez components, respectively. Reshaping each component into a [100, 100] array yields the data visualized in the figures below. The **H** array follows the same structure.

**File Naming Convention:**

In `pre-training.rar`: Files are named `dataxxx.mat`, where xxx corresponds to the data index.\
In `fine-tuning.rar`: Files are named in the format `continuous_x_0.00_y_64.00`, where:\
**continuous** indicates a non-binarized meta-atom, while **discrete** indicates a binarized one.\
**0.00** and **64.00** represent the coordinates (in μm) of the meta-atom's top-left vertex within the overall metasurface.
！[]()
