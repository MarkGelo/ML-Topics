# Stylegan2-ada

Using stylegan2-ada to generate food images...
and other stuff

# Food

Used images from reddit.

## Waifu Face

The dataset used was the [Danbooru2019 Portrait](https://www.gwern.net/Crops#danbooru2019-portraits) which had 302,652 images of anime (waifu) faces cropped to 512x512 from solo Danbooru2019 images. However, upon close inspection, there are some problems in the dataset due to duplication, low quality images, and multiple faces in one image. Further details can be found on [Danbooru2019 Portraits Problems](#Danbooru2019-PortraitsProblems)

## Human Face

Used FFHQ. Probably should remove images with more than one face, but the models in stylgan2ada did fine so should be fine.

### Danbooru2019 Portraits Problems

Image duplicates (Perceptual Hashing): 3804 found
![Danbooru2019 Dupes](images/danbooru-dupes.png)

Multiple faces or no faces: __ found
show examples

Low quality images (images with black borders and really small faces): __ found
show examples

Removing these images resulted in ___ total images used for the stylegan2-ada model.