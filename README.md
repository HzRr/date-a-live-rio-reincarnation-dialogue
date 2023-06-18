# Date A Live: Rio Reincarnation Dialogue Dataset

[Click here to switch to English](EN_README.md)

该仓库包含了从凛绪轮回（Date A Live: Rio Reincarnation）解包文件中提取的对话文本和对应的配音路径。这些数据可用于训练文本到语音（TTS）模型。

请注意，此数据集尚未剔除质量较差的文本和配音，因此用户可以自行处理或等待处理后的分支。如果您发现数据中存在问题或错误，请随时提交问题报告或请求合并。

## 数据集结构

- AudioText: 其中含有不同角色的txt文件, 内容格式为 AudioName|Text (注意: 若无对应音频文件，则会显示NoAudioFile)
- Dialogue: 包含1st.bin, 2st.bin, 3st.bin文件含有的所有对话， 内容格式为 Character|Text
- Audios.7z: 内含snd格式音频文件

## 使用方法

1. 克隆仓库到本地：

```bash
git clone https://github.com/hzrr/date-a-live-rio-reincarnation-dialogue.git
```

2. 进入仓库目录：

```bash
cd date-a-live-rio-reincarnation-dialogue
```

3. 查看并处理数据集，剔除质量较差的文本或等待处理后的分支。

4. 使用数据集进行训练或其他需要的操作。

## 贡献

欢迎贡献！如果您想向该数据集添加更高质量的对话文本和配音，或对数据集进行改进，请按照贡献指南提交您的贡献。

## 授权许可

该数据集的版权和许可遵循 [LICENSE](LICENSE) 文件中所述。

请注意，凛绪轮回（Date A Live: Rio Reincarnation）系列及相关内容的版权归原始版权所有者所有。

## 使用的解包工具

本项目使用了 [DALTools](https://github.com/thesupersonic16/DALTools) 来进行解包操作。我们在此对 DALTools 的开发者 [thesupersonic16](https://github.com/thesupersonic16) 表示衷心的感谢，他的工具为本项目的开发提供了极大的帮助。

请注意，DALTools 解包工具的版权归 [thesupersonic16](https://github.com/thesupersonic16) 所有。如需了解其许可和使用要求，请在源代码仓库查看相关信息。感谢他们的开源贡献！
