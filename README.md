# HP OMEN 15 DC macOS

惠普暗影精灵 4 代 (GTX1060 + 144Hz 版) 安装 macOS High Sierra 的配置文件。

> 说明：此 EFI 配置文件是在作者舍友的电脑上测试可用，作者本人并没有惠普暗影精灵 4 的机器，所以此 EFI 可能不会长期维护。此版本的暗影精灵 4 由于使用了 G-Sync 技术，所以没有核心显卡，只有 GTX1060 独立显卡，因此只能完美安装 macOS High Sierra (10.13) 版本。

## 下载

请前往 [Release](https://github.com/kirainmoe/hp-omen15-dc-macos/releases) 页面，下载 EFI 和网卡驱动文件。

## 正常工作的功能

- CPU 变频、睿频
- 键盘、触摸板基础功能
- 声卡（外放、麦克风、外接耳机孔）
- 有线网卡
- USB 和 Type-C
- 电池信息和原生电源管理
- 温度传感器
- 睡眠
- nvidia GTX1060 独立显卡（需自行安装 webdriver）
  - 受限于 nvidia 显卡不受 PNLF 控制的原因，屏幕亮度将无法调节。
- HDMI 和 DP 外接
- 蓝牙
  - 请自行前往 [Release](https://github.com/kirainmoe/hp-omen15-dc-macos/releases) 页面下载对应无线网卡的蓝牙驱动

## 部分工作的功能

- 触摸板手势不完全
  - 受限于暗影精灵 4 使用的触摸板协议为 PS/2，部分多指手势无法正常工作
- Intel 无线网卡
  - 请自行前往 [Release](https://github.com/kirainmoe/hp-omen15-dc-macos/releases) 页面下载对应无线网卡的驱动
- 部分键盘快捷键


# 截图

![image.png](https://i.loli.net/2019/10/01/cowADVZuFE8QsCf.png)
