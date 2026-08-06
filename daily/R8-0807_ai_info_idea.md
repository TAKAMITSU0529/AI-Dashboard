# AI情報ブリーフィング R8-0807（2026-08-07）
作成：AI Company CTO（技術・AI担当）

---

## ① AIニュース Top5

### 1. Claude Opus 5 正式リリース・Sonnet 5 の料金改定が迫る
**要約**
Anthropic が Claude Opus 5 を正式リリース。Claude Max・Claude Pro のデフォルトモデルとなり、コーディング・知識労働・科学研究に最適化された最上位モデルとして位置づけられた。同時に Sonnet 5 のプロモーション料金（$2/$10/百万トーク）は 8/31 終了、9/1 より標準料金（$3/$15）に移行予定。

**重要性**
- **AI研修事業**：研修コンテンツに「Opus 5 vs Sonnet 5 のコスト設計」を追加できる。中小企業向けAI導入研修で「モデル選択の経済合理性」を教えると差別化になる
- **Web制作事業**：Claude API を使ったコード生成・提案書自動化コスト計算を 9/1 前に見直す必要あり
- **補助金支援事業**：Claude を使った補助金申請書自動生成ツールのランニングコストに影響する可能性

**ソース**：https://releasebot.io/updates/anthropic/claude

---

### 2. OpenAI が GPT-5.6 Sol を投入・無料枠でも無制限チャット化
**要約**
OpenAI が GPT-5.6 Sol を ChatGPT に展開。より直接的・簡潔な回答スタイルに改善し、Plus/Pro ユーザーには「推論努力スライダー」も追加（簡単な質問は低推論、複雑な計画立案は高推論に切替可能）。また無料ユーザーへの無制限チャット開放を発表。

**重要性**
- **AI研修事業**：「推論努力スライダー」は研修の教材として即活用できる。コスト最適化の具体的操作方法として説明できる
- **Web制作事業**：無料 GPT-5.6 へのアクセス拡大により、中小クライアントも AI 活用の入口に立ちやすくなる。AI 活用支援のきっかけとして提案しやすい環境になった

**ソース**：https://9to5mac.com/2026/08/06/openai-updating-chatgpt-with-a-smarter-gpt-5-6-sol-and-unlimited-free-chats/

---

### 3. Google Gemini 3.6 Flash が安定版リリース・サブエージェント向けモデルも登場
**要約**
Gemini 3.6 Flash が production-ready の安定版としてリリース。コード生成・エージェント計画立案能力が向上し、3.5 Flash より低コスト。さらに高容量自動化向けの超低レイテンシモデル「Gemini 3.5 Flash-Lite」も提供開始。

**重要性**
- **Web制作事業**：サブエージェント構成（調査→設計→コード生成の自動化）を Gemini 3.6 Flash-Lite で低コスト運用できる可能性。Web 制作の一部を AI エージェントに委ねるワークフロー設計に活用できる
- **AI研修事業**：「Google vs Anthropic のモデル比較」コンテンツとして研修で扱えるタイムリーなネタ
- **補助金支援**：複数補助金のリサーチ→申請書ドラフトをエージェントで自動化するコストが下がる

**ソース**：https://ai.google.dev/gemini-api/docs/changelog

---

### 4. OpenClaw が iOS/Android アプリ化・Meta AI との統合も進行中
**要約**
オープンソースAIエージェントフレームワーク「OpenClaw」がついに iOS・Android アプリとして正式リリース（2026/6/30）。同時に Meta AI との統合も進行中で、Manus AI も Telegram 経由のモバイルエージェント操作に対応。OpenClaw の創設者 Peter Steinberger が OpenAI に入社したことも注目を集めている。

**重要性**
- **AI研修事業**：「スマホだけで AI エージェントを動かす」研修コンテンツが作れる。スモールビジネスオーナーへの訴求力が高い
- **陰陽師/占い事業**：OpenClaw モバイルアプリを使った占い自動配信・鑑定スケジューリングの自動化が実現可能に
- **Web制作事業**：クライアント向けに「自社でも使える AI エージェント」として OpenClaw を組み込んだ提案書が作りやすくなった

**ソース**：https://techcrunch.com/2026/06/30/openclaw-is-finally-available-on-android-and-ios/

---

