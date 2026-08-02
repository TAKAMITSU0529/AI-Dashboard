# AI情報ブリーフィング R8-0803（2026-08-03）
作成：AI Company CTO（技術・AI担当）

---

## ① AIニュースTop5

### 1. GPT-5.6の大幅値下げ：Luna -80%、Terra -20%（OpenAI）
**要約**：OpenAIは7月30日、GPT-5.6ファミリーの価格を大幅に引き下げ。Luna（高速型）が80%減、Terra（バランス型）が20%減。3バリアント（Luna / Terra / Sol）のうち最強のSolはコーディング・知識業務・サイバーセキュリティで最高スコアを達成。ChatGPT Voiceも業務ツール・Codexと統合された。
**重要性**：API経由でGPT-5.6 Lunaを活用したAI研修コンテンツ生成・Web制作自動化ツールの運用コストが激減。**AI研修・Web制作**事業で、LLM（大規模言語モデル）を使った自社ツール開発のコスト障壁がほぼゼロになるタイミング。今すぐGPT-5.6 Luna採用を検討すべき。
**ソース**：https://openai.com/index/gpt-5-6/ / https://techcrunch.com/2026/07/09/openai-launches-its-new-family-of-models-with-gpt-5-6/

---

### 2. Google Gemini Sparkがアジア太平洋へ展開（Google）
**要約**：Googleの自律型AIエージェント「Gemini Spark」が8月1日よりアジア太平洋地域のGoogle AI Ultraサブスクリプション向けに展開開始。数週間内にAI Proへも拡大予定。Sparkは独立して複数ステップのタスクを自律実行し、Google Workspace・Chrome・対応サードパーティアプリをまたいで動作する。
**重要性**：日本語対応が確認されれば、**AI研修**事業の新コンテンツ（「Gemini Sparkを使った業務自動化研修」）の商材化チャンス。また**Web制作**の提案にGemini Spark連携を加えると差別化になる。Google AI Ultraを契約して即検証推奨。
**ソース**：https://newsbytes.ph/2026/08/01/google-expands-gemini-spark-ai-agent-to-asia-pacific/

---

### 3. Claude Sonnet 5の価格が9月から変更・Claude for Open Source開始（Anthropic）
**要約**：Claude Sonnet 5のプロモーション価格（$2/$10 per million tokens）が8月31日終了、9月1日から標準価格（$3/$15）へ。一方でAnthropicはオープンソースコントリビューター向けに6ヶ月分の無料Claude Max 20x（約$1,200相当）を提供する「Claude for Open Source」を開始。Claude CodeユーザーへのWeekly使用量50%増加ボーナスも8月19日まで延長。
**重要性**：Claude APIを使う**CTO（自社自動化）・Web制作**ツールのコスト計算を8月中に見直す。Claude for Open Sourceはオープンソースプロジェクトを持つ**CTO**への好機。Claude Codeの使用量ボーナスを8月19日までに最大限活用する。
**ソース**：https://www.anthropic.com/news / https://claudelog.com/claude-news/ / https://releasebot.io/updates/anthropic/claude

---

### 4. OpenClaw 2026.6大型アップデート：信頼性・MCP拡張・ローカル推論強化
**要約**：OpenClawがデータ安全性・クラッシュリカバリ・セッション巻き戻し・ブランチ機能・強化されたMCPアプリ対応・ローカル推論のサポートを含む大型アップデートをリリース。月次の「extended-stable」リリース体制も確立（最初のリリースはOpenClaw 2026.6.33）。
**重要性**：AI Companyが採用しているOpenClawの安定性と機能が大幅向上。MCPアプリの拡張により、**Web制作・補助金支援・AI研修**での自動化フローが一段と強化できる。MCP接続ツールの棚卸しと、新しいMCPアプリの調査を実施する好機。
**ソース**：https://releasebot.io/updates/openclaw

---

### 5. デジタル化・AI導入補助金2026：生成AI活用が新たに補助対象化（経済産業省）
**要約**：2026年度より「デジタル化・AI導入補助金」（旧IT導入補助金）が改訂。生成AI活用システムが補助対象として明確化。1事業者最大450万円（補助率1/2〜4/5）が支援される。IT導入支援事業者を通じた申請が必要で、申請受付はすでに開始済み。
**重要性**：**補助金支援**事業の主力商材。「AI導入補助金を活用したChatGPT・Claude API連携システム導入」という切り口でのコンサルパッケージは今最も売りやすい商品。IT導入支援事業者の登録状況確認と、支援事例の整備を急ぐ。
**ソース**：https://mirasapo-plus.go.jp/infomation/32009/ / https://www.chusho.meti.go.jp/koukai/hojyokin/kobo/2026/260310001.html

---

## ② マイクロ法人 × AI活用で大きく稼いでる事例 5選

