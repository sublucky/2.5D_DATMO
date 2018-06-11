# 2.5D_DATMO

2.5D Grid-based Detection and Tracking of Moving Objects (DATMO)

A DATMO approach is proposed based on motion grids. The motion grids is achieved by building a short-term static model of the scene, followed by a properly-designed subtraction mechanism to compute the motion, and to rectify the localization error of the GPS-aided INS positioning system. For the generic moving object extraction from motion grids a morphology based clustering method is used. The extracted (detected) moving objects are finally tracked using KFs. The proposed method extracts an object-level representation from motion grids, in the absence of a priori assumption on the shape of objects, which makes it suitable for a wide range of objects.