### 5. Manus AI（Meta傘下）が「My Computer」機能でデスクトップ制御参入
**要約**
Meta 傘下の Manus AI が「My Computer」機能を発表し、PC 上のアプリ操作・リサーチ・メール管理・ワークフロー自動化が可能なデスクトップエージェントとして OpenClaw に直接競合。Telegram 経由でスマホからサブエージェントを操作する機能も追加された。

**重要性**
- **全事業共通**：PC 操作をまるごと AI に委任できる時代が到来。Manus の「My Computer」で日常的なバックオフィス作業（請求書作成・スプレッドシート更新・メール対応）を自動化できる
- **AI研修事業**：「Manus でここまでできる」という実演が研修の目玉コンテンツになる。スモールビジネス向けの自動化デモとして最適

**ソース**：https://www.fm-magazine.com/issues/2026/aug/manus-ai-agent-skills-openclaw-and-more-part-2/

---

## ② マイクロ法人 × AI活用で大きく稼いでる事例 5選

### 事例1：Matthew Gallagher（米・LA在住・41歳）｜医療テックスタートアップ

| 項目 | 詳細 |
|------|------|
| 何を | Medvi：GLP-1（肥満治療薬）テレヘルスプラットフォーム |
| どうやって | $20,000 の元手・正社員 1 名のみ。医療インフラはアウトソース（規制対応は外注）、顧客獲得と LP 改善に集中 |
| チーム規模 | 実質 1 人＋業務委託数名 |
| 使用AIツール | ChatGPT / Claude / Grok（業務全般）・ElevenLabs（音声顧客対応）・Midjourney / Runway（広告クリエイティブ生成） |
| 売上 | 2025年度：$401M（約600億円）売上・純利益率16.2%。2026年予測：$1.8B（約2,700億円） |
| 収益モデル | DTC（直販サブスク）＋提携医師ネットワーク |

**社長の事業への応用**
- **補助金支援事業**：「補助金申請のインフラ（審査・資料作成）は外注・提携で、顧客獲得と LP に集中」という Medvi 型モデルを採用できる
- **AI研修事業**：「$20K で $1.8B の会社を作った AI 活用法」は研修の最強事例として使える

**ソース**：https://www.forbes.com/sites/josipamajic/2026/04/02/ai-and-20000-helped-one-man-build-a-18-billion-telehealth-startup/

---

### 事例2：Pieter Levels（オランダ・35歳）｜インディーハッカー

| 項目 | 詳細 |
|------|------|
| 何を | Photo AI（AI写真生成）・NomadList（ノマドコミュニティ）・Remote OK（リモート求人）・FlightSim（AIフライトシミュレーター）など |
| どうやって | 1 人・バニラ PHP・VCなし。アイデアを 3〜4 時間でプロトタイプ化し、有料ユーザーがついてから育てる |
| チーム規模 | 1 人（社員ゼロ） |
| 使用AIツール | Claude Code（コーディング）・Midjourney（画像）・Stable Diffusion |
| 売上 | Photo AI だけで MRR $132K（年率約2億円）。全ポートフォリオで年収 $3M＋（約4.5億円） |
| 収益モデル | サブスク SaaS + 広告 |

**社長の事業への応用**
- **Web制作事業**：「Claude Code で 3 時間でプロト作成→有料化テスト」という Levels 式スピード開発を Web 制作案件のサービス化プロセスに取り込める
- **陰陽師/占い事業**：Photo AI 型の「占い専用画像生成AI」サービスをニッチ特化で展開するアイデアがある

**ソース**：https://www.indiehackers.com/post/photo-ai-by-pieter-levels-complete-deep-dive-case-study-0-to-132k-mrr-in-18-months-3a9a2b1579

---

### 事例3：@ridark_eth（匿名・30歳・米国）｜ポートフォリオ型マイクロSaaS

| 項目 | 詳細 |
|------|------|
| 何を | 35 本の「地味な問題を解くシンプルツール」をポートフォリオ化 |
| どうやって | Claude ＋ コードエディタのみ。1日4〜6時間の深い作業に集中。VC なし・チームなし |
| チーム規模 | 1 人 |
| 使用AIツール | Claude（コーディング・UX設計） |
| 売上 | 月収 $77,000（約1,100万円）。各ツールは $1K MRR 達成率18%→35本で統計的に確実に当たりが出る |
| 収益モデル | 月額サブスク（各 $9〜$49/月） |

**社長の事業への応用**
- **Web制作事業**：Web 制作と並行して「地味に売れる業務ツール」を年間3〜5本リリースする副収益ストリームを作れる。年商3,200万円達成への複線化
- **補助金支援事業**：「補助金書類チェッカー SaaS」「補助金採択率 AI 診断ツール」など補助金領域の地味ツールはニッチ独占しやすい

