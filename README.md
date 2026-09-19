The documentation for translation is [here](https://github.com/vcmi/vcmi/blob/develop/docs/translators/Translations.md).

Information for dubbing are [here](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)

Please create a new issue [here](https://github.com/vcmi-mods/japanese-translation/issues/new) for any mistake.

# How to play to Heroes of Might and Magic III in Japanese

1. Buy _Heroes of Might and Magic III Complete Edition_ on GOG (not the HD version)
1. Install the game
1. Download VCMI (free)
1. Install VCMI
1. When installing VCMI, specify the location of the base game's `Data`, `MP3`, and `Maps` folders.
1. Set the language to _Japanese_
1. Install the _日本語訳_ mod
1. Launch the game

# Heroes of Might and Magic III を日本語でプレイする方法

1. GOGで_Heroes of Might and Magic III Complete Edition_を購入します（HD版ではありません）。
1. ゲームをインストールします。
1. VCMIをダウンロードします（無料）。
1. VCMIをインストールします。
1. VCMIをインストールする際、ベースゲームの「Data」、「MP3」、「Maps」フォルダの場所を指定します。
1. 言語を_Japanese_に設定します。
1. _日本語訳_ modをインストールします。
1. ゲームを起動します。

# How to dub

1. Copy a prolog/epilog from [`japanese-translation/content/config/vcmi-japanese/campaigns.json`](https://github.com/vcmi-mods/japanese-translation/tree/vcmi-1.7/content/config/vcmi-japanese)
2. Go to [ZONOS 2](https://huggingface.co/spaces/multimodalart/ZONOS2)
4. Paste the speech text
5. Select _Japanese_
4. Upload a voice
6. Click on _Generate_
7. Download the audio file
8. Retrieve the property for the speech in the [`japanese-translation/content/config/vcmi-japanese/campaigns.json`](https://github.com/vcmi-mods/japanese-translation/tree/vcmi-1.7/content/config/vcmi-japanese) file
9. Retrieve the related audio filename in the [empty-translation mod](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)
10. Rename the audio file
11. Move the file to `japanese-translation/content/sounds/` folder

# How to contribute

1. Go to the GitHub mod page: https://github.com/vcmi-mods/japanese-translation
2. Fork the repository by clicking on the "Fork" button
3. Browse to the file you want to change
4. Click on the pencil button to edit the file
5. Edit the file
6. Click on the "Commit changes..." button
7. Click on the "Pull request" tab
8. Click on the "Create Pull Request" button
9. Write a description and create the PR (Pull Request)