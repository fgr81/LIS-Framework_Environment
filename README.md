# Singularity ( or Apptainer) container for LIS-Framework
## developed and tested on version 7.5.0 (https://github.com/NASA-LIS/LISF/releases/tag/v7.5.0-public)

### Building the container:
singularity build --fakeroot lis_env.sif recipe.def

### Use of the container:
0. Following this tutorial: https://nasa-lis.github.io/LISF/public_testcase_walkthrough/public_testcase_walkthrough.html, extract LISF and create the 'working' folder. 
1. Place the container in the folder hosting LISF too.
2. Edit and source compileX.source to obtain LDT, LIS, LVT.
