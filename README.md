# Date A Live: Rio Reincarnation Dialogue Dataset

[Click here to switch to English](EN_README.md)

该仓库包含了从凛绪轮回（Date A Live: Rio Reincarnation）解包文件中提取的对话文本和对应的配音路径。这些数据可用于训练文本到语音（TTS）模型。

请注意，此数据集尚未剔除质量较差的文本和配音，因此用户可以自行处理或等待处理后的分支。如果您发现数据中存在问题或错误，请随时提交问题报告或请求合并。

## 数据集结构

- AudioText: 其中含有不同角色的txt文件, 内容格式为 AudioName|Text (注意: 若无对应音频文件，则会显示NoAudioFile)
- Dialogue: 包含1st.bin, 2st.bin, 3st.bin文件含有的所有对话， 内容格式为 Character|Text
- Audios.7z: 内含snd格式音频文件

## 角色列表(部分)


| 文件名        | 音频序号 | 英文名            | 中文名           | 日文名         |
|-------------|---------|-----------------|----------------|---------------|
| CHAR_SHIDO  | 0       | Itsuka Shido    | 五河 士道       | いつか しどう   |
| CHAR_TOHKA  | 1       | Yatogami Tohka  | 夜刀神 十香     | やとがみ とおか |
| CHAR_ORIGAMI| 2       | Tobiichi Origami| 鸢一 折纸       | とびいち おりがみ|
| CHAR_YOSHINO| 3       | Himekawa Yoshino| 氷芽川 四糸乃   | ひめかわ よしの |
| CHAR_KURUMI | 4       | Tokisaki Kurumi | 时崎 狂三       | ときさき くるみ |
| CHAR_KOTORI | 5       | Itsuka Kotori   | 五河 琴里       | いつか ことり   |
| CHAR_RINNE  | 6       | Sonogami Rinne  | 園神 凜祢       | そのがみ りんね |
| CHAR_YOSHINON|7      | Yoshinon        | 四糸奈           | よしのん       |
| CHAR_REINE  | 8       | Murasame Reine  | 村雨 令音       | むらさめ れいね |
| CHAR_KANAZUKI|9      | Kannazuki Kyouhei| 神無月 恭平     | かんなづき きょうへい|
| CHAR_TONOMACHI|10    | Tonomachi Hiroto| 殿町 宏人       | とのまち ひろと |
| CHAR_TAMAE   | 11     | Okamine Tamae   | 岡峰 珠惠       | おかみね たまえ |
| CHAR_KUSAKABE| 12     | Kusakabe Ryouko | 日下部 燎子     | くさかべ りょうこ |
| CHAR_AI      | 13     | Yamabuki Ai     | 山吹 亜衣       | やまぶき あい   |
| CHAR_MAI     | 14     | Unknown         | 叶樱麻衣         | Unknown       |
| CHAR_MII     | 15     | Fujibakama Mii  | 藤袴 美衣       | ふじばかま みい |
| CHAR_RULER   | 16     | Ruler           | Ruler          | ルーラー    |
| CHAR_MARIA   | 21     | Arusu Maria     | 或守 鞠亜       | あるす まりあ |
| CHAR_KAGUYA  | 22     | Yamai Kaguya    | 八舞 耶倶矢     | やまい かぐや |
| CHAR_YUZURU  | 23     | Yamai Yuzuru    | 八舞 夕弦       | やまい ゆづる |
| CHAR_MIKU    | 24     | Izayoi Miku     | 誘宵 美九       | いざよい みく |
| CHAR_MANA    | 25     | Takamiya Mana   | 崇宫 真那       | たかみや まな |
| CHAR_MIKIE   | 26     | Okamine Mikie   | 冈峰 美紀恵     | おかみね みきえ |
| CHAR_MARINA  | 27     | Arusu Marina    | 或守 鞠奈       | あるす まりな |
| CHAR_RIO     | 28     | Sonogami Rio    | 園神 凜緒       | そのがみ りお |

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
