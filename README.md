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

## 许可 / License

本项目的原创技术报告、架构图和代码由赵伟峰（Weifeng Zhao）以 [CC BY-NC 4.0（署名—非商业性使用）](https://creativecommons.org/licenses/by-nc/4.0/deed.zh-hans) 许可发布。允许按协议进行非商业分享和改编，分享时须署名、注明修改并保留许可信息。商业使用请联系作者另行取得书面授权：149199879@qq.com。第三方代码、模型、数据及音乐作品遵循各自许可。

Copyright (c) 2026 Weifeng Zhao (赵伟峰). Original reports, architecture diagrams and code are licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). Noncommercial sharing and adaptation are permitted under the license, with attribution, indication of changes and retention of license information when sharing. For separate written commercial permission, contact 149199879@qq.com. Third-party code, models, datasets and musical works remain subject to their own terms.

完整协议见 [LICENSE](LICENSE)。
