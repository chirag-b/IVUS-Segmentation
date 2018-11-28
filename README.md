[NumPy]: http://www.numpy.org/ 
[Keras]: https://keras.io/
[Tensorflow]: https://www.tensorflow.org/
[Matplotlib]: https://matplotlib.org/
[scikit-image]: http://scikit-image.org/docs/dev/api/skimage.html
[HDF5 For Python]: https://www.h5py.org/
[Sample-Image]: /sample-image/frame_01_0001_003.png
      

# IVUS-Segmentation
Segmentation of Intravascular Ultrasound images.


## Introduction
This project aims to segment the media and lumen in ultrasound images of arteries. This problem is important because, atheroscelorotic plaque build up can narrow the walls of the arteries(stenosis) and lead to myocardial infarction. The segmentation of lumen and media borders can help doctors locate such plaque build up and help reduce the effects of stenosis if identified earlier. 

## Requirements
  + [NumPy]
  + [Keras]
  + [Tensorflow]
  + [MatplotLib]
  + [scikit-image]
  + [HDF5 For Python]
  

## Dataset
The dataset used for this project consists of ultrasound scans of size 384x384. Training set comprised of 109 images and test set comprises of 326 images. A sample image from the dataset. More information about the dataset is available in [1]

<img src=/sample-image/frame_01_0001_003.png height=200 width=200></img>


## Citation
A paper on this project is available in the archive [here](https://arxiv.org/abs/1806.07554). Please cite using the following BibTeX entry.
```
@article{DBLP:journals/corr/abs-1806-07554,
  author    = {Chirag Balakrishna and
               Sarshar Dadashzadeh and
               Sara Soltaninejad},
  title     = {Automatic detection of lumen and media in the {IVUS} images using
               U-Net with {VGG16} Encoder},
  journal   = {CoRR},
  volume    = {abs/1806.07554},
  year      = {2018},
  url       = {http://arxiv.org/abs/1806.07554},
  archivePrefix = {arXiv},
  eprint    = {1806.07554},
  timestamp = {Mon, 13 Aug 2018 16:49:04 +0200},
  biburl    = {https://dblp.org/rec/bib/journals/corr/abs-1806-07554},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

## References
[1] `Balocco, S., Gatta, C., Ciompi, F., Wahle, A., Radeva, P., Carlier, S., Unal, G.,
Sanidas, E., Mauri, J., Carillo, X., et al.: Standardized evaluation methodology and
reference database for evaluating ivus image segmentation. Computerized medical
imaging and graphics 38 (2), 70–90 (2014)`
