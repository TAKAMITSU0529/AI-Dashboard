# AI情報ブリーフィング R8-0818（2026-08-18）
作成：AI Company CTO（技術・AI担当）

---

## ① AIニュース Top5

### 1. Claude Sonnet 5 の価格改定迫る／Claude Code が GitLab 対応へ

**要約：**
Anthropic は Claude Sonnet 5 のプロモーション価格（入力$2・出力$10/百万トークン）を 8月31日で終了し、9月1日から標準価格（$3/$15）へ移行すると発表。同時に Claude Code は GitLab のマージリクエスト対応、セルフホスト型ランナーの高速化、MCP のゲートウェイ・プラグイン検証強化などを追加。Claude Code サブスクライバー向けの週次使用量 50% 増量ボーナスも 8月19日まで延長中。

**重要性：**
- **AI研修事業**：Sonnet 5 を研修コンテンツ自動生成に使っているなら、9月以降のコスト計算を今週中に見直す。月1,000万トークン使用なら月額コスト増は約¥2,000〜4,000円（為替次第）で軽微だが、大量バッチ処理するなら Haiku 4.5 へ切り替えるタイミング。
- **Web制作事業**：Claude Code + GitLab 連携で、クライアントの GitLab リポジトリに直接コード提案・レビューを入れる開発フローが完成。受注単価アップの交渉材料になる。

**ソース：** https://releasebot.io/updates/anthropic/claude · https://releasebot.io/updates/anthropic/claude-code

---

### 2. GPT-5.6 Sol アップデート：「推論の深さ」をスライダーで調整可能に

**要約：**
OpenAI は 8月6日に GPT-5.6 Sol（旧 GPT-5.6）をアップデート。Plus・Pro ユーザーは応答ごとに「どれだけ深く考えるか」のスライダーで推論コストと速度を調整できるようになった。Free・Go ユーザーも新しいデフォルトモデルを利用可能。Google Drive 連携と Mac の「Computer History」機能（過去のアプリ操作をコンテキストに取り込む）も追加。

**重要性：**
- **AI研修事業**：「推論スライダー」という UI 概念は研修の教材になる。生成AI を使いこなすビジネスパーソン向け講座で「なぜ深く考えさせるか・どう切り替えるか」を実習セッション化できる。
- **補助金支援事業**：Google Drive 連携により、クライアントから受け取った補助金申請書類（Docs/Sheets）を直接 ChatGPT に読み込ませて添削・修正が可能に。ワークフロー短縮効果大。

**ソース：** https://aibusinessweekly.net/p/chatgpt-new-features-2026 · https://releasebot.io/updates/openai/chatgpt

---

### 3. Gemini 3.7 Flash & Gemini Omni Flash（動画生成）正式リリース

**要約：**
Google が Gemini 3.7 Flash（コーディング・エージェント・知識業務向け高速モデル・低価格）と Gemini Omni Flash（テキスト・画像・映像・音声から動画クリップを生成・編集できる動画モデル）を正式リリース。Google Classroom へのデモ資料自動生成や、Google Meet の議事録・アクションアイテム自動生成も拡充。

**重要性：**
- **動画デザイン事業**：Omni Flash はテキスト指示だけで映像クリップを生成・編集できる。これまで After Effects 等で行っていた短尺動画制作を AIに任せ、社長は演出ディレクションに集中するフローへ移行できる。制作コスト60〜70%削減の試算が現実的。
- **AI研修事業**：Gemini + Google Classroom の連携でオンライン研修資料（フラッシュカード・小テスト・ガイド）の自動生成が実用段階に。研修SaaS化の核技術として採用候補。

**ソース：** https://releasebot.io/updates/google/gemini · https://www.techrepublic.com/article/news-google-biggest-announcements-2026/

---

### 4. OpenClaw マーケットプレイスに悪意あるスキル 824件発覚、Microsoft が警告

**要約：**
セキュリティ研究者が OpenClaw（Claude Cowork）のスキルマーケットプレイスで 824件の悪意あるスキルを発見。重大な脆弱性も確認されており、Microsoft は「機密データを持つデバイスでは実行しないよう」と公式勧告を出した。一方で Meta AI は Manus ブラウザエージェントと OpenClaw の統合を準備中とも報じられている。

**重要性：**
- **AI研修事業**：これは即・研修コンテンツになる。「AIエージェントのセキュリティリスク」を題材にした中間管理職向け講座の新章を追加できる。実被害ニュースがあると受講者の危機感が高まり成約率向上。
- **補助金支援事業**：クライアントに AI ツール導入を支援する際、マーケットプレイス製スキル・プラグインのリスク評価フローを提案書に入れる。「安全な AI 導入パートナー」としての差別化に直結。

