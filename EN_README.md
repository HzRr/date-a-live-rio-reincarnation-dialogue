# Date A Live: Rio Reincarnation Dialogue Dataset

[Click here to switch to Chinese](README.md)

This repository contains extracted dialogue text and corresponding audio paths from the unpacked files of "Date A Live: Rio Reincarnation" game. This data can be used for training Text-to-Speech (TTS) models.

Please note that this dataset has not been curated for poor-quality text and audio. Users may handle it themselves or wait for an updated branch. If you discover any issues or errors in the data, feel free to submit bug reports or merge requests.

## Dataset Structure

- AudioText: Contains txt files for different characters, with the format AudioName|Text (Note: If there is no corresponding audio file, it will display "NoAudioFile").
- Dialogue: Contains all the dialogues from 1st.bin, 2nd.bin, and 3rd.bin files, with the format Character|Text.
- Audios.7z: Contains audio files in the snd format.

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