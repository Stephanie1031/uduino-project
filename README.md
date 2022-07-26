<h1 align="center">uduino-project</h1>


>这是一个通过unity与Arduino共同开发的简易三维迷宫游戏（附带自制手柄）。

## 软件部分

游戏本体为unitychan.exe文件，是利用unity中现有的串口通信包以及素材文件生成的。

<p align='center'><img width="300" src="https://github.com/Stephanie1031/uduino-project/blob/main/game.jpg"></p>
<h5 align="center">游玩画面</h5>

硬件部分，采用Arduino可编程单片机与元器件共同组成游戏手柄（Arduino部分的代码.ino在文件夹mpu中）

<p align='center'><img width="300" src="https://github.com/Stephanie1031/uduino-project/blob/main/controller.jpg" ></p>
<h5 align="center">手柄样式</h5>

特殊的元器件主要包含一个温控电阻，一个滑动变阻器，一个触摸式开关，以及mpu6050模块（负责感知手柄各个方向上的倾斜角度）
<p align='center'><img width="300" src="https://github.com/Stephanie1031/uduino-project/blob/main/lines.jpg" ></p>
<h5 align="center">连线示意图</h5>

## 演示视频

[![Watch the video](https://github.com/Stephanie1031/uduino-project/blob/main/game.jpg)](https://www.bilibili.com/video/BV1hk4y1z7ww?spm_id_from=333.999.0.0)

虽然在后期有尝试添加一些文案剧情使游戏形式更加完整（不过因为本人做不动了最后变成了有些尴尬的模样 咕咕咕）

<u>需要注意的是，游戏本体在没有手柄的情况下无法控制角色的行为，此项目仅为软硬件结合的一次简易尝试</u>