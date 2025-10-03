<div align="center">
<br>
<h3>Incremental Learning for AI-generated Image Detection</h3>

Zihao Cai<sup>1†</sup>, Xue Song<sup>1†</sup>, Xinhan Li<sup>1</sup>, Bo Li<sup>1</sup>, Haijun Shan<sup>2</sup>, [Jingjing Chen](https://scholar.google.com/citations?hl=zh-CN&user=DfWdqzQAAAAJ)<sup>1‡</sup>

<div class="is-size-6 publication-authors">
  <p class="footnote">
    <span class="footnote-symbol"><sup>†</sup></span>Equal contribution
    <span class="footnote-symbol"><sup>‡</sup></span>Corresponding author
  </p>
</div>

<sup>1</sup>Fudan University <sup>2</sup>CEC GienTech Technology Co.,Ltd.

</div>

## 🎨 FakeCOCO 
<p align="center"><img src="docs/Visualization of dataset.jpg" width="800"/></p>

**License**:
```
FakeCOCO is only used for academic research. Commercial use in any form is prohibited.
```

**Comparison of `FakeCOCO` with existing benchmark.**

<p align="center"><img src="docs/Comparison with existing benchmark.jpg" width="800"/></p>
To better understand the characteristics of our dataset, we visualized both FakeCOCO and GenImage for a side-by-side comparison. The key difference lies in their prompt sources:


- FakeCOCO (Ours): Generated from detailed COCO captions, capturing the complexity and context of real-world scenarios.

- GenImage: Generated from simple ImageNet class names, which usually focus on a single object.

As a result, our generated images tend to portray multifaceted scenes with multiple objects, diverse textures, and intricate interactions, allowing them to better simulate the real world.

### Download
The proposed dataset "FakeCOCO" has been released on modelscope.


## 🚀 TODO

- ✅ &nbsp; Release the FakeCOCO dataset

- ⬜️ &nbsp; Release checkpoints

- ⬜️ &nbsp; Release inference scripts

- ⬜️ &nbsp; Release training code

## ✉️ Contact
If you have any question about this project, please feel free to contact zhcai25@m.fudan.edu.cn.