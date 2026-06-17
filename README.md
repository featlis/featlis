# Portfolio

## About Me
**featlis**

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&duration=1600&pause=10000&color=38B3F7&width=900&height=70&lines=%E3%82%88%E3%82%8F%E3%82%88%E3%82%8F%E3%83%87%E3%83%99%E3%83%AD%E3%83%83%E3%83%91%E3%83%BC%E7%AD%86%E9%A0%AD%E3%82%92%E5%8B%9D%E6%89%8B%E3%81%AB%E5%8B%99%E3%82%81%E3%81%95%E3%81%9B%E3%81%A6%E3%81%84%E3%81%9F%E3%81%A0%E3%81%84%E3%81%A6%E3%81%84%E3%81%BE%E3%81%99)](https://git.io/typing-svg)

国立高等専門学校
情報工学、データサイエンス、ときたまにソフトウェア開発に取り組んでいる。
また、VRChat向けの世界構築や、Unityを用いたアバターのカスタマイズ（VRCFury, Modular Avatar等）など、VR技術にも強い関心を持つ。

## Projects

### Twitter Translate BOT for Discord
Discord上のメッセージに含まれるTwitter (X) のリンクを自動的に検知し、指定された言語に翻訳して返信する高機能Bot。

#### 🛠 使用技術
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  <img src="https://img.shields.io/badge/aiohttp-2C5BB4?style=for-the-badge&logo=aiohttp&logoColor=white" alt="aiohttp">
</p>

#### ✨ 主な機能と技術的な工夫
* **シームレスな非同期処理**: ユーザーのメッセージからリンクを抽出し、非同期HTTPクライアント（`aiohttp`）を用いてAPIから高速に翻訳結果を取得・表示する。
* **インタラクティブなUIの実装**: `discord.ui.View` を活用したボタンUIを実装。ユーザーはチャット上で直感的に翻訳先の言語をリアルタイムで切り替えられる。
* **徹底したローカライゼーション**: `discord.app_commands.Translator` を拡張した `DiscordTranslator` クラスを独自に実装。ユーザーのDiscordクライアントの言語設定を自動判定し、コマンド説明やシステムメッセージを動的に翻訳する。
* **設定の永続化**: `/set_default_lang` などのスラッシュコマンドで変更したサーバー設定を `bot_config.json` に保存し、再起動後も状態を維持する堅牢な設計。

## Skills & Interests
* **プログラミング / ソフトウェア開発**
  * Python (データ分析、Discord Bot開発)
  * Unity (VRChatワールド構築、アバター改変)
* **学習領域**
  * 情報理論、離散数学、複素解析
* **趣味・活動**
  * デジタルイラスト制作 (CLIP STUDIO PAINT, Affinity Photo)
  * ゲーム、読書
