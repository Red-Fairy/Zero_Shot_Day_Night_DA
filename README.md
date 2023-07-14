<h2 align="center">
  <b>Similarity Min-Max: Zero-Shot Day-Night Domain Adaptation</b>

  <b><i>ICCV 2023</i></b>


<div align="center">
    <a href="https://cvpr.thecvf.com/virtual/2023/poster/22552" target="_blank">
    <img src="https://img.shields.io/badge/ICCV 2023-Conference Paper-red"></a>
    <a href="" target="_blank">
    <img src="https://img.shields.io/badge/Paper-arXiv-green" alt="Paper arXiv"></a>
    <!-- <a href="https://pku-epic.github.io/GAPartNet/" target="_blank">
    <img src="https://img.shields.io/badge/Page-GAPartNet-blue" alt="Project Page"/></a> -->
</div>
</h2>

---

This the official repository of the paper **Similarity Min-Max: Zero-Shot Day-Night Domain Adaptation**.

For more information, please visit our [project website](https://github.com/Red-Fairy/ZeroShotDayNightDA).

Authors: Rundong Luo, Wenjing Wang, Wenhan Yang, Jiaying Liu

## Abstract
Low-light conditions not only hamper human visual experience but also degrade the model's performance on downstream vision tasks. While existing works make remarkable progress on day-night domain adaptation, they rely heavily on domain knowledge derived from the task-specific nighttime dataset. This paper challenges a more complicated scenario with border applicability, *i.e.*, zero-shot day-night domain adaptation, which eliminates reliance on any nighttime data. Unlike prior zero-shot adaptation approaches emphasizing either image-level translation or model-level adaptation, we propose a similarity min-max paradigm that considers them under a unified framework. On the image level, we darken images towards minimum feature similarity to enlarge the domain gap. Then on the model level, we maximize the feature similarity between the darkened images and their normal-light counterparts for better model adaptation. To the best of our knowledge, this work represents the pioneering effort in jointly optimizing both aspects, resulting in a significant improvement of model generalizability. Extensive experiments demonstrate our method's effectiveness and broad applicability on various nighttime vision tasks, including classification, semantic segmentation, visual place recognition, and video action recognition.