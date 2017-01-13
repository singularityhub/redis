# Redis

This is the official library of redis builds for Singularity images hosted on Singularity Hub. The following standard applies:

 - each `Singularity` file corresponds to a build
 - each branch corresponds with a different verison, or tag. 

## Usage

    sudo singularity create redis.img
    sudo singularity bootstrap redis.img Singularity
