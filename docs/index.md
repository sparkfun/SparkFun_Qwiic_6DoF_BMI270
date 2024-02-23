<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<div class="grid.cards.desc" markdown>

<table class="pdf" style="border-style:none;" markdown="1">
<tbody markdown="1">
<tr markdown="1">
<td align="center" width="35%" markdown="block">
[![SparkFun 6DoF IMU Breakout - BMI270 (Qwiic)](https://cdn.sparkfun.com/assets/parts/2/2/4/2/9/22397_1_1.jpg){ width=90% }](https://www.sparkfun.com/products/22397)


The [SparkFun 6DoF IMU Breakout - BMI270 (Qwiic)](https://www.sparkfun.com/products/22397) is a Qwiic enabled board based on the ultra-low power BMI270 from Bosch. This chip is a highly integrated, low power IMU designed for wearable, smart clothing and AR/VR applications. Not only does the BMI270 comprise a fast and sensitive accelerometer and gyro pair, but it also contains a number of intelligent, on-chip motion-triggered interrupt features.  

<center>
[Purchase from SparkFun :fontawesome-solid-cart-plus:](https://www.sparkfun.com/products/22397){ .md-button .md-button--primary }
</center>
</td>
<td align="center" width="35%" markdown="block">
[![SparkFun Micro 6DoF IMU Breakout - BMI270 (Qwiic)](https://cdn.sparkfun.com/assets/parts/2/2/4/3/0/22398_1_1.jpg){ width=90% }](https://www.sparkfun.com/products/22398)

The [SparkFun Micro 6DoF IMU Breakout - BMI270 (Qwiic)](https://www.sparkfun.com/products/22398) is the 1x1's mini-me, containing most of it's elder sibling's functionality in a tiny little package. 

<center>
[Purchase from SparkFun :fontawesome-solid-cart-plus:](https://www.sparkfun.com/products/22398){ .md-button .md-button--primary }
</center>
</td>
</tr>
</tbody>
</table>
</div class>


### Required Materials

To follow along with this tutorial, you will need the following materials. You may not need everything though depending on what you have. Add it to your cart, read through the guide, and adjust the cart as necessary.

<table style="border-style:none">
    <tr>
        <td>
            <a href="https://www.sparkfun.com/products/22397">
                <center><img src="https://cdn.sparkfun.com/assets/parts/2/2/4/2/9/22397_1_1.jpg" style="width:140px; height:140px; object-fit:contain;" alt="SparkFun 6DoF IMU Breakout - BMI270 (Qwiic)"></center>
                <h3 class="title">SparkFun 6DoF IMU Breakout - BMI270 (Qwiic)</h3>
            </a>
            SEN-22397
        </td>
        <td>
            <a href="https://www.sparkfun.com/products/22398">
                <center><img src="https://cdn.sparkfun.com/assets/parts/2/2/4/3/0/22398_1_1.jpg" style="width:140px; height:140px; object-fit:contain;" alt="SparkFun Micro 6DoF IMU Breakout - BMI270 (Qwiic)"></center>
                <h3 class="title">SparkFun Micro 6DoF IMU Breakout - BMI270 (Qwiic)</h3>
            </a>
            SEN-22398
        </td>
        <td>
            <a href=" https://www.sparkfun.com/products/17259">
                <center><img src="https://cdn.sparkfun.com/r/455-455/assets/parts/1/6/2/4/6/17259-Flexible_Qwiic_Cable_-_100mm-01.jpg" style="width:140px; height:140px; object-fit:contain;" alt="USB micro-B Cable - 6 Foot" height="140"></center>
                <h3 class="title">Flexible Qwiic Cable - 100mm</h3>
            </a>
            PRT-17259
        </td>
        <td>
            <a href="https://www.sparkfun.com/products/10215">
                <center><img src="https://cdn.sparkfun.com/r/455-455/assets/parts/4/5/5/8/10215-01.jpg" style="width:140px; height:140px; object-fit:contain;" alt="USB micro-B Cable - 6 Foot" >
                </center>
                <h3 class="title">USB micro-B Cable - 6 Foot</h3>
            </a>
            CAB-10215
        </td>
        <td>
            <a href="https://www.sparkfun.com/products/15663">
                <center><img src="https://cdn.sparkfun.com/assets/parts/1/4/2/4/1/15663-SparkFun_Thing_Plus_-_ESP32_WROOM-01.jpg" style="width:140px; height:140px; object-fit:contain;" alt="SparkFun ESP32 Thing Plus" >
                </center>
                <h3 class="title">SparkFun ESP32 Thing Plus</h3>
            </a>
            DEV-15663
        </td>
    </tr>
</table>

### Suggested Reading

If you aren’t familiar with the following concepts, we recommend checking out these tutorials before continuing.

<div class="grid cards hide col-4" markdown align="center">

-   <a href="https://learn.sparkfun.com/tutorials/82">
    <figure markdown>
    ![I2C](https://cdn.sparkfun.com/assets/learn_tutorials/8/2/I2C-Block-Diagram.jpg)
    </figure>
    </a>
    <a href="https://learn.sparkfun.com/tutorials/82">**I2C**
    </a>

-   <a href="https://learn.sparkfun.com/tutorials/terminal-basics">
    <figure markdown>
    ![SPI](https://cdn.sparkfun.com/assets/learn_tutorials/1/1/2/terminalThumb.jpg)
    </figure>
    </a>
    <a href="https://learn.sparkfun.com/tutorials/terminal-basics">**Serial Terminal Basics**
    </a>
</div>

<center>
<div align="center">
    <div style="top:5px;left:5px;background-color:Gray;position:relative">
        <div style="top:-5px;left:-5px;background-color:#ffffff;position:relative;border:1px solid black;">
            <a href="https://www.sparkfun.com/qwiic"><img src="https://cdn.sparkfun.com/assets/custom_pages/2/7/2/qwiic-logo.png" alt="Qwiic Connect System" title="Qwiic Connect System"></a>
        </div>
    </div>
</div>
</center>

The SparkFun 6DoF IMU Breakout - BMI270 (Qwiic) Sensor takes advantage of the [Qwiic connect system](https://www.sparkfun.com/qwiic). We recommend familiarizing yourself with the **Logic Levels** and **I<sup>2</sup>C** tutorials.  Click on the banner above to learn more about [Qwiic products](https://www.sparkfun.com/qwiic).

<center>
    <iframe width="600" height="327" src="https://www.youtube.com/embed/x0RDEHqFIF8" title="SparkFun's Qwiic Connect System" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>
