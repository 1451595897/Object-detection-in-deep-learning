# Object-detection-in-deep-learning
## Overview of object detection in deep learning
For object detection, we first need to understand what datasets are commonly used for this task in deep learning.
Popular databases for object recognition and object detection are as follow.
<table>
        <tr>
            <th>Dataset Name</th>
            <th>Total Images </th>
            <th>Categories</th>
            <th>Images Per Category</th>
            <th>Objects Per Image</th>
            <th>Image Size</th>
            <th>Started Year</th>
        </tr>
        <tr>
            <th>MNIST</th>
            <th>60, 000 </th>
            <th>10 </th>
            <th>6, 000 </th>
            <th>1 </th>
            <th>28 × 28</th>
            <th>1998 </th>
        </tr>
        <tr>
            <th>Caltech101</th>
            <th>9, 145</th>
            <th>101 </th>
            <th>40 ∼ 800</th>
            <th>1 </th>
            <th>300 × 200</th>
            <th>2004</th>
        </tr>
        <tr>
            <th>Caltech256</th>
            <th>30, 607</th>
            <th>256 </th>
            <th>80+</th>
            <th>1 </th>
            <th>300 × 200</th>
            <th>2007</th>
        </tr>
        <tr>
            <th>Scenes15</th>
            <th>4, 485 </th>
            <th>15 </th>
            <th>200 ∼ 400</th>
            <th>——</th>
            <th>256 × 256</th>
            <th>2006</th>
        </tr>
        <tr>
            <th>Tiny Images</th>
            <th>79 millions+</th>
            <th>53, 464</th>
            <th>——</th>
            <th>——</th>
            <th>32 × 32</th>
            <th>2006</th>
        </tr>
        <tr>
            <th>PASCAL VOC (2007)</th>
            <th>9, 963</th>
            <th>20 </th>
            <th>96 ∼ 2008</th>
            <th>2.5 </th>
            <th>470 × 380</th>
            <th>2005</th>
        </tr>
        <tr>
            <th>PASCAL VOC (2012)</th>
            <th>11, 540</th>
            <th>20 </th>
            <th>303 ∼ 4087</th>
            <th>2.4</th>
            <th>470 × 380</th>
            <th>2005</th>
        </tr>
        <tr>
            <th>SUN</th>
            <th>131, 072</th>
            <th>908 </th>
            <th>——</th>
            <th>16.8</th>
            <th>500 × 300</th>
            <th>2010</th>
        </tr>
        <tr>
            <th>ImageNet</th>
            <th>14 millions+</th>
            <th>21, 841</th>
            <th>——</th>
            <th>1.5 </th>
            <th>500 × 400</th>
            <th>2009</th>
        </tr>
        <tr>
            <th>KITTI Vision</th>
            <th>14999</th>
            <th>5</th>
            <th>——</th>
            <th>——</th>
            <th>——</th>
            <th>2012</th>
        </tr>
        <tr>
            <th>Oxford-IIIT Pet</th>
            <th>7, 349</th>
            <th>37</th>
            <th>184 ∼ 200</th>
            <th>1 </th>
            <th>——</th>
            <th>2012</th>
        </tr>
        <tr>
            <th>MS COCO</th>
            <th>328, 000+</th>
            <th>91</th>
            <th>——</th>
            <th>7.3</th>
            <th>640 × 480</th>
            <th>2014</th>
        </tr>
        <tr>
            <th>Places</th>
            <th>10 millions+</th>
            <th>434</th>
            <th>——</th>
            <th>——</th>
            <th>256 × 256</th>
            <th>2014</th>
        </tr>
        <tr>
            <th>Open Images </th>
            <th>9 millions+</th>
            <th>6000+</th>
            <th>——</th>
            <th>——</th>
            <th>varied</th>
            <th>2017</th>
        </tr>
        <tr>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
</table>
