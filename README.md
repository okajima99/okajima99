# Tsukasa Okajima

LLM・推薦システム・自動化ツールの設計・実装に取り組んでいます。  
動くシステムを作りながら、AI エンジニアリングの実力を積み上げています。

## 主なプロジェクト

### [RSS-LLM-Agent](https://github.com/okajima99/RSS-LLM-Agent)
RSSフィードの収集・LLMによる記事要約・Embeddingモデルを用いた多軸スコアリング・2エージェントcuratorによる意味的選別・LINE通知までを一貫して行うパーソナライズ情報エージェント。BGE-M3 + Claude Code CLI + macOS launchd で構成し、個人環境で継続運用中。

### [HAVEN](https://github.com/okajima99/pwa-client)
ローカルPC上の Claude Code CLI セッションをスマートフォンから操作するためのPWAクライアント。FastAPIバックエンドで複数エージェントセッションを並走管理し、SSEストリーミングでリアルタイム応答を表示。Tailscale経由のプライベートアクセス構成。

### [Agent-Based-Dig-Recommender-Simulator](https://github.com/okajima99/Agent-Based-Dig-Recommender-Simulator)
推薦アルゴリズムがユーザーの嗜好・情報探索行動に与える影響を、エージェントベースモデル（ABM）でシミュレーションした卒業研究プロジェクト。PyTorch + CUDA 環境で実装。

### [learning](https://github.com/okajima99/learning)
ML / LLM 関連の学習リポジトリ。Transformer の minimal 実装・RAG の minimal 実装など。

## 技術スタック

- **言語**: Python
- **AI / ML**: LLM（Claude API）, BGE-M3, PyTorch
- **バックエンド**: FastAPI
- **フロントエンド**: React / Vite（PWA）
- **その他**: macOS launchd, Tailscale, Git / GitHub
