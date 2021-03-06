Face-study
==========

* ~~Study of neutral face dataset from: [http://agingmind.utdallas.edu/facedb/view/neutral-faces](http://agingmind.utdallas.edu/facedb/view/neutral-faces)~~ **[URL DEAD]**

* ~~Dataset file: [Color Neutral jpg (11MB)](http://vitallongevity.utdallas.edu/faces/Color_Neutral_jpg.zip)~~ **[URL DEAD]**

* Processed dataset: [Color Neutral Processed (23MB)](https://www.dropbox.com/s/80t4q349groiqfc/processed.zip?dl=0)

* Accuracy: 82%

* Face Area : Mouth Area (Ratio) (bounding rectangle method)
Average: 22.39
![Alt text](http://i.imgur.com/oTD4kjw.png  "face to mouth ratio")

* **Face Area : Mouth Area** (Ratio) (lip contour method)
Average: 54.30
![Alt text](http://i.imgur.com/osULKDp.png "face to mouth ratio")

Sample dataset example
----------------------
* Sample dataset

![Alt text](http://i.imgur.com/C22m8hZ.jpg "sample")

* Detect face and mouth using Haar Feature-based Cascade Classifier
  * Detect face

  ![Alt text](http://i.imgur.com/TOHXM9y.png "face detect")

  * Extract face and detect mouth

  ![Alt text](http://i.imgur.com/Q0HXBh8.png "mouth detect")

  * Correct detection

  ![Alt text](http://i.imgur.com/eqUYhLk.png "correct mouth detect")

* Extracted mouth region

![Alt text](http://i.imgur.com/1py7SiQ.png "extracted mouth")

* Thresholding to extract lips (Otsu's Binarization Method)

![Alt text](http://i.imgur.com/hmSLt7o.png "thresholding")

* Shi-Tomasi Corner Detection (In progress)

![Alt text](http://i.imgur.com/JMyJ9nt.png "corner detection")

* Complete processed image (contours + Shi-Tomasi corner detection)

![Alt text](http://i.imgur.com/GUU08p3.png "processed image")
