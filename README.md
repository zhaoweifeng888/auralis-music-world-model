# Auralis：基于 JEPA 的音乐世界模型

Auralis: A JEPA-Based World Model for Music

作者 / Author: 赵伟峰 (Weifeng Zhao)

Auralis 是一个个人研究项目，探索在音频音乐生成模型的内部表示上引入 JEPA，预测音乐片段之间的关系。当前处于研究提案和代码原型阶段，尚未训练，没有模型权重或实验结果。

Auralis is a personal research project exploring JEPA over internal representations of audio music generation models. It is an untrained proposal and prototype with no released weights or experimental results.

## 技术报告 / Technical reports

- [中文版技术报告](technical-report-zh.md)
- [English technical report](technical-report-en.md)

## 代码 / Code

[下载完整研究项目包（ZIP）](auralis-research.zip)。压缩包中分为 report/ 和 code/ 两个目录，包含双语报告及基础训练代码。

[Download the complete research package (ZIP)](auralis-research.zip). The archive contains report/ and code/ directories with bilingual reports and the training prototype.

代码接受外部预先提取的一维音频 token，尚不包含真实音频 token 提取器、ACE-Step 接入、评估、歌曲生成或音频输出；代码尚未在 PyTorch 环境中运行验证。架构图为研究设计，接口均待验证。

The code accepts pre-extracted one-dimensional audio tokens. Audio token extraction, ACE-Step integration, evaluation and audio generation are not implemented; the prototype has not yet been run in a PyTorch environment.

建议数据集及其限制见技术报告。请分别核对代码、模型、数据及底层作品的许可。Auralis 名称已被其他音乐和音频项目使用，尚未完成全面同名或商标检索。
