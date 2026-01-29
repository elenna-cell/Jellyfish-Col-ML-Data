Data randomizer uses excel's mersenne's twister to generate uniformly random data based on Belbachir's given mean/sd (https://static-content.springer.com/esm/art%3A10.1007%2Fs00216-009-3019-y/MediaObjects/216_2009_3019_MOESM1_ESM.pdf). The data was corrected further by mean/sd scaling.

Training Data use data from Data randomizer to train based on JASP
Training Data+Jellyfish use data collected from Aurelia Collagen to cluster 

The RandomNumberGenerator.xlsx contains proper mean/SD adjusted randomdata, and can be used while ensuring that the mean/SD matched with Belbachir's source. These data are used in Trainingdata and Trainingdata+Jellyfish jasp file. 
In Data Randomizer Uniform, the generated data use default excel mersenne twister to output uniformly distributed data. However, the mean and SD is not adjusted to Belbachir's paper. This can be calculated and is used as demonstration why simply randomizing data will result in errenous dataset.