**ソース**：https://www.buildmvpfast.com/blog/solo-developer-35-micro-saas-apps-77k-month-portfolio-2026

---

### 事例4：Nebula アプリ（米国チーム・占星術アプリ）

| 項目 | 詳細 |
|------|------|
| 何を | Nebula：AI 占星術アプリ。チャット鑑定・毎日の星座運勢・相性診断 |
| どうやって | フリーミアムで獲得→プレミアム鑑定へ誘導。LLM による個人化ホロスコープ生成 |
| チーム規模 | 小規模スタートアップ（10名未満） |
| 使用AIツール | LLM（OpenAI API）＋ 占星術計算エンジン |
| 売上 | 月収 $516,000（約7,700万円/月・年率 $6.2M） |
| 収益モデル | アプリ内課金（月 $19.99〜）＋個別鑑定 |

**社長の事業への応用**
- **陰陽師/占い事業**：日本版「陰陽師 AI 鑑定アプリ」は海外 Nebula の日本特化版として十分勝機がある。四柱推命・九星気学・陰陽道などの独自性で差別化できる
- 月額1,980円 × 1,000ユーザー = 月収198万円のモデルは現実的なターゲット

**ソース**：https://ai.omisoft.net/ai-astrology-app-development-predict-your-success/

---

### 事例5：Wayfare Tavern × Hostie AI（飲食×AI予約自動化）

| 項目 | 詳細 |
|------|------|
| 何を | Wayfare Tavern（米国高級レストラン）が Hostie AI のバーチャルコンシェルジュを導入 |
| どうやって | 電話・SMS・メールでの予約・問い合わせ・更新対応を AI が24時間自動対応 |
| チーム規模 | 既存スタッフ削減なし・AI が追加対応 |
| 使用AIツール | Hostie AI（LLM ベースの飲食特化エージェント） |
| 売上インパクト | 電話予約 **150%増**（AI 導入後）。機会損失の大幅削減 |
| 収益モデル | Hostie は SaaS 月額課金（B2B） |

**社長の事業への応用**
- **飲食事業**：同じ仕組みを自社飲食店に導入できる。LINE Bot + Claude API で「予約受付→確認→リマインド」の完全自動化が可能
- **AI研修事業**：「飲食店でもできる AI 予約自動化」は中小飲食事業者向け研修の具体事例として最適。Hostie の日本版ポジションを取る教材化も検討できる

**ソース**：https://hostie.ai/articles/restaurant-automation-in-2026-complete-guide

---

## ③ 社長の事業に直結する実践AIアイデア 5選

### アイデア1：補助金申請書「AI自動ドラフト生成」SaaS
**対象事業**：補助金支援事業

**具体アクションプラン**
1. Claude API（Sonnet 5）に「事業概要インタビュー形式フォーム」を用意→入力内容から補助金申請書のドラフトを自動生成するシステムを構築（Claude Code で 3〜5 日で MVP 化可能）
2. まず既存クライアント 3 社でベータテスト→改善→月額課金（月 29,800 円/社）のSaaSとして展開
3. 補助金申請の成功率データを蓄積し「AI採択率診断」も有料オプションとして追加

**期待売上インパクト**
- 20社 × 29,800円/月 = **月収59.6万円（年収715万円）**
- 採択成功報酬（採択額の3%）を組み合わせると年収1,500万円超えも視野

---

### アイデア2：陰陽師AIチャット鑑定「LINEミニアプリ」
**対象事業**：陰陽師/占い事業

**具体アクションプラン**
1. LINE ミニアプリ + Claude API で「四柱推命・九星気学チャット鑑定ボット」を構築（開発費：Creative Studio チームで 2〜3 週間）
2. 無料体験（1問まで）→有料鑑定（1,500円/問 または 月額 4,980円 でし放題）へ誘導するフリーミアムモデルを設計
3. X（旧Twitter）・TikTok で「今日の陰陽師的アドバイス」を毎日 AI 生成して投稿 → リンクから LINE に誘導

**期待売上インパクト**
- 登録者 500人 × 月額 4,980円 の転換率 20% = **月収49.8万円（年収597万円）**

---

### アイデア3：飲食店向け「AI予約・問い合わせ自動化 LINE Bot」
**対象事業**：飲食事業 × AI研修事業（研修事例としても活用）

