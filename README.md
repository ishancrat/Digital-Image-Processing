# Digital-Image-Processing
<details open>
  <summary> File1</summary>
  <br>
  File1 contains basic codes pertaining to image processing. It begins with the reading and displaying of images. The sample images is first read and then displayed.
  <br>
  <br>
  <p align="center">
  <img width="300" height="300" src="/images/Lenna.png">
</p>
  <hr>
  The next goal was to convert the given image to grayscale. Three methods were used-
  <ul>
    <li> Inbuilt Command (cvtColor)
     <li> Averaging pixel values across all channels
       <li> Using standard transform formula
  </ul>
  
  Results of each of the above are displayed below, in the same order.
  <br>
  <br>
  <img width="250" height="250" src="/images/grayinbuilt.png">
  <img width="250" height="250" src="/images/grayavg.png">
  <img width="250" height="250" src="/images/graytransform.png">
  
  <hr>
  Next up, pixel intensities from each of the channels were picked up, and three grayscales were created, each having the intensities of a particular channel from the original image
  <br>
  <br>
  <img width="900" height="300" src="/images/singlechannel.png">
  <br>
  <br>
  Further, colored channels were created. Only one of the channels was allowed to maintain its values while the pixel values in the remaining channels were set to zero.
  <br>
  <img width="1040" height="260" src="/images/colorlayers.png">
  <hr>
  <h2>Histogram Equalization</h2>
  Histogram Equalization helps to improve the contrast of images by distributing the pixel intensities in a wider sense.
  <br>
  Initially, an 8 bit image was constructed and histogram equalization was applied to it.
  <br>
  <br>
  <p align="center">
  <img width="300" height="300" src="/images/8bitss.png">
    <img width="300" height="300" src="/images/8bitheqss.png">
  </p>
  Then the logic was extended and applied to a larger image
  <br>
  <br>
  <p align="center">
    <!-- 1024 by 683-->
  <img width="400" height="278" src="/images/hawk.jpg">
    <img width="400" height="278" src="/images/hawkrecon.png">
  </p>
</details>
