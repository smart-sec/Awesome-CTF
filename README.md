# Awesome-CTF

**❗【免责声明】本项目所涉及的技术、思路和工具仅供学习，任何人不得将其用于非法用途和盈利，不得将其用于非授权渗透测试，否则后果自行承担，与本项目无关。 使用本项目前请先阅读 [法律法规](https://github.com/Threekiii/Awesome-Laws)。**

_Disclaimer: The technologies, concepts, and tools provided in this Git repository are intended for educational and research purposes only. Any use for illegal activities, unauthorized penetration testing, or commercial purposes is strictly prohibited. Please read the [Awesome-Laws](https://github.com/Threekiii/Awesome-Laws) before using this repository._

📖 一个 CTF 知识库。_A knowledge base for CTF (Capture The Flag) challenges._

## Roadmap

## 目录 _Contents_

- [First of All](#first-of-all)
- [开源导航 _Open-Source Navigation_](#%E5%BC%80%E6%BA%90%E5%AF%BC%E8%88%AA-open-source-navigation)
- [Crypto](#crypto)
	- [综合工具 _Nice Tools_](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
	- [加解密 _Encryption / Decryption_](#%E5%8A%A0%E8%A7%A3%E5%AF%86-encryption--decryption)
	- [编解码 _Encoding / Decoding_](#%E7%BC%96%E8%A7%A3%E7%A0%81-encoding--decoding)
	- [数学计算 _Mathematical Calculation_](#%E6%95%B0%E5%AD%A6%E8%AE%A1%E7%AE%97-mathematical-calculation)
- [Misc](#misc)
	- [综合工具 _Nice Tools_](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
	- [图片分析 _Images Analysis_](#%E5%9B%BE%E7%89%87%E5%88%86%E6%9E%90-images-analysis)
		- [图片隐写 _Steganography_](#%E5%9B%BE%E7%89%87%E9%9A%90%E5%86%99-steganography)
		- [图片元数据 _EXIF_](#%E5%9B%BE%E7%89%87%E5%85%83%E6%95%B0%E6%8D%AE-exif)
		- [图片杂项 _Misc_](#%E5%9B%BE%E7%89%87%E6%9D%82%E9%A1%B9-misc)
		- [二维码 _QR Code_](#%E4%BA%8C%E7%BB%B4%E7%A0%81-qr-code)
	- [音视频分析 _Multimedia Analysis_](#%E9%9F%B3%E8%A7%86%E9%A2%91%E5%88%86%E6%9E%90-multimedia-analysis)
	- [流量分析 _Traffic_](#%E6%B5%81%E9%87%8F%E5%88%86%E6%9E%90-traffic)
	- [取证分析 _Forensics Analysis_](#%E5%8F%96%E8%AF%81%E5%88%86%E6%9E%90-forensics-analysis)
		- [磁盘取证 _Disk Forensics_](#%E7%A3%81%E7%9B%98%E5%8F%96%E8%AF%81-disk-forensics)
		- [内存取证 _Memory Forensics_](#%E5%86%85%E5%AD%98%E5%8F%96%E8%AF%81-memory-forensics)
		- [日志取证 _Log Forensics_](#%E6%97%A5%E5%BF%97%E5%8F%96%E8%AF%81-log-forensics)
		- [浏览器取证 _Browser Forensics_](#%E6%B5%8F%E8%A7%88%E5%99%A8%E5%8F%96%E8%AF%81-browser-forensics)
	- [密码破解 _Brute Force_](#%E5%AF%86%E7%A0%81%E7%A0%B4%E8%A7%A3-brute-force)
	- [数据处理 _xx Editor_](#%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86-xx-editor)
	- [其他 _Others_](#%E5%85%B6%E4%BB%96-others)
- [Web](#web)
- [Pwn](#pwn)
	- [仿真环境 _Emulation_](#%E4%BB%BF%E7%9C%9F%E7%8E%AF%E5%A2%83-emulation)
	- [二进制修改 _Binary Patching_](#%E4%BA%8C%E8%BF%9B%E5%88%B6%E4%BF%AE%E6%94%B9-binary-patching)
	- [GDB 增强 _GDB Enhancement_](#gdb-%E5%A2%9E%E5%BC%BA-gdb-enhancement)
	- [IDA 增强 _IDA Enhancement_](#ida-%E5%A2%9E%E5%BC%BA-ida-enhancement)
	- [ROP](#rop)
	- [逆向 _Reverse_](#%E9%80%86%E5%90%91-reverse)
		- [综合工具 _Nice Tools_](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
		- [静态分析 _Static Analysis_](#%E9%9D%99%E6%80%81%E5%88%86%E6%9E%90-static-analysis)
		- [动态调试 _Dynamic Analysis_](#%E5%8A%A8%E6%80%81%E8%B0%83%E8%AF%95-dynamic-analysis)
		- [Java](#java)
		- [Mobile](#mobile)
		- [Python](#python)
		- [Rust/Go/.NET](#rustgonet)

## First of All

CTF 常见竞赛模式:

- 理论知识: 通常为选择题。
- 解题模式: 通常分为 Crypto、Misc、Web、Pwn、Reverse 五个类别。
- AWD 模式: Attack with Defense，通常仅包含 Web 及 Pwn 两个类别。
- AWD Plus 模式: Attack with Defence Plus，通常为解题（攻击）+ 加固（防御）。
- RHG 模式: Robot Hacking Game，通常为使用自动化攻击程序实现对漏洞的全自动挖掘及漏洞。

18 年以后的其他新竞赛模式:

- Real World CTF
- King of The Hill

## 开源导航 _Open-Source Navigation_

- CTF Wiki: https://ctf-wiki.org/
- CTF Hub: https://www.ctfhub.com/
- CTF Time: https://ctftime.org/
- AWD-Guide: https://github.com/AabyssZG/AWD-Guide
- 攻防世界: https://adworld.xctf.org.cn/
- Hacker 101: https://www.hacker101.com/
- Cryptopals: https://cryptopals.com/
- Awesome-ctf: https://github.com/apsdehal/awesome-ctf
- CTF Tools: https://github.com/zardus/ctf-tools
- Forensics-Wiki: https://www.forensics-wiki.com/
- 在线 shellcode 集合: https://shell-storm.org/shellcode/index.html
- CTF writeups from P4 Team: https://github.com/p4-team/ctf
- CTF-Archives: https://github.com/CTF-Archives
- 近期赛事：
	- https://github.com/ProbiusOfficial/Hello-CTFtime
	- https://hello-ctf.com/Event/
	- https://ctf.bugku.com/game/index.html
	- https://www.ichunqiu.com/competition/all
	- https://adworld.xctf.org.cn/contest/list

## Crypto

*Tools used for solving Crypto challenges.*

### 综合工具 _Nice Tools_

- Online：
	- http://www.ip33.com/
	- https://evilcos.me/lab/xssee/
	- http://www.metools.info/
	- https://www.107000.com/
	- https://github.com/wangyiwy/oktools
	- http://www.hiencode.com/
	- http://www.atoolbox.net/
	- https://www.sojson.com/
	- https://the-x.cn/
- Offline：
	- Ciphey: https://github.com/Ciphey/Ciphey python
	- CyberChef: https://github.com/gchq/CyberChef web
	- ctfcode: http://1o1o.xyz/bo_ctfcode.html
	- CaptfEncoder: https://github.com/guyoung/CaptfEncoder

### 加解密 _Encryption / Decryption_

- 摩斯电码: http://moersima.00cha.net/
- 摩斯电码: http://www.zhongguosou.com/zonghe/moersicodeconverter.aspx
- 栅栏密码: https://www.qqxiuzi.cn/bianma/zhalanmima.php
- 猪圈密码: http://www.hiencode.com/pigpen.html
- 零宽字符: http://330k.github.io/misc_tools/unicode_steganography.html
- quipqiup: https://www.quipqiup.com/ 在线古典密码词频爆破
- rabbit: https://asecuritysite.com/encryption/rabbit2
- MD5:
	- https://www.cmd5.org/
	- https://www.somd5.com/
	- https://www.onlinehashcrack.com/
	- https://crackstation.net/
	- https://crack.sh/
	- https://passwordrecovery.io/
	- https://md5decrypt.net/en/Sha256/
	- https://hashes.com/en/decrypt/hash
- RSA:
	- https://www.ssleye.com/ssltool/
	- https://www.lddgo.net/en/encrypt/rsa work with .pem
- 加密算法模板: https://github.com/a568972484/The_encryption_template_Python

### 编解码 _Encoding / Decoding_

- Unicode: https://www.compart.com/en/unicode/
- GB2312: http://code.mcdvisa.com/
- UUencode: http://web.chacuo.net/charsetuuencode
- XXencode: http://web.chacuo.net/charsetxxencode
- Escape/Unescape: https://tool.chinaz.com/tools/escape.aspx
- HTML 实体编码: https://zh.rakko.tools/tools/21/
- Base64 填充位隐写读取: https://github.com/cjcslhp/wheels/tree/master/b64stego

### 数学计算 _Mathematical Calculation_

- yafu: https://github.com/bbuhrow/yafu for RSA
- cado-nfs: https://gitlab.inria.fr/cado-nfs/cado-nfs 整数分解（Number Field Sieve）
- z3: https://github.com/Z3Prover/z3 求解器
- or-tools: https://github.com/google/or-tools maybe faster than z3
- factordb: http://factordb.com/ 在线大数分解数据库
- 在线求解线性方程组: http://www.yunsuan.info/matrixcomputations/solvelinearsystems.html
- 数独求解器: https://shudu.gwalker.cn/
- flatter: https://github.com/keeganryan/ 格基规约

## Misc

*Tools used for solving Misc challenges.*

### 综合工具 _Nice Tools_

- PuzzleSolver: Misc 工具 https://github.com/Byxs20/PuzzleSolver

### 图片分析 _Images Analysis_

#### 图片隐写 _Steganography_

- Stegsolve: 图片隐写查看器 http://www.caesum.com/handbook/stego.ht
- Stegonline: Stegsolve 在线版 https://stegonline.georgeom.net/upload
- F5-steganography: 隐写工具 jpg https://github.com/matthewgao/F5-steganography
- OutGuess: 隐写工具 jpg https://github.com/crorvick/outguess
- Silenteye: 隐写工具 jpg https://achorein.github.io/silenteye/
- zsteg: 检测 png 和 bmp 图片隐写数据 https://github.com/zed-0xff/zsteg
- PNGDebugger: 读取 png 文件头，检查 CRC https://github.com/rvong/png-debugger#pngdebugger
- cloacked-pixel: LSB 隐写工具 png https://github.com/livz/cloacked-pixel
- LSB-Steganography: LSB 隐写工具 png https://github.com/RobinDavid/LSB-Steganography

#### 图片元数据 _EXIF_

- 图虫在线 EXIF 查看器: https://exif.tuchong.com/
- EXIF 查看器: exiftool https://exiftool.org/
- Magicexif 元数据编辑器: https://www.magicexif.com/
- TweakPNG: png 图像编辑器，修改元数据 https://entropymine.com/jason/tweakpng/

#### 图片杂项 _Misc_

- Ezgif: 在线分帧 https://ezgif.com/split
- 盲水印提取: https://github.com/chishaxie/BlindWaterMark
- OCR 在线识别: https://web.baimiaoapp.com/
- 解决拼图问题: montage+gaps https://github.com/nemanja-m/gaps

#### 二维码 _QR Code_

- 在线绘制二维码/汉信码: https://www.pixilart.com/draw?ref=home-page
- 在线绘制二维码: https://merricx.github.io/qrazybox/
- 在线扫描一维码: https://online-barcode-reader.inliteresearch.com/

### 音视频分析 _Multimedia Analysis_

- Audacity: 音频隐写 https://www.audacityteam.org/
- Mp3Stego: Mp3 音频隐写 https://www.petitcolas.net/steganography/mp3stego/
- RX-SSTV: 145.800Mhz 频率信号解码 音频→图片 https://www.qsl.net/on6mu/rxsstv.htm

### 流量分析 _Traffic_

- Pcap 流量包在线修复: http://f00l.de/hacking/pcapfix.php
- knm: https://github.com/FzWjScJ/knm for keyboard and mouse
- UsbKeyboardDataHacker: https://github.com/WangYihang/UsbKeyboardDataHacker for keyboard
- USB-Mouse-Pcap-Visualizer: https://github.com/WangYihang/USB-Mouse-Pcap-Visualizer for mouse
- PCredz: https://github.com/lgandx/PCredz extract information from pcap
- CS_Decrypt: https://github.com/5ime/CS_Decrypt for CobaltStrike
- godzilla_decryptor: https://github.com/Threekiii/Awesome-Redteam/blob/master/scripts/Godzilla_Decryptor/godzilla_decryptor.py for Godzilla
- BlueTeamTools: https://github.com/abc123info/BlueTeamTools for Behinder 1.x-3.x and Godzilla1.x-4.x

### 取证分析 _Forensics Analysis_

_Tools used for solving Forensics challenges_.

#### 磁盘取证 _Disk Forensics_

- DiskGenius: https://www.diskgenius.cn/
- Sleuth Kit: https://github.com/sleuthkit/sleuthkit
- Autopsy: https://www.autopsy.com/
- AccessData FTK Imager: https://www.exterro.com/digital-forensics-software/ftk-imager for `ad1`
- ElcomSoft Distributed Password Recovery: https://www.elcomsoft.com/edpr.html for BitLocker
- Elcomsoft Forensic Disk Decryptor: https://www.elcomsoft.com/efdd.html

#### 内存取证 _Memory Forensics_

- Volatility: https://github.com/volatilityfoundation/volatility
- Volatility3: https://github.com/volatilityfoundation/volatility3
- GIMP: https://www.gimp.org/ with .dmp
- pyvmx-cracker: https://github.com/axcheron/pyvmx-cracker for .vmx password crack
- VMwareVMX: https://github.com/RF3/VMwareVMX for .vmx decrypt

#### 日志取证 _Log Forensics_

- LogForensics: https://security.tencent.com/index.php/opensource/detail/15
- ProcessMonitor: https://learn.microsoft.com/zh-cn/sysinternals/downloads/procmon
- Event log explorer: https://www.eventlogxp.com/
- LogonTracer: https://github.com/JPCERTCC/LogonTracer for Windows AD

#### 浏览器取证 _Browser Forensics_

- hindsight: Chrome/Chromium 取证 https://github.com/obsidianforensics/hindsight
- HackBrowserData: 浏览器导出解密 https://github.com/moonD4rk/HackBrowserData

### 密码破解 _Brute Force_

_Tools used for various kind of bruteforcing (passwords etc.)_

- crunch: 字典生成
	- Kali/Linux: https://sourceforge.net/projects/crunch-wordlist
	- Windows: https://github.com/shadwork/Windows-Crunch
- pydictor: 字典生成 md5 计算 https://github.com/LandGrey/pydictor/blob/master/README_CN.md
- aircrack-ng: 破解 wifi 密码 https://github.com/aircrack-ng/aircrack-ng
- Advanced Office Password Recovery（AOPR）: 破解 office 文档密码 https://www.elcomsoft.com/aopr.html
- Advanced Archive Password Recovery（ARCHPR）: 破解 zip 和 rar 文件密码 https://www.elcomsoft.com/archpr.html
- crc32: CRC32 爆破 https://github.com/theonlypwner/crc32
- ZipCenOp: zip 伪加密破解
- Ziperello: zip 压缩包密码破解
- c-jwt-cracker: JWT Token 爆破 https://github.com/brendan-rius/c-jwt-cracker
- how-does-Xmanager-encrypt-password: Xmanager 密码解密 https://github.com/HyperSine/how-does-Xmanager-encrypt-password
- SharpXDecrypt: Xshell 全版本密码恢复 https://github.com/JDArmy/SharpXDecrypt
- navicat_password_decrypt: Navicat 密码恢复 注册表 or .ncx https://github.com/Zhuoyuan1/navicat_password_decrypt

### 数据处理 _xx Editor_

- 010 Editor: https://www.sweetscape.com/010editor/
  - 010 Editor 插件模板下载: 例如 ELF.bt https://www.sweetscape.com/010editor/repository/templates/
- Binwalk: https://github.com/ReFirmLabs/binwalk
- 在线十六进制编辑器: https://hexed.it/
- 在线正则表达式: https://c.runoob.com/front-end/854/
- 在线正则表达式: https://regex101.com/
- 在线正则英语单词: https://regdict.com/

### 其他 _Others_

- 挖矿收益计算器: https://minersns.com/tools/jsqlist

## Web

> Omitted, see [Awesome-Redteam](https://github.com/Threekiii/Awesome-Redteam) for details.

## Pwn

### 仿真环境 _Emulation_

- CrossOver: https://www.crossoverchina.com/
- Qemu: https://github.com/qemu/qemu

### 二进制修改 _Binary Patching_

- https://github.com/Gallopsled/pwntools
- https://github.com/NixOS/patchelf
- https://github.com/io12/pwninit
- https://github.com/cyrus-and/gdb-dashboard
- https://github.com/lieanu/LibcSearcher
- https://github.com/redpwn/pow

### GDB 增强 _GDB Enhancement_

- Pwndbg: https://github.com/pwndbg/pwndbg
- Pwngdb: https://github.com/scwuaptx/Pwngdb
- gdb-dashboard: https://github.com/cyrus-and/gdb-dashboard 小内存调试（如 IoT）

### IDA 增强 _IDA Enhancement_

- idaplugins-list: https://github.com/onethawt/idaplugins-list
- keypatch: https://github.com/keystone-engine/keypatch
- sig-database: https://github.com/push0ebp/sig-database IDA FLIRT DB
- FLIRTDB: https://github.com/Maktm/FLIRTDB IDA FLIRT DB
- ida-pro-mcp: https://github.com/mrexodia/ida-pro-mcp IDA with AI

### ROP

- ROPgadget: https://github.com/JonathanSalwan/ROPgadget
- Ropper: https://github.com/sashs/Ropper

### 逆向 _Reverse_

#### 综合工具 _Nice Tools_

- OpenArk: https://github.com/BlackINT3/OpenArk anti-rootkit
- python arsenal for RE: https://pythonarsenal.com/ reverse toolkit
- IDA Pro: https://hex-rays.com/ida-pro/
- IDA Pro MCP: https://github.com/mrexodia/ida-pro-mcp IDA with AI
- Angr: https://github.com/angr/angr  binary analysis platform [doc]( https://docs.angr.io/) [examples](https://docs.angr.io/en/latest/examples.html)
- Cutter: https://cutter.re/ open source RE platform
- UPX: https://github.com/upx/upx

#### 静态分析 _Static Analysis_

- checksec: https://github.com/slimm609/checksec
- Detect-It-Easy: https://github.com/horsicq/Detect-It-Easy
- ExeinfoPE: https://github.com/ExeinfoASL/ASL
- PEiD: https://www.aldeid.com/wiki/PEiD
- bindiff: https://www.zynamics.com/software.html
- 在线编译器: https://godbolt.org/

#### 动态调试 _Dynamic Analysis_

- Ollydbg: https://www.ollydbg.de/
- x64dbg: https://x64dbg.com/

#### Java

- jadx: https://github.com/skylot/jadx
- JEB: https://www.pnfsoftware.com/
- GDA: https://github.com/charles2gan/GDA-android-reversing-Tool
- jd-gui: https://github.com/java-decompiler/jd-gui

#### Mobile

- scrcpy: https://github.com/Genymobile/scrcpy
- android-reverse: https://github.com/WuFengXue/android-reverse

#### Python

- py2exe: https://www.py2exe.org/ py->exe
- pyinstaller: https://github.com/pyinstaller/pyinstaller py->exe
- unpy2exe: https://github.com/matiasb/unpy2exe exe->pyc
- pyinstxtractor: https://github.com/extremecoders-re/pyinstxtractor exe->pyc
- pycDcode: https://github.com/rocky/python-uncompyle6/ pyc->py
- pycDcode: https://github.com/BarakAharoni/pycDcode

#### Rust/Go/.NET

- https://github.com/cha5126568/rust-reversing-helper for rust
- https://github.com/strazzere/golang_loader_assist for golang
- https://github.com/sibears/IDAGolangHelper for golang
- https://www.jetbrains.com/zh-cn/decompiler/ for .NET
- https://github.com/dnSpy/dnSpy for .NET
