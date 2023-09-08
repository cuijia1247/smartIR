# SmartIR
Supervised Multi-class Image Retargeting Reconstruction Model based on Long-range Attention Map

The dataset includes 2135 images in seven different themes: ‘animal’, ‘building’, ‘cars’, ‘flower’, ‘indoor’, ‘landscape’ and ‘people’. All images are selected from existing CV datasets, such as COCO, Stanford Cars, the Oxford Buildings and so on. The image selection criteria are image contents, composition, illumination, and background, which are directly related to the challenges of retargeting techniques, and all the images are indexed based on these criteria.

## animal images


 content  | horse | sheep | bird | elephant | bear | cat | dog | giraffe | cattle |
  index   |  01   |  02   |  03  |    04    |  05  | 06  |  07 |   08    |   09   |
 background  | 单元格内容 | 单元格内容  
 composition

For each image included in the proposed SMART dataset, two designers are invited to independently retarget the image from the original size of 640*480 to the desired size of 320*480 based on their aesthetic preferences. There are no additional rules for designers to minimize the image size, but the preservation of key information and visually pleasing effects is essential. Subsequently, the results of the two designers results are evaluated by a third designer to select the better one as the ground truth for image retargeting. More than 70% of images retargeted by both designers display a high degree of consistency, indicating a stable design aesthetic. For the remaining less than 30%, the third designer is required to make decisions according to the standard of preservation of image information.