**ソース：** https://thelettertwo.com/2026/06/07/openclaw-microsoft-google-meta-ai-agents · https://local-ai-zone.github.io/blog/ai-updates-august-2026.html

---

### 5. Anthropic「AI for Science」グラント最大$50,000（約750万円相当）開放

**要約：**
Anthropic が希少遺伝病の研究者向けに最大 $50,000 分（6ヶ月）の Claude クレジット無償提供プログラムの申請受付を開始。あわせてオープンソースメンテナー向けに Claude Max 20x（年間約$1,200相当）を6ヶ月無料提供する「Claude for Open Source」も開始。

**重要性：**
- **補助金支援事業**：海外のAIグラント情報を日本の補助金情報と組み合わせた「AI導入支援フルパッケージ」として提案できる。クライアントに「国内補助金＋海外グラント両方を狙う」戦略を提示できる専門家ポジションを取れる。
- **AI研修事業**：Anthropic の無料クレジットを活用した「ハンズオン研修プログラム」として、ランニングコスト0での実習環境提供が可能。他社研修との差別化ポイントになる。

**ソース：** https://blog.mean.ceo/anthropic-claude-news-august-2026/ · https://releasebot.io/updates/anthropic

---

## ② マイクロ法人 × AI活用で大きく稼いでる事例 5選

### 事例1：Pieter Levels（オランダ）— Photo AI で月収₹1,580万円（$132K MRR）

| 項目 | 内容 |
|------|------|
| **誰が** | Pieter Levels（オランダ人ノマドソロファウンダー）|
| **何を** | Photo AI：AIプロフィール写真生成サービス |
| **どうやって** | 2023年2月ローンチ→18ヶ月で$132K MRR。サポートも雇用ゼロ、設計から運営まで1人。X（旧Twitter）で「Building in Public」戦略で200万フォロワーに公開成長 |
| **使用AI** | Stable Diffusion・Dreambooth（学習）+ Stripe（決済）+ Cloudflare（インフラ） |
| **収益** | 月$132,000（約₹1,950万円）MRR。ポートフォリオ全体（RemoteOK・NomadList含む）で年$3.5M ARR（約₹5.2億円） |
| **社長への応用** | **Web制作×AI写真**：法人向けプロフィール写真撮影の代替として「AI社員証写真生成サービス」をアドオン販売。1社5〜10名×¥5,000〜10,000/人 で単価底上げ可能 |

**ソース：** https://ppc.land/how-one-photo-ai-app-generates-132k-monthly-after-70-failed-startups

---

### 事例2：Marc Lou（フランス）— 15商品×月$80K MRR、年間$1.03M

| 項目 | 内容 |
|------|------|
| **誰が** | Marc Lou（フランス人インディーハッカー）|
| **何を** | ShipFast（Next.js スターターキット）・CodeFast（コーディング学習）・DataFast（Analytics）他15商品 |
| **どうやって** | 1商品を1〜2週間でリリース→失敗しても次へ。AIでコード生成・LP文章自動化・デザイン自動化。Twitter/Xで「今日これ作った」を毎日発信 |
| **使用AI** | Claude Code・Cursor・v0（Vercel）・GPT-4o |
| **収益** | 2025年累計$1,032,000（約₹1.5億円）。ShipFastだけで月$20K MRR |
| **社長への応用** | **AI研修事業**：「ShipFast型のAIスターターキット」を研修修了者向けに販売。Web制作を学んだ受講者がすぐ稼げる「AI副業スターターパック（テンプレ＋プロンプト集）¥29,800」で展開 |

**ソース：** https://dev.to/glad_labs/ai-saas-solo-founder-success-stories-2026-startup-journeys-of-solo-developers-who-built-jca

---

### 事例3：Alex（米国）— 35本のマイクロSaaS で月収$77,000（約₹1,150万円）

| 項目 | 内容 |
|------|------|
| **誰が** | Alex（30代・米国在住・ソロ開発者）|
| **何を** | PDF結合・CSV変換・SEOチェッカー・メール検証ツールなど超ニッチなマイクロツール35本 |
| **どうやって** | 「1ツール＝1問題を解決する」に徹する。各ツールの開発期間は平均2週間。Google 検索流入を中心に SEO で集客、課金は月$9〜29のシンプルなサブスク |
| **使用AI** | Cursor + Claude でコード生成、ChatGPT でSEOコンテンツ生成 |
| **収益** | 月$77,000（約₹1,150万円）35本合計 |
| **社長への応用** | **補助金支援事業**：「補助金申請書チェックツール」「事業計画書の採点AIツール」など補助金ニッチに特化したマイクロツールを開発。初期投資¥50,000以内でプロトタイプ可能 |

**ソース：** https://www.buildmvpfast.com/blog/solo-developer-35-micro-saas-apps-77k-month-portfolio-2026

