These page will teach you to how to use this tool.

## Requirements
See [requirements.txt](https://github.com/GLLloveQQ/tool/blob/master/requirements.txt)

## How
### Datasets
```
Your datasets should have two parts at least. One is images and other is mask.
The name of you images and mask should be a number. And the number should start at 0000. (The next is 0001)
Please put the images into the ./pypoi/images/image , and put the mask into the ./pypoi/images/mask

If you press the save button, the result will be save in ./images/imagepre
If you press the blend&asve button, the result wil be save in ./images/blended and also the result mask will be save in ./images/mask
```
### Code
```
You should change the datasets path in gui.py and you can only modify 50 images at a time


In gui.py, the load_example method will load the picture.
The image on the left is randomly selected within a given range and the index of it is named ii.
The index of right image is named example_id.

After editing 50 images, you should let the example_id += 50
```
