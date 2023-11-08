# Satellite-Imagery-Feature-Detection

Image Segmentation using Segnet and U-Net on SAR images

Space technologies can give operational advantage over potential adversaries. In predominant areas like defense and science, advance space engineering requires an automatic feature labelling system to accurately classify features in overhead imagery which helps in effective satellite intelligence and surveillance from space. Using computer vision, we can also orchestrate responses to future threats and opportunities with enhanced and affordable defense and security capability.

The dataset can be retrieved from https://www.kaggle.com/competitions/dstl-satellite-imagery-feature-detection/data The dataset consists of 3- Band Images - RGB natural color images 16 Band Images - Multispectral (400 – 1040nm) and short-wave infrared (1195-2365nm) range. Grid_sizes – Xmin and Y max coordinates of each image Polygon_wkt – Classes and polygon coordinates.

![image](https://github.com/Ygurram14/Satellite-Imagery-Feature-Detection/assets/143032421/c677d0b4-8d18-4923-80bf-becbd1e6fbbf)
![image](https://github.com/Ygurram14/Satellite-Imagery-Feature-Detection/assets/143032421/0821cfb1-251a-4885-bc5d-eb05dd248c14)


The dataset is trained on U-net and Segnet and we observe the following results The proposed algorithms are trained with the prepared datasets. The learning rate of 0.0001 was applied for both the algorithms, with 15 epochs each. The outputs generated were considerable as the maximum classes were forest and manmade structures.

One of U-Net outputs:

![image](https://github.com/Ygurram14/Satellite-Imagery-Feature-Detection/assets/143032421/6431e092-afa7-4bfa-a51c-f3870df278e7)


One of Segnet outputs:

![image](https://github.com/Ygurram14/Satellite-Imagery-Feature-Detection/assets/143032421/75cc7740-a1a6-4669-ab7e-c9def567b4f3)