---

### 事例4：Base44チーム（イスラエル）— 6ヶ月で約120億円EXIT

| 項目 | 内容 |
|------|------|
| **誰が** | Base44 創業チーム（イスラエル・少数精鋭） |
| **何を** | AI でウェブアプリを自然言語から自動生成するノーコードプラットフォーム |
| **どうやって** | 「プロンプトを書くだけでフルスタックアプリが完成する」を実現。ターゲットを「コードが書けない起業家・中小企業経営者」に絞る。2024年後半ローンチ、2025年中に約120億円で大手に売却 |
| **使用AI** | Claude API（Anthropic）中心のマルチモデル構成 |
| **収益** | EXIT金額：約120億円（詳細非開示） |
| **社長への応用** | **Web制作事業**：Base44 型の「AI自動サイト生成＋手直し込みセット」をサービスとして設計。クライアントが自然言語で要件を言う→AIが下書き→社長が仕上げる。制作時間を1/5に短縮し、低単価案件の受注量を増やして総売上を上げる |

**ソース：** https://www.matrixflow.net/case-study/150/ · https://genai-ai.co.jp/ai-kanri/blog/cc-ai-earn-money-automation/

---

### 事例5：占星術アプリ市場 — アジア太平洋38%シェア・AI占いアプリの急成長

| 項目 | 内容 |
|------|------|
| **誰が** | Astra・AstroVoice AI など複数スタートアップ（米国・インド中心） |
| **何を** | AIが個人の生年月日・星座・タロットから自動鑑定文を生成する占いアプリ |
| **どうやって** | フリーミアムで集客（月45%のシェア）→プレミアム鑑定・サブスク・ウォレットチャージで収益化。プッシュ通知で毎日「今日の運勢」を配信しDAU維持 |
| **使用AI** | GPT-4o / Claude for long-form reading generation + LLM-backed interpretation engine |
| **収益** | 市場全体：2026年世界$62〜83億（アジア太平洋が38%の最大市場）。個別アプリ：$5K〜$50K MRR が一般的な到達点 |
| **社長への応用** | **陰陽師/占い事業**：AI自動鑑定文生成×LINE公式アカウント配信で「毎朝の今日の運勢」を自動送信。月¥980〜1,980のサブスクで1,000人加入→月収¥98万〜198万円。既存のブランド力がある分、参入コストは低い |

**ソース：** https://www.astrovoice.ai/blog/ai-and-astrology-in-2026-the-fusion-reshaping-cosmic-wisdom-for-everyone/ · https://astrologyapi.com/blog/astrology-app-statistics

---

## ③ 社長の事業に直結する実践AIアイデア 5選

### アイデア1：デジタル化・AI導入補助金2026 × AI研修のセット販売

**対象事業：** AI研修事業 × 補助金支援事業

**背景：**
2026年改正でジェネレーティブAI導入ツールが明示的に補助対象に。最大450万円（補助率1/2〜4/5）の補助金を活用して研修費用も実質無料化できる。

**具体アクション：**
1. **「補助金で実質¥0の AI 研修」LP を作成**（SEO ターゲット：「AI 研修 補助金 愛知」）。Claude で LP 文章を自動生成→Vercel でデプロイ。所要時間：2日
2. **補助金申請代行フィーを研修料金に上乗せ**：研修¥30万＋申請代行¥10万のセット（クライアントは補助後の実質負担¥4〜8万）
3. **申請書類の雛形を Claude で自動生成**するフローをドキュメント化。対応件数を増やす

**期待売上インパクト：** 月3〜5件成約×¥40万＝月¥120〜200万円

**参考：** https://www.btncon.com/blog/digital-ai-subsidy-2026

---

### アイデア2：AI占い × LINE サブスク「陰陽師からの毎朝メッセージ」

**対象事業：** 陰陽師/占い事業

**背景：**
占いアプリ市場はアジア太平洋が世界最大（38%）。フリーミアム→サブスクへの転換が収益の核。既存の陰陽師ブランドを持つ社長は競合より低コストで参入できる。

**具体アクション：**
1. **LINE公式アカウント＋Claude API 連携**：誕生日を登録したユーザーに毎朝 Claude が個人化された「陰陽師からの一言」を自動送信（初期費用¥5〜10万のシステム構築）
2. **月¥980〜1,980のサブスクプラン**を LINE で販売。無料体験7日間で見込み客を確保
3. **月1回のライブ鑑定（Zoom）を特典**として加え、単価¥3,980〜9,800のプレミアムプランへ誘導

**期待売上インパクト：** 500人加入×¥1,980＝月¥99万円（維持コスト：Claude API + LINE 合計¥2〜3万/月）

---

### アイデア3：AI動画サムネイル×ショート動画の量産サービス

**対象事業：** 動画デザイン事業

