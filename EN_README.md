# Date A Live: Rio Reincarnation Dialogue Dataset

[Click here to switch to Chinese](README.md)

This repository contains extracted dialogue text and corresponding audio paths from the unpacked files of "Date A Live: Rio Reincarnation" game. This data can be used for training Text-to-Speech (TTS) models.

Please note that this dataset has not been curated for poor-quality text and audio. Users may handle it themselves or wait for an updated branch. If you discover any issues or errors in the data, feel free to submit bug reports or merge requests.

## Dataset Structure

- AudioText: Contains txt files for different characters, with the format AudioName|Text (Note: If there is no corresponding audio file, it will display "NoAudioFile").
- Dialogue: Contains all the dialogues from 1st.bin, 2nd.bin, and 3rd.bin files, with the format Character|Text.
- Audios.7z: Contains audio files in the snd format.

## Character List (Partial)

| Filename     | Audio Index | English Name       | Chinese Name      | Japanese Name    |
|-------------|------------|-------------------|------------------|------------------|
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

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/hzrr/date-a-live-rio-reincarnation-dialogue.git
```

2. Navigate to the repository directory:

```bash
cd date-a-live-rio-reincarnation-dialogue
```

3. Review and process the dataset, removing poor-quality text or waiting for an updated branch.

4. Use the dataset for training or other required operations.

## Contributions

Contributions are welcome! If you would like to add higher-quality dialogue text and audio to the dataset or improve the dataset in any way, please follow the contribution guidelines to submit your contributions.

## License

The copyright and license for this dataset are described in the [LICENSE](LICENSE) file.

Please note that the "Date A Live: Rio Reincarnation" series and related content are the property of their respective owners.

## Utilized Unpacking Tool

This project utilizes [DALTools](https://github.com/thesupersonic16/DALTools) for the unpacking process. We would like to express our heartfelt gratitude to the developer of DALTools, [thesupersonic16](https://github.com/thesupersonic16), whose tool greatly assists in the development of this project.

Please note that DALTools unpacking tool is copyrighted by [thesupersonic16](https://github.com/thesupersonic16). For licensing and usage requirements, please refer to the relevant information in the source code repository. We appreciate their open-source contribution!
