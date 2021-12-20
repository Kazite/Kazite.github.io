---
layout: post
title: "【基本概念】半导体（Semiconductor）"
date: 2021-09-07
category:Note
typora-root-url: ../../../Kazite.github.io
typora-copy-images-to: ../../assets_2021Late

---

参考资料：

[[1]常见材料数据库网站](http://wap.sciencenet.cn/blog-1502061-1179947.html?mobile=1&from=timeline&isappinstalled=0)

[[2]知乎：如何理解有机发光中EQE与IQE](https://www.zhihu.com/question/66851499)

# 半导体参数基本知识

本周调研了几类半导体的基本性质，这里对收获的经验作一定总结

## 常用数据库

材料基本性质数据库

* [Materials Project](https://materialsproject.org/about)
* [Semiconductor physical properties database](http://www.ioffe.ru/SVA/NSM/Semicond/)

电子结构数据库

* [AFLOW](http://www.aflowlib.org/)

拓扑材料数据库

* [Materiae](http://materiae.iphy.ac.cn/#/)
* [Topological Materials Arsenal](https://ccmp.nju.edu.cn/)
* [Topological Materials Database](http://topologicalquantumchemistry.org/#/)
* [topological insulators](https://www.materialscloud.org/discover/2dtopo/dashboard/ptable)
* [TopoMat database](https://www.materialscloud.org/discover/topomat)
* [Topological Magnetic Materials Database](https://www.topologicalquantumchemistry.fr/magnetic/)

二维材料数据库

* [Materials Cloud](https://www.materialscloud.org/discover/2dstructures/dashboard/ptable)
* [2D Materials](https://materialsweb.org/twodmaterials)
* [Nano Lett. 17, 1915 (2017)文章及附件](https://pubs.acs.org/doi/abs/10.1021/acs.nanolett.6b05229)
* [Chem. Soc. Rev. 43, 6537 (2014)文章及附件](http://pubs.rsc.org/en/content/articlehtml/2014/cs/c4cs00102h)
* [Computational 2D materials database](https://cmrdb.fysik.dtu.dk/c2db/)

超导材料数据库

* [第I类超导体](http://www.superconductors.org/Type1.htm)
* [第II类超导体](http://www.superconductors.org/Type2.htm)

磁结构数据库

* [MAGNDATA](http://webbdcrista1.ehu.es/magndata/index.php?show_db=1)

声子谱

* [phonondb@kyoto-u](http://phonondb.mtl.kyoto-u.ac.jp/index.html)

非线性光学晶体数据库

* [Nonlinear Optical Crystal First-Principles Database](http://nlo.hbu.cn/#/)

光学数据库

* [RefractiveIndex.INFO](https://refractiveindex.info/?shelf=main&book=Be&page=Rakic-BB)
* [LUXPOP](http://www.luxpop.com)
* [n,k database](http://www.ioffe.ru/SVA/NSM/nk/)

## 外量子效率与内量子效率

**External Quantum Efficiency (EQE)** is the ratio of the number of charge carriers collected by the solar cell to the number of photons of a given energy *shining on the solar cell from outside* (incident photons).

**Internal Quantum Efficiency (IQE)** is the ratio of the number of charge carriers collected by the solar cell to the number of photons of a given energy that shine on the solar cell from outside *and* are absorbed by the cell.

發光二極體的發光效率一般稱為元件的外部量子效率(external quantum efficiency)，其為元件的內部量子效率(internal quantum efficiency)及元件的取出效率(extraction efficiency)的乘積。所謂元件的內部量子效率其實就是元件本身的電光轉換效率，主要與元件本身的特性如元件材料的能帶、缺陷、雜質及元件的磊晶組成及結構等相關。而元件的取出效率指的則是元件內部產生的光子，在經過元件本身的吸收、折射、反射後實際上在元件外部可量測到的光子數目。因此相關於取出效率的因素包括了元件材料本身的吸收、元件的幾何結構、元件及封裝材料的折射率差及元件結構的散射特性等。而上述兩種效率的乘積，就是整個元件的發光效果，也就是元件的外部量子效率。

**室友的自我理解：**量子效率有点像是能量转换效率，把输入的能量转化为光能，内量子效率就是这个材料发光中心把能量转换成光能的能力，可能是理论算出来的，外量子效率是实际测得的光子，闪烁体发光是在晶体内部，传播过程中的损耗和吸收还有界面处的全反射会导致实际收集的光子数很少