# 3DLeafTortuosity
Computing plant leaf tortuosity from microCT stacks

Recent updates:

__2018-04-27__
- Added stomata lbelling method in the preamble.
- Splitted cells here and there to separate some bits.
- Moved older updates to README.md

__2018-04-26__
- Changed np.array `dtype` to boolean to produce smaller files (might be useful for very large files).
- Added a definition of the pixel values to facilitate the thresholding.
- Created a amphistomatous epidermis to compute L_epi.
- Moved the functions to a separate file.
- Included code to save the tortuosity factor and lateral diffusivity files for later processing (commented out).
