# Portfolio

## About Me
**featlis**

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&duration=1600&pause=10000&color=38B3F7&width=900&height=70&lines=%E3%82%88%E3%82%8F%E3%82%88%E3%82%8F%E3%83%87%E3%83%99%E3%83%AD%E3%83%83%E3%83%91%E3%83%BC%E7%AD%86%E9%A0%AD%E3%82%92%E5%8B%9D%E6%89%8B%E3%81%AB%E5%8B%99%E3%82%81%E3%81%95%E3%81%9B%E3%81%A6%E3%81%84%E3%81%9F%E3%81%A0%E3%81%84%E3%81%A6%E3%81%84%E3%81%BE%E3%81%99)](https://git.io/typing-svg)

<div align="center">
  <img src="https://raw.githubusercontent.com/SAWARATSUKI/KawaiiLogos/main/IamSeries/png/IamProgrammer!.png" width="350" alt="I am Programmer">
</div>

情報工学やデータサイエンスの勉強をしています。プログラミングはまだ勉強中で未熟ですが、少しずつソフトウェア開発にも挑戦しています。
また、VRChatのワールド作成やUnityを使ったアバター改変など、VRの世界で遊ぶことも好きです。

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=featlis&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" height="150" alt="GitHub Stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=featlis&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" height="150" alt="Top Languages">
</div>

## Projects

### PrintTweet for Discord
Twitter(X)のURLから、ツイートのスクリーンショット画像をDiscordに送信する小さなBotを作ってみました。

#### 🛠 使用技術
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  <img src="https://img.shields.io/badge/tweetcapture-000000?style=for-the-badge&logo=github&logoColor=white" alt="tweetcapture">
</p>

#### ✨ 主な機能と技術的な工夫
* **高品質な画像生成**: `tweetcapture` を用いて、RT・いいね数なども含めたツイートのスクリーンショットを生成します。
* **柔軟なテーマ対応**: スラッシュコマンド引数でライト・ダーク・ブラックモードを切り替えられます。

### Twitter Translate BOT for Discord
Discordでのコミュニケーションを少し便利にする、X(Twitter)のリンクを検知して翻訳するBotを作成しました。

#### 🛠 使用技術
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  <img src="https://img.shields.io/badge/aiohttp-2C5BB4?style=for-the-badge&logo=aiohttp&logoColor=white" alt="aiohttp">
</p>

#### ✨ 主な機能と技術的な工夫
* **非同期処理**: ユーザーのメッセージからリンクを抽出し、非同期HTTPクライアント（`aiohttp`）を用いてAPIから翻訳結果を取得します。
* **UIの実装**: `discord.ui.View` を活用したボタンUIを実装し、チャット上で直感的に翻訳先の言語を切り替えられるようにしました。
* **ローカライゼーション**: ユーザーのDiscordクライアント言語設定を判定し、メッセージを翻訳する仕組みを取り入れました。
* **設定の永続化**: スラッシュコマンドで変更したサーバー設定を `bot_config.json` に保存するようにしました。

## Skills & Interests
* **プログラミング / ソフトウェア開発**
  * Python (データ分析、Discord Bot開発)
  * Unity (VRChatワールド構築、アバター改変)
* **学習領域**
  * 情報理論、離散数学、複素解析
* **趣味・活動**
  * デジタルイラスト制作 (CLIP STUDIO PAINT, Affinity Photo)
  * ゲーム、読書

## Credits & License
このプロフィールおよびポートフォリオでは、以下の素晴らしいリソース・ライブラリを使用させていただいています：

- **KAWAII LOGOS** by [SAWARATSUKI](https://github.com/SAWARATSUKI/KawaiiLogos) (Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.ja))
- **GitHub Readme Stats** by [anuraghazra](https://github.com/anuraghazra/github-readme-stats) (Licensed under [MIT License](https://github.com/anuraghazra/github-readme-stats/blob/master/LICENSE))
- **Readme Typing SVG** by [DenverCoder1](https://github.com/DenverCoder1/readme-typing-svg) (Licensed under [MIT License](https://github.com/DenverCoder1/readme-typing-svg/blob/main/LICENSE))
