# DYMOLA singularity image

## Creating image

Put the DYMOLA installation archive in the same folder as as the dymola.def file. Create the image with:

    sudo singularity build dymola.sif dymola.def

## Running DYMOLA

The image will by default start Dymola

