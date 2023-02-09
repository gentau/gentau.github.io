---
sort: 1
---


# Astronomy software

## iSpec

iSpec 是一个用于光谱分析的开源框架（Blanco-Cuaresma et al. 2014a, Blanco-Cuaresma 2019）。它适用于建立诸如 Gaia FGK 基准恒星库一样的光谱库（Blanco-Cuaresma et al 2014b，以及用于确定一些如有效温度、表面重力加速度、金属丰度和单个丰度等的天体物理参数。iSpec 结合了几个辐射转移代码用以生成合成光谱，以及从等值宽度中获取丰度。此外，iSpec 还可以从预先计算好的网格中进行光谱的插值。

该框架提供了可以从 Python3 脚本中使用的 API，它也包含了一个符合 SAMP 协议的可视化界面，可以与其他天文应用软件协同工作。这些应用软件有 TOPCAT , VOSpec (🐛, 英文文档的链接已经失效), 以及使用间接方式访问 Virtual Observatory 的 splat

用户可以从此链接 获取 iSpec。除了 iSpec 自身使用到的辐射转移代码（如下列出），iSpec 在 GNU Affero General Public License (开源软件许可) 条例下进行分发。

SPECTRUM R. O. Gray
Turbospectrum Bertrand Plez (🐛, 英文文档的链接已经失效)
SME Valenti & Piskunov
MOOG Chris Sneden
Synthe/WIDTH9 Kurucz/Atmos

Note: 以上内容来自Ispec中文使用手册网站: https://iscottmark.github.io/iSpec/
官方网站: https://www.blancocuaresma.com/s/iSpec