# CNN Breast Cancer Detection _Using Keras_

Second Data Science Project of my list.



## Dataset source

https://tampapath.medium.com/new-freely-available-lung-and-colon-cancer-image-dataset-for-ml-researchers-94756581ed81

​		↓↓

https://academictorrents.com/details/7a638ed187a6180fd6e464b3666a6ea0499af4af

​		↓↓

Torrent magnet: 

```magnet:?xt=urn:btih:7a638ed187a6180fd6e464b3666a6ea0499af4af&tr=http%3A%2F%2Facademictorrents.com%2Fannounce.php&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969```

(Gave problems with uTorrent, I used JSTorrent)

### Folder disposition

Extract the files like this:

```` bash
data
├── colon_image_sets
│   ├── colon_aca
│   └── colon_n
└── lung_image_sets
    ├── lung_aca
    ├── lung_n
    └── lung_scc
````

## Info about dataset

25000 images.

There are 2 different types of pathologies on this dataset: Colon and Lung.

- On the Colon part, ``\colon_n`` has non cancer images, and ``\colon_aca`` has cancer images.

- On the Lung part, ``\lung_n`` has not cancer images, ``\lung_aca`` contains  [adenocarcinoma cells](https://en.wikipedia.org/wiki/Adenocarcinoma_of_the_lung) and ``\lung_scc`` contains [squamous cells](https://en.wikipedia.org/wiki/Squamous-cell_carcinoma_of_the_lung) .

## To read

https://www.kaggle.com/thebrownviking20/intro-to-keras-with-breast-cancer-data-ann

https://www.pyimagesearch.com/2019/02/18/breast-cancer-classification-with-keras-and-deep-learning/

https://medium.com/analytics-vidhya/sub-classifying-lung-cancer-with-tensorflow-2-and-keras-616353e59e5e