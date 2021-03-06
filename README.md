# 2.5D DATMO

2.5D Grid-based Detection and Tracking of Moving Objects (DATMO)

A DATMO approach is proposed based on motion grids. The motion grids is achieved by building a short-term static model of the scene, followed by a properly-designed subtraction mechanism to compute the motion, and to rectify the localization error of the GPS-aided INS positioning system. For the generic moving object extraction from motion grids a morphology based clustering method is used. The extracted (detected) moving objects are finally tracked using KFs. The proposed method extracts an object-level representation from motion grids, in the absence of a priori assumption on the shape of objects, which makes it suitable for a wide range of objects. Watch the result in the video below.

https://youtu.be/3jZ8znHyWts

![picture2](https://user-images.githubusercontent.com/5465785/43979909-2e6cbddc-9ce4-11e8-9992-f73ce7323cfc.png)

The algorithm is described in:

A. Asvadi, P. Peixoto, and U. Nunes, “Detection and Tracking of Moving Objects Using 2.5D Motion Grids,” In IEEE 18th International Conference on Intelligent Transportation Systems (ITSC 2015), pp. 788 – 793, Las Palmas, Spain, 2015. DOI: 10.1109/ITSC.2015.133
