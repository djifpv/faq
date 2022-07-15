# [Dji FPV](https://www.dji.com/cn/dji-fpv)

### [下载](https://www.dji.com/cn/downloads/products/dji-fpv)

* [说明书](assets/DJI_FPV_User_Manual_CHS.pdf)
* [遥控器](assets/DJI_FPV_Remote_Controller_2_User_Guide.pdf)
* [V2眼镜](assets/DJI_FPV_Goggles_V2_User_Guide.pdf)

### 使用前
* 改遥控器油门不回中, 需要调节遥控器油门. 调整至不晃动不回中低阻尼. **必须设置该项否则禁止开启手动模式**
  ```扭紧F1螺丝可使得油门控制摇杆不会自动回中，并且阻力变大；扭紧F2螺丝可使得油门控制摇杆弹簧弹力减小。```
  [关于DJI FPV遥控器左右握把处F1&F2螺丝松紧对应功能的咨询](https://bbs.dji.com/thread-264250-1-1.html)
* 手动模式: 在眼镜```设置->操控->遥控器设置->自定义按键```里把自定义模式设置成手动模式. 切换至自定义模式则可进入手动模式.  
  解除姿态限制: 在眼镜```设置->操控->遥控器设置->操控手感```里解除姿态限制, 解除俯仰横滚的角度限制.
* 操控手感参数设置.(仅供参考, 看自己手感设置)  
  ```
  30/600/0.20
  30/600/0.20
  30/420/0.20
  ```
  来源: [你们要的DJI FPV参数来了。话不多说直接上干货，视频最后实在是。。。。](https://www.bilibili.com/video/BV1HL4y1F7hd?spm_id_from=333.999.0.0&vd_source=38080a466f04634f51458e6482b9b663)


### 初步操作
**建议飞到高处再随意使用手动模式**
* 起桨
  普通/运动模式, 双摇杆内八起桨(左摇杆右后, 右摇杆左后).
  手动模式, 按两下Start(右前下键)起桨.
* 刹车
  **一定记住刹车键在左前, 和自行车的刹车一样**, 快失去控制了就点一下, 长按刹车能返航.
* 起飞
  * 普通/运动模式, 升油门, **最推荐的起飞方式是N挡目视飞到高空, 然后再戴上FPV眼镜**
  * 手动模式, 升油门会往前上方向飞行, 需要通过俯仰来调整悬停位置. **建议起飞时自动模式, 手动模式在50米以上的高空开启, 若失去控制点刹车** 不会穿越机的ACRO模式飞行的人禁止开启手动模式.
* 降落
  按返航按键, 或者飞到返航点, 油门拉最低. **建议N挡目视精准降落, 用M挡降落容易损耗飞机和电池的脚垫**

### 大疆天空端视频串流
* [手机端APP](./assets/DigiView_1.0.0_Beta.apk). 需要用OTG线连接飞机和手机
* 使用树莓派进行串流 [大疆FPV眼镜视频输出新方案，树莓派HDMI直出！支持iOS设备监看！](https://www.bilibili.com/video/BV1fU4y1P7iK) 支持树莓派3B

### 注意事项
* 丢控制时保持遥控油门回中, 或者直接关掉遥控等图传恢复. 这不是穿越机, 若遥控恢复连接有可能直接炸机.
* 手动模式下大油门只能持续几秒, 若长时间大油门, 不像航模的高C数电池, 飞机的低C数电池会因为放电进入过热保护, 半小时内无法充电.