**具体アクションプラン**
1. LINE Official Account + Claude API を使い「予約受付→確認→前日リマインド→満席時キャンセル待ち登録」を自動化するシステムを自社飲食店で構築（CTO が 1 週間で実装可能）
2. 自社店舗で「150%予約増」などの実績データを 3 ヶ月で蓄積する
3. 地域の飲食店向けに横展開：月額 29,800円 での SaaS 販売 or AI研修の実演コンテンツとして売る

**期待売上インパクト**
- 飲食店舗の予約増収（機会損失解消）＋ 10店舗 × 29,800円 = **月収29.8万円の副収益**
- 研修コンテンツ化で 1回 30万円の企業研修としての販売も可能

---

### アイデア4：中小企業向け「AI活用度診断レポート」自動生成サービス
**対象事業**：AI研修事業 × Web制作事業

**具体アクションプラン**
1. 10〜15 問の診断フォームを作成（業種・規模・現在のIT活用状況を入力）→ Claude が「御社に最適なAI活用ロードマップ（PDF）」を自動生成するシステムを構築
2. 無料診断でリード獲得 → 有料研修（1回 30〜50万円）または AI導入支援（月額 15万円〜）への商談化
3. Webサイトのランディングページに無料診断CTAを設置し、Google広告（月 5万円）でトラフィック獲得

**期待売上インパクト**
- 月 50社が診断 → 転換率 10% → 月 5 社の商談 → 成約率 40% → 月 2 件 × 30万円 = **月収60万円（年収720万円）**

---

### アイデア5：Web制作 × マーメイド事業「AI観光体験コンテンツパッケージ」
**対象事業**：Web制作事業 × マーメイド事業

**具体アクションプラン**
1. マーメイド体験のターゲット（女性・子連れファミリー・インバウンド観光客）に特化した多言語 LP を Claude + AI翻訳で自動生成するテンプレートを構築
2. Runway / Kling AI で「マーメイドが水中で踊る」AI動画広告を低コスト（制作費 5,000円以下）で量産し、Instagram・TikTok で配信
3. 予約から体験後のフォトレポート自動送付まで LINE Bot で完結する「感動体験ループ」を設計

**期待売上インパクト**
- AI動画広告によるリーチ拡大でマーメイド体験予約を **月10件→月30件へ増加**（単価 15,000円と仮定 = 月収増 30万円）
- 同パッケージを他の体験事業者に横展開：5社 × 30万円 = **Web制作売上150万円/月**

---

## まとめ：今週の最重要アクション

| 優先度 | アクション | 担当 |
|--------|------------|------|
| 🔴 HIGH | Claude API のコストを 8/31 までに見直す（Sonnet 5 料金改定対応） | CTO |
| 🔴 HIGH | 補助金 AI ドラフト生成 MVP の要件定義を開始（Claude Code で実装） | CTO × COO |
| 🟡 MED | 陰陽師 LINE Bot の企画書作成（Nebula 事例を参考に収益モデル設計） | CPO |
| 🟡 MED | 飲食店 AI 予約 Bot を自社店舗でプロトタイプ実装 | CTO |
| 🟢 LOW | Manus AI の「My Computer」機能を試して AI 研修コンテンツ化を検討 | CTO |

---

次回：明日 7:30 AM

---
*ソース一覧*
- https://releasebot.io/updates/anthropic/claude
- https://9to5mac.com/2026/08/06/openai-updating-chatgpt-with-a-smarter-gpt-5-6-sol-and-unlimited-free-chats/
- https://ai.google.dev/gemini-api/docs/changelog
- https://techcrunch.com/2026/06/30/openclaw-is-finally-available-on-android-and-ios/
- https://www.fm-magazine.com/issues/2026/aug/manus-ai-agent-skills-openclaw-and-more-part-2/
- https://www.forbes.com/sites/josipamajic/2026/04/02/ai-and-20000-helped-one-man-build-a-18-billion-telehealth-startup/
- https://www.indiehackers.com/post/photo-ai-by-pieter-levels-complete-deep-dive-case-study-0-to-132k-mrr-in-18-months-3a9a2b1579
- https://www.buildmvpfast.com/blog/solo-developer-35-micro-saas-apps-77k-month-portfolio-2026
- https://ai.omisoft.net/ai-astrology-app-development-predict-your-success/
- https://hostie.ai/articles/restaurant-automation-in-2026-complete-guide
