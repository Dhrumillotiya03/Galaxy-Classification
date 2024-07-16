# Galaxy-Classification
The morphological classification of galaxies, broadly
into spirals and ellipticals, but also into more detailed categories
like barred/unbarred spirals, ellipticals and spheroidals has been
a long-standing theory in astronomy and cosmology. With the
rapid influx of data from instruments starting from SDSS,
JWST and soon-to-be LSST, it increasingly becomes infeasible
for classification by human experts (or even amateurs), thereby
necessitating the use of machine learning models like the con-
volutional neural networks (CNNs) on these galaxy images. If
such models are trained on data of older telescopes and aimed
to be used on that from newer ones, checking the accuracy of
such models across datasets becomes imperative. In this project,
we perform this analysis for galaxy image datasets from two
telescopes - the Sloan Digital Sky Survey (SDSS) and the Dark
Energy Camera (DECam). In each case, we train a CNN on one
of the image sets and check its accuracy on the other wherever
cross-labelling is possible, for 7 to 10 finely divided classes. We
also check the same for coarser classification of 3 classes. Our
findings suggest that while these models may not perform well
for finely classified galaxy images, they can serve as a reliable
indicator for coarse classification into spiral, disk and elliptical
galaxies.
