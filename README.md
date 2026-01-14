# Switch 版 Chiaki 增强分支  
**在 [hikigayairoha/chiaki-switch](https://github.com/hikigayairoha/chiaki-switch) 基础上二次开发，感谢原作者与社区贡献！**

---
一键下载：[chiaki.nro](https://github.com/hymoe/chiaki-switch/releases/download/v2.2.0/chiaki.nro)

源码下载：
```bash
git clone -b feature_bitrate_amplification https://github.com/hymoe/chiaki-switch.git
```
---
## 🚀 功能亮点
- **码率档位增加**
  720P支持13/20/25/30Mbps档位，1080P支持15/20/30/40/50Mbps档位。
- **减号键 → 触控板按下**  
  一键搞定 PS5 触控板功能，告别繁琐组合键。  
- **「＋」＋「－」同时按住 → PS 键**  
  快速呼出系统菜单，操作更顺手。   
- **第三方手柄震动 & 陀螺仪**  
  已验证「魔派双子星二代」完美支持；陀螺仪在 **GT7** 等原生支持场景生效。  

---
## 📊 当前支持分辨率与预设码率
| 分辨率预设 | 默认码率 |
|-----------|----------|
| 360p | 2 Mbps |
| 540p | 6 Mbps |
| 720p | 13 Mbps |
| 720p20M | 20 Mbps |
| 720p25M | 25 Mbps |
| 720p30M | 30 Mbps |
| 1080p | 15 Mbps |
| 1080p20M | 20 Mbps |
| 1080p30M | 30 Mbps |
| 1080p40M | 40 Mbps |
| 1080p50M | 50 Mbps |

---
## 🌿 feature_bitrate_amplification 分支新增功能
- 新增多个高码率分辨率预设（含 720p/1080p 多档位）。
- 前端界面可直接选择预设，无需手动输入码率。
- 配置文件 `video_resolution` 支持新档位字符串。

---

## 📦 系统需求
| 项目 | 版本 |
|------|------|
| 固件 | **20.5.0**（实测） |

---

## 🛠️ 快速开始
1. 下载最新 release 的 `.nro` 文件；
2. 电脑有线连接 ns ，打开相册内的 DBI，选择：run mtp responder，即可同电脑传输文件；
3. 放入 switch 盘下的：SD Card/switch/    目录下；
4. 按 ns 主菜单键返回；
5. 点击相簿，找到并打开 Chiaki，享受增强体验！

---

## 🎮 按键对照
| Switch 按键 | 映射功能 |
|-------------|-----------|
| **－** | 触控板按下 |
| **＋ & － 同时按住** | PS 键 |

---

## 📝 编译提示
如需自行编译，参考下方视频教程，仅需替换源码即可。  
代码修改学习参考：  
[【B 站】Switch 版 Chiaki 编译流程（含 1080P/720P 码率调整）](https://www.bilibili.com/video/BV12f421S7v3)

---

## ❤️ 致谢
- **hikigayairoha** 提供触控板和PS键映射
- **kkwong** 提供震动与陀螺仪基础实现  
- **B 站 UP 主：阿西西的日常** 分享详细编译流程
