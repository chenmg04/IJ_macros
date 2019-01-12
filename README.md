# IJ_macros
ImageJ Macros for batch processing multiple image files.

batch_process_ZSeries.txt batch process multiple ZSeries image folders under the same directory(acquired by PrairieView from Burker): reads each fold as a single multipage TIFF file, gets Max Z-projection for each file, auto enhance the contrast, then registers and stitches them as a single neuron.  This Macro applies for experiments taking many image stacks for the morphology of single neurons, but can be easily adapted for other applications.  