### 1. Pieter Levels（オランダ・個人）：Photo AI で月$105K（約1,600万円）を1人で運営
- **誰が**：Pieter Levels（@levelsio）、オランダ人。独学フルスタック開発者
- **何を**：PhotoAI.com — AIが本人の写真から本格的なプロフィール写真を生成するサービス
- **どうやって**：単一の40,870行PHPファイル、Hetznerの専用サーバー1台。1人で開発・運営。外注・チームなし
- **何を活用したか**：Stable Diffusion（画像生成AI）、Replicate.com（AIモデルホスティング）、PHP + 独自コード
- **どのように稼いだか**：月収$105,000（約1,600万円）、利益$80,000（約1,200万円）。有料プランのサブスクリプション課金。全ポートフォリオで年$3M超（約4.6億円）
- **社長の事業への応用**：**陰陽師・占い**事業で「生年月日・名前から開運写真・守護神フォト」生成AIを展開可能。**Web制作**でクライアント向けAI写真生成サービスを付加価値として追加できる
- **ソース**：https://levels.io/photoai-40870-line-index-php-105k-mo-revenue / https://www.fast-saas.com/blog/pieter-levels-success-story/

---

### 2. Danny Postma（オランダ・個人）：HeadshotProで月$300K（約4,600万円）
- **誰が**：Danny Postma、オランダ人。バリ在住のインディーハッカー
- **何を**：HeadshotPro.com — 数枚のセルフィーから120枚以上のプロフィール写真を生成するAIサービス
- **どうやって**：2023年3月16日に公開、2週間で$100K到達。完全ソロ。コードはAI支援開発
- **何を活用したか**：Stable Diffusion API、独自ファインチューニング（LoRA）、Stripe決済
- **どのように稼いだか**：月$300,000（約4,600万円）、年$3.6M（約5.5億円）。有料写真パック販売（1回決済 or サブスク）
- **社長の事業への応用**：**Web制作**事業のクライアント（士業・コンサル・美容師・飲食）に「プロフィール写真AIパック」を月額オプションで追加できる。愛知県内中小企業のBtoB向けで差別化になる
- **ソース**：https://aibusiness.vc/solo/headshot-pro-300k-month / https://greyjournal.net/hustle/grow/solo-founders-million-dollar-ai-businesses-2026/

---

### 3. Marc Lou（フランス・個人）：SaaSポートフォリオで月$81K（約1,240万円）
- **誰が**：Marc Lou、フランス人インディーハッカー
- **何を**：ShipFast（SaaSボイラープレート）・CodeFast・DataFastなど15本のSaaSポートフォリオ
- **どうやって**：高速ビルド＋公開（Building in Public）で毎月1〜2本リリース。累計$2.26M超を突破
- **何を活用したか**：Next.js、Cursor（AIコーディング）、Claude / GPT-4 for content、Stripe、Lemon Squeezy
- **どのように稼いだか**：2026年2月収入$81,683（自己申告）。主力ShipFastとCodeFastが各$20K/月。テンプレート販売（買い切り）とサブスク併用
- **社長の事業への応用**：**AI研修**事業で「AIを使った副業SaaS構築講座」コンテンツを組める。Marc Louのモデルを日本語で解説する研修商品は市場に少ない
- **ソース**：https://indieai.directory/blog/marc-lou-81683-february-2026-income-breakdown/ / https://www.indiehackers.com/post/what-marc-lou-s-1m-year-reveals-about-solo-saas-compounding-Kd7SbxGXTYn5gMdfoY8R

---

### 4. Maor Shlomo（イスラエル・個人）：Base44を6ヶ月で構築→Wixへ$80M売却
- **誰が**：Maor Shlomo、イスラエル人ソロ創業者
- **何を**：Base44 — ノーコードでWebアプリを自然言語から作れるAIプラットフォーム
- **どうやって**：Claude + GPT-4を組み合わせてプロダクトを構築。ソロで6ヶ月でユーザー25万人達成・黒字化
- **何を活用したか**：Anthropic Claude API、OpenAI GPT、独自UIエンジン
- **どのように稼いだか**：黒字化後2025年6月にWixへ$80M（約123億円）で売却
- **社長の事業への応用**：**補助金支援**事業で「ノーコードAIツールを使った業務効率化」をクライアントに提案する際の最強事例として使える。**AI研修**でもBase44の事例は受講者のモチベーションを上げる実例になる
- **ソース**：https://greyjournal.net/hustle/grow/solo-founders-million-dollar-ai-businesses-2026/ / https://widejournal.com/business/entrepreneurship/ai-solopreneur-one-person-business-2026/

---

### 5. 匿名ソロ開発者（米国・個人）：35本のMicro SaaSで月$77K（約1,180万円）
- **誰が**：30代男性ソロ開発者（buildmvpfast.comで事例公開）、米国在住
- **何を**：35本のニッチMicro SaaSアプリポートフォリオ（各$2,000〜$5,000 MRR）
- **どうやって**：1日4〜6時間の集中開発。スマホOFF。ベーシックなコードエディタ + AIチャット1本。スタックは最小限
- **何を活用したか**：Cursor（AIコーディング）、Claude、基本的なWebフレームワーク、Stripe
- **どのように稼いだか**：単月$77,000（約1,180万円）。各アプリが小さくても積み上げで大きな収益。運営コストは月$500以下
- **社長の事業への応用**：**陰陽師・占い**や**飲食**など各事業に特化したニッチAIツール（例：「飲食店の原価計算AI」「占い師向けクライアント管理AI」）を5〜10本スタックさせるモデルとして参考にできる
- **ソース**：https://www.buildmvpfast.com/blog/solo-developer-35-micro-saas-apps-77k-month-portfolio-2026

