# Sit to Stand

&emsp;<font size=6><table><tr><td bgcolor=#ffff99> 
Leading Leg 2024/01/08&ensp; </td></tr></table></font>
<br>
<h3>判讀程式碼目標：</h3>
<h4>透過 MediaPipe 和 OpenCV 庫來偵測並計算髖部、膝蓋彎曲角度的程式，分析每個影片左、右兩側原地「坐立->起立->坐立」幾次</h4> 
<br>
Mediapipe 的骨架模型：

![](https://imgur.com/C98MGPb.png)<br>
<br>
Sit to Stand 髖部的關鍵點：右側：12, 24, 26/ 左側：11, 23, 25
Sit to Stand 膝蓋的關鍵點：右側：24, 26, 28/ 左側：23, 25, 27
<br>
<br>
<br>
<h3>4.mov 影片讀取結果：</h3>
體適能標準影片來源：<br>
(1) https://www.youtube.com/watch?v=Hy436yxQJMc <br>
(2) https://www.youtube.com/watch?v=Je8jzTzKUcA<br>
<br>
運行程式碼：<br>
(1) https://youtube.com/shorts/uQqp36EN7AU?feature=share<br>
(2) https://youtu.be/PkC88zNpD5U<br>