**背景：**
Gemini Omni Flash でテキスト指示→動画クリップ生成が実用化。YouTube 向けサムネイル＋ショート動画を AI で量産し、中小企業の SNS 担当者が自分でできる「AI 動画制作キット」としてサービス化できる。

**具体アクション：**
1. **「飲食店向け AI 動画月額プラン」**を設計：月5本のショート動画＋サムネイル＋月1本の長尺動画。価格：月¥29,800〜49,800
2. **Gemini Omni Flash + Runway + CapCut API** を組み合わせた自社制作フロー構築（初期セットアップ1週間）
3. **愛知の飲食店 50 軒に DM**で「Instagram 更新代行」として提案。自社の飲食事業との相乗効果でリアルな事例が先に作れる

**期待売上インパクト：** 10社×¥39,800＝月¥39.8万円（横展開で20社なら月¥79.6万円）

---

### アイデア4：補助金申請書 AI 自動生成ツール（マイクロSaaS 展開）

**対象事業：** 補助金支援事業

**背景：**
Alex 事例（35本マイクロSaaS）のように「補助金書類チェック特化ツール」を SaaS 化する。競合の少ないニッチで、Claude API を中核にした B2B ツールは月¥9,800〜29,800 の課金が通りやすい。

**具体アクション：**
1. **MVP 設計**：「事業計画書の文章を入力→補助金審査基準でAIが採点・改善案を出力」1機能のみで構築（Claude API + Next.js + Vercel で2〜3週間）
2. **補助金コンサル事務所・社労士向けに BtoB 販売**：1事務所あたり月¥9,800〜19,800
3. **補助金支援事業の既存クライアントをβテスター**にし、3ヶ月で事例を5件揃えてから公開販売

**期待売上インパクト：** 50社×¥12,800＝月¥64万円（ストック収入）

---

### アイデア5：AI研修「マイクロ法人×AI収益化」コース新設

**対象事業：** AI研修事業

**背景：**
「AIで副業・マイクロ法人で稼ぐ」というニーズは急増中。Photo AI・Marc Lou・マイクロSaaS 等の具体事例を使い、「愛知でAI副業を始めたい会社員・個人事業主」向けの週末集中コースを設計できる。

**具体アクション：**
1. **「AIで月収30万円を目指す！週末マイクロ法人コース」**（2日間・¥49,800〜79,800）を設計。Claude Code・Cursor・Vercel の実習付き
2. **地元商工会議所・愛知県産業労働センター経由**でセミナー告知。補助金で費用カバーできる旨を明記して集客
3. **卒業生コミュニティ（Discord）**を作り、¥2,980/月のサブスクで継続課金。成功事例が出たらLPに掲載→SNS拡散

**期待売上インパクト：** 月2回開催×15名×¥59,800＝月¥179.4万円＋コミュニティ収入

---

## まとめ・本日のアクション優先度

| 優先度 | アクション |
|--------|-----------|
| 🔴 今週中 | Claude Sonnet 5 の9月以降コスト試算。API使用量確認→Haiku 4.5 切替判断 |
| 🔴 今週中 | デジタル化・AI導入補助金2026（最大450万）の申請期限を確認→クライアントへ案内メール準備 |
| 🟡 今月中 | 陰陽師 LINE サブスクのプロトタイプ設計（Claude API + LINE 連携） |
| 🟡 今月中 | AI動画量産フロー（Gemini Omni Flash）の社内テスト |
| 🟢 来月以降 | 補助金申請書チェックツール MVP 設計着手 |

---

次回：明日 7:30 AM

---

*ソース一覧：*
- https://releasebot.io/updates/anthropic/claude
- https://releasebot.io/updates/anthropic/claude-code
- https://aibusinessweekly.net/p/chatgpt-new-features-2026
- https://releasebot.io/updates/openai/chatgpt
- https://releasebot.io/updates/google/gemini
- https://www.techrepublic.com/article/news-google-biggest-announcements-2026/
- https://thelettertwo.com/2026/06/07/openclaw-microsoft-google-meta-ai-agents
- https://blog.mean.ceo/anthropic-claude-news-august-2026/
- https://ppc.land/how-one-photo-ai-app-generates-132k-monthly-after-70-failed-startups
- https://dev.to/glad_labs/ai-saas-solo-founder-success-stories-2026-startup-journeys-of-solo-developers-who-built-jca
- https://www.buildmvpfast.com/blog/solo-developer-35-micro-saas-apps-77k-month-portfolio-2026
- https://www.matrixflow.net/case-study/150/
- https://www.astrovoice.ai/blog/ai-and-astrology-in-2026-the-fusion-reshaping-cosmic-wisdom-for-everyone/
- https://www.btncon.com/blog/digital-ai-subsidy-2026
