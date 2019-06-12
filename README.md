# kaggle_fashion
这是kaggle中iMaterialist (Fashion) 2019 at FGVC6比赛的相关code.
比赛网址：https://www.kaggle.com/c/imaterialist-fashion-2019-FGVC6

相关数据网址：https://www.kaggle.com/c/imaterialist-fashion-2019-FGVC6/data


本项目中使用的是mrcnn网络，参考的https://www.github.com/matterport/Mask_RCNN.git  （mrcnn文件夹下的文件均是使用这里面的）

MRCNN文件夹下的mask_rcnn_coco.h5文件是空的，gitup有文件大小要求，上传不了，终端获取方法请参考以下方式：

!wget --quiet https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5

!ls -lh mask_rcnn_coco.h5