---

## ③ 社長の事業に直結する実践AIアイデア 5選

### アイデア1：「デジタル化・AI導入補助金パック」を主力商品化
- **対象事業**：補助金支援
- **具体アクションプラン**：
  1. IT導入支援事業者の登録状況を今週中に確認。未登録なら申請着手（登録費用0円）
  2. 補助対象の「生成AIシステム導入パッケージ」を3プラン（50万・100万・200万円）で設計。Claude API or GPT-5.6 Luna活用の業務効率化ツールを成果物として設定
  3. 既存クライアント（C&Yスポーツ・ルーツオート等）へ提案。「補助金で実質負担0〜半額」で売りやすい
- **期待売上インパクト**：1件100万円サポート費（補助金額の10〜15%が相場）× 月3件 = **月30万〜45万円**

---

### アイデア2：愛知県中小企業向け「AI導入研修パッケージ（補助金対応版）」
- **対象事業**：AI導入研修 × 補助金支援
- **具体アクションプラン**：
  1. 「AI研修費用もデジタル化・AI導入補助金の対象になる」という切り口でLP（ランディングページ）を作成
  2. 研修内容：半日×3回（ChatGPT基礎・Claude業務活用・自動化ツール実践）、1社15万円→補助後7.5万円の価格設定
  3. 愛知県商工会議所・中小企業診断士ネットワークへアプローチして紹介パートナー化
- **期待売上インパクト**：15万円×月5社 = **月75万円**（補助金利用で成約率向上）

---

### アイデア3：「AI陰陽師 × 開運フォト生成」デジタル商品
- **対象事業**：陰陽師・占い
- **具体アクションプラン**：
  1. Stable Diffusion + Replicate APIで「名前・生年月日・干支入力 → パーソナル守護神・開運護符画像生成」の仕組みをClaude APIで設計（Pieter Levelsのモデル参考）
  2. note・BASE・Stripeで「開運フォトパック 5,000円」として販売開始。X（旧Twitter）で「AI陰陽師」キャラクターを立ててコンテンツ発信
  3. 月1回の「個別AI鑑定」ZOOMセッション（29,800円）をアップセルに設定
- **期待売上インパクト**：フォトパック100件×5,000円 + ZOOMセッション10件×29,800円 = **月80万円**

---

### アイデア4：「Web制作 × AI写真撮影不要パック」で単価アップ
- **対象事業**：Web制作
- **具体アクションプラン**：
  1. HeadshotPro型の「プロフィール写真AI生成」をWeb制作パッケージに同梱（スマホ数枚でOK → 120枚の本格写真生成）。Replicate APIで実装コスト1件$5以下
  2. Web制作基本パック +3万円のオプション「AIプロフィール写真生成」として提供。既存クライアントへも単品販売
  3. 「撮影費0円・移動時間0円・当日修正OK」をウリにLPとSNS発信
- **期待売上インパクト**：+3万円×月10件 = **月30万円の上乗せ**

---

### アイデア5：Gemini Sparkを活用した「AI業務代行サービス」の試験提供
- **対象事業**：AI研修 × COO（業務効率化）
- **具体アクションプラン**：
  1. Google AI Ultraを契約してGemini Sparkを即日検証。「Googleカレンダー調整・Gmail返信・Driveファイル整理」の自動化デモを社内で作成
  2. 既存クライアント（飲食・リフォーム系）に「月3万円のAI業務代行トライアル」として提案。Gemini Sparkで週次レポート・問い合わせ対応・スケジュール管理を代行
  3. 効果測定（月間削減時間・削減コスト）を数字で出し、3ヶ月後に月額10万円コースへアップセル
- **期待売上インパクト**：月3万円×10社スタート = **月30万円**。半年で月額10万円×10社 = **月100万円**

---

## 今週の最優先アクション（社長判断用）

| 優先度 | アクション | 期限 |
|--------|-----------|------|
| ★★★ | デジタル化・AI導入補助金の支援事業者登録状況確認 | 今週中 |
| ★★★ | Claude Code使用量ボーナス（+50%）を8月19日までに最大活用 | 8月19日まで |
| ★★ | Google AI Ultra契約・Gemini Spark日本語検証 | 今週 |
| ★★ | GPT-5.6 Luna（-80%値下げ）でのAPI活用コスト再計算 | 今週 |
| ★ | AI陰陽師デジタル商品の企画案をCPOと詳細化 | 来週まで |

---

次回：明日 7:30 AM
