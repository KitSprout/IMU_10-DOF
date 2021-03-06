﻿[IMU_10-DOF](https://github.com/OpenPCB/IMU_10-DOF)
========
* Author  : [Hom](https://github.com/Hom19910422)
* Version : v1.1
* Update  : 2014/01/25

Description
========
IMU-10DOF 是一個慣性測量 ( [IMU](http://en.wikipedia.org/wiki/Inertial_measurement_unit), Inertial Measurement Unit ) 的模組，透過 [I2C](http://en.wikipedia.org/wiki/I%C2%B2C) 傳輸。  

License
========
* 硬體(Hardware)採用 [CC BY-SA 3.0 TW](http://creativecommons.org/licenses/by-sa/3.0/tw/deed.zh_TW) 方式授權 
  
　　<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/tw/"><img alt="創用 CC 授權條款" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/tw/80x15.png" /></a>  
　　<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title"> IMU_10-DOF </span>由<a xmlns:cc="http://creativecommons.org/ns#" href="https://plus.google.com/u/0/112822505513154783828/posts" property="cc:attributionName" rel="cc:attributionURL"> Hom </a>製作，以<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/tw/deed.zh_TW"> 創用CC 姓名標示-相同方式分享 3.0 台灣 授權條款 </a>釋出。  

Hardware
========
* 使用 [MPU-9150](http://www.invensense.com/mems/gyro/mpu9150.html) + [MS5611](http://www.meas-spec.com/product/pressure/MS5611-01BA03.aspx) 
* 相容 [MPU-6050](http://www.invensense.com/mems/gyro/mpu6050.html) 
* 設計軟體 [Altium Designer 13](http://www.altium.com/en/products/altium-designer) ( [PcbLib](https://github.com/CYACAcademic/AltiumDesigner_PcbLibrary) use AD PcbLib v0.1 ) 
* PCB 尺寸 : 13.46 * 11.68mm ( 半孔 : 12.45 * 11.68mm ) 

IMU_10-DOF v2.0 預計修改：  
>1. Sensor 改為 SPI 操作的 MPU-9250，來增加讀取速度。  
>2. MS5611 也將改為 SPI 讀取，與 MPU-9250 共用 SPI。  
>3. 體積將小幅度縮小，同時兼容 SPI 操作的 MPU-6500。  

Related Documents
========
* [Google Drive](https://drive.google.com/folderview?id=0BzL2wwAot6oPRU84cjJ2eDBCZUE&usp=sharing)

View
========
<img src="https://lh3.googleusercontent.com/-OKKZuUMA59g/UlKRErDyH5I/AAAAAAAAEEc/McHutxBqPTY/s1200/DSC_1390.jpg" />
<img src="https://lh4.googleusercontent.com/-UsRZ7nOD-RY/UlQsbq_NL9I/AAAAAAAAEMY/FyzqAAmqTKI/s1200/DSC_1499.jpg" />
<img src="https://lh3.googleusercontent.com/-tOlgK3vnMeI/UlQsblHUgpI/AAAAAAAAEMM/c8lRlVyWHnI/s1200/DSC_1455.jpg" />
<img src="https://lh3.googleusercontent.com/-tOlgK3vnMeI/UlQsblHUgpI/AAAAAAAAEMM/c8lRlVyWHnI/s1200/DSC_1455.jpg" />
<img src="https://lh4.googleusercontent.com/-rgPVzlSO6vE/UlQscjotAgI/AAAAAAAAEMc/XRlxowqB47Y/s1200/DSC_1502.jpg" />
<img src="https://lh5.googleusercontent.com/-KrWa5cEfOwU/UlQsbutCumI/AAAAAAAAEMQ/qg0-rCaE-34/s1200/DSC_1464.jpg" />
<br />
更多圖片 [Google+ albums](https://plus.google.com/u/0/photos/+文宏王Hom/albums/5920608056539236641)

Schematic
========
<img src="https://lh5.googleusercontent.com/-RJA1JljuKEo/UmWbONErBOI/AAAAAAAAEh0/BDLJh1AI2H4/s1200/IMU_10DOF_Sch.png"  />
