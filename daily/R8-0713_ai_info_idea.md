# AI情報ブリーフィング R8-0713（2026-07-13）
作成：AI Company CTO（技術・AI担当）

---

## ① AIニュース Top5

### 1. OpenAI「ChatGPT Work」正式ローンチ ── 数時間作業を自律完遂するエージェント

**要約**
2026年7月9日、OpenAIが「ChatGPT Work」を正式リリース。ユーザーが目標を設定するだけで、Slack・Google Drive・CRM等のアプリを横断し、スプレッドシート・スライド・ドキュメント・Webアプリなどの「完成した成果物」を数時間かけて自律生成する。GPT-5.6（Sol）エンジンを搭載し、ReAct（推論＋実行）フレームワークで段階的にタスクを分解・完遂する。

**重要性（事業紐づけ）**
- **Web制作**：クライアントへの提案書・競合調査レポートを ChatGPT Work に投げ、社長は確認・修正のみで完結 → 制作リードタイム30〜50%短縮
- **AI研修**：「こんなエージェントが出ました」と即テーマにできる超具体的な教材。受講者の「え、本当に動くの？」という感動体験を研修に組み込める
- **補助金支援**：申請書下書きをChatGPT Workに生成させ、人間が最終確認するワークフローが現実的に

**ソース**
- [OpenAI Launches ChatGPT Work Agent to Handle Complex Tasks - Bloomberg](https://www.bloomberg.com/news/articles/2026-07-09/openai-unveils-chatgpt-work-agent-to-field-tasks-for-hours)
- [ChatGPT Work: OpenAI's Agent That Ships Finished Work](https://www.digitalapplied.com/blog/chatgpt-work-openai-agent-launch-2026)

---

### 2. Anthropic「Claude Reflect」ダッシュボード公開 ── AI利用を可視化する新機能

**要約**
Anthropicが「Reflect」をベータ公開。自分のClaudeの使用パターン（どんなトピックを扱ったか、利用頻度、得意タスク傾向）を可視化するダッシュボード。Free・Pro・Max全ユーザー（メモリON）が利用可能。同時に、Anthropicの研究者がClaudeの内部に「言葉にする前に概念を保持・操作する小さなワークスペース」が存在することを発見し、意識に近い構造との類似性を報告。

**重要性（事業紐づけ）**
- **AI研修**：「AIは本当に理解しているのか？」という受講者の疑問に、最新の一次情報で応えられる。意識研究の話題は研修の掴みとして最強クラス
- **Web制作・陰陽師**：Reflectを使って「どの指示で質が上がるか」のPDCAを記録し、プロンプト資産を蓄積できる

**ソース**
- [Anthropic's new Claude feature is quietly selling you on AI | TechCrunch](https://techcrunch.com/2026/07/09/anthropics-new-claude-feature-is-quietly-selling-you-on-ai/)
- [Anthropic says Claude has carved out its own space to ponder](https://www.axios.com/2026/07/06/anthropic-claude-ai-conscious)

---

### 3. Claude Sonnet 5 がデフォルトモデルに昇格 ＋ Claude Cowork がWeb・モバイル展開

**要約**
2026年7月1日よりClaude Sonnet 5がFree・Pro全ユーザーのデフォルトに。旗艦モデルOpus 4.8に近い性能をより低価格で提供（8月末まで割引価格）。同時に、Claude Cowork（デスクトップアプリ）がMaxサブスクライバー向けにWebおよびモバイルで利用可能になり、「PCで指示→スマホで途中確認→完了後に受け取り」のフローが実現。

**重要性（事業紐づけ）**
- **全事業共通**：Sonnet 5へのアップグレードでコスト増なしに生産性向上。今すぐAPIコールのモデルIDを`claude-sonnet-5`に更新するだけで恩恵を受けられる
- **飲食・マーメイド**：外出中にスマホからCoworkでタスク投げ、PC不要で店舗オペレーション改善のドキュメントを自動生成

**ソース**
- [Claude Cowork expands to mobile and web | TechCrunch](https://techcrunch.com/2026/07/07/the-coding-agent-wars-are-spilling-into-the-rest-of-the-office-claude-cowork/)
- [Anthropic will make Claude Cowork available to users via the cloud](https://www.nbcnews.com/tech/tech-news/anthropic-will-make-claude-cowork-available-users-cloud-rcna353218)

---

### 4. OpenAI「GPT-5.6」ファミリー（Sol / Terra / Luna）とマルチエージェント加速

**要約**
OpenAIがGPT-5.6ファミリーをリリース。旗艦「Sol」、汎用「Terra」、コスト最適「Luna」の3モデル体制。最大の革新は「Ultra Mode」──単一エージェントを超え、サブエージェント群が並列稼働して複雑タスクを加速する。ChatGPT Plusで7月10日から提供開始、Teamプランは1.5Mトークンコンテキスト対応。

**重要性（事業紐づけ）**
- **Web制作**：Lunaで低コストな量産タスク、Solで高品質な提案書・設計 と使い分けることでコスト効率が最大化
- **AI研修**：「マルチエージェント」の概念を最新事例として教えられる。Ultra Modeのデモは研修の目玉コンテンツになる

**ソース**
- [OpenAI releases GPT-5.6 and ChatGPT Work tool](https://www.axios.com/2026/07/09/ai-openai-gpt-release)
- [OpenAI July 2026: GPT-5.6 Release, ChatGPT Updates and AI News](https://llmmac.com/blog/articles/2026-openai-july-gpt-5-6-chatgpt-updates-ai-news.html)

---

### 5. Google「Gemini Enterprise Agent Platform」ローンチ ＋ Google検索がGemini 3.5 Flash全面移行

**要約**
GoogleがVertex AIを進化させた「Gemini Enterprise Agent Platform」を発表。Salesforce・ServiceNow・Oracle・Adobe・Workdayとのパートナーエコシステムで、業務横断エージェントが実現。同時に、Google検索がGemini 3.5 Flashによる「AIサマリーページ」に全面移行し、従来のリンクリスト形式が廃止される方向へ。

**重要性（事業紐づけ）**
- **Web制作・補助金**：Google検索のAI化でSEO戦略が根本変化。クライアントへの「AI時代のSEO」説明・提案が急務。対策としてAIO（AI最適化）コンテンツ設計を今すぐ商品化できる
- **AI研修**：Google検索の変化は中小企業経営者に最も刺さる危機感ネタ。「SEOが死ぬ」訴求で研修の問い合わせを集められる

**ソース**
- [AI News - July 2026: Key Events & Releases](https://dentro.de/ai/news/)
- [Google updates its Gemini app to take on ChatGPT and Claude at IO 2026 | TechCrunch](https://techcrunch.com/2026/05/19/google-updates-its-gemini-app-to-take-on-chatgpt-and-claude-at-io-2026/)

---

## ② マイクロ法人 × AI活用で大きく稼いでる事例 5選

### 事例1：Pieter Levels（オランダ・ソロ開発者） ── AI × SaaS × 建て公方でARR 3.5億円

| 項目 | 内容 |
|------|------|
| 誰が | Pieter Levels（オランダ、30代、ソロ開発者） |
| 何を | Photo AI（AIヘッドショット）・InteriorAI・RemoteOK など40+プロダクト |
| どうやって | SNS（X/Twitter）で10年間「建て公方（Build in Public）」。40+プロダクトを公開しながら失敗→学習を繰り返し、Photo AIが7ヶ月でPMF（製品市場適合）達成 |
| 使用AIツール | Stable Diffusion API・Replicate・Stripe・Vercel・自作PHPスタック |
| 稼ぎ | Photo AI 月138K USD（約2,000万円）・全体ARR $3.5M（約5.2億円）・利益率90%超・従業員ゼロ |
| **社長の事業への応用** | **AI研修**：「一人でARR5億」の実例として最強の訴求素材。愛知の中小経営者に「うちでもできる」と思わせる具体性がある。Photo AIと同じ構造（ニッチ×AI自動化×SNS集客）を補助金支援や陰陽師/占い分野でも展開可能 |

ソース：[How Pieter Levels Built a $3.5M AI Empire as a Solo Developer](https://filenux.com/news/how-pieter-levels-built-a-3-5m-ai-empire-as-a-solo-developer/)

---

### 事例2：Nick Dobos（米国・インディーハッカー） ── 100+AIツールサイトでARR 88億円相当

| 項目 | 内容 |
|------|------|
| 誰が | Nick Dobos（米国、自称インディーハッカー） |
| 何を | BoredHumans.com ── AI生成ツール100+を1ドメインに集積 |
| どうやって | AIジェネレーター・チャットボット・遊べるツールを量産→オーガニックSEOで数百万PV/月。広告収益型 |
| 使用AIツール | OpenAI API・各種生成AI API・Google AdSense |
| 稼ぎ | 月~$733K（約1.1億円）・ARR ~$8.8M（約13億円）相当 |
| **社長の事業への応用** | **Web制作**：クライアント向けに「無料AIツールを集めたポータル」をオマケとして設置し、SEOを稼ぐ設計がそのまま転用可能。陰陽師/占い事業では「無料占いツール集」サイトでリード獲得→有料鑑定に誘導するファネルが組める |

ソース：[AI SaaS Solo Founder Success Stories (2026)](https://crazyburst.com/ai-saas-solo-founder-success-stories-2026/)

---

### 事例3：イスラエル人ソロファウンダー（Base44） ── 6ヶ月でWixに約120億円で売却

| 項目 | 内容 |
|------|------|
| 誰が | イスラエルのソロ開発者（公開情報の範囲内） |
| 何を | Base44 ── ノーコードAIアプリ開発プラットフォーム |
| どうやって | 一人でMVP開発→PMF→6ヶ月でWixに買収提案受諾 |
| 使用AIツール | Claude API・OpenAI API・自社構築ノーコードエンジン |
| 稼ぎ | EXIT額 $80M（約120億円）・買収時MRR $189K（約2,800万円）・ARR $3.5M（約5.2億円） |
| **社長の事業への応用** | **AI研修・補助金**：「AI×ノーコード×ニッチSaaS」は愛知の中小製造業・飲食業でも再現可能。補助金でノーコードツール導入支援＋AI研修をセット提案する「伴走型AIシステム化支援」プランに落とし込める |

ソース：[生成AIを活用した一人社長ってぶっちゃけどうなの？ - MatrixFlow](https://www.matrixflow.net/case-study/150/)

---

### 事例4：Marc Lou（フランス・ソロ起業家） ── 10+マイクロSaaSでMRR 80万円

| 項目 | 内容 |
|------|------|
| 誰が | Marc Lou（フランス、ソロプレナー） |
| 何を | ShipFast（Next.jsボイラープレート）・Zap等10+マイクロSaaS |
| どうやって | Xで「毎週1プロダクト」ペースで公開→バイラル→$49〜$199の買い切り販売 |
| 使用AIツール | Claude Code・Cursor・Vercel・Stripe・Supabase |
| 稼ぎ | MRR ~$80K（約1,200万円）・1製品あたり粗利率95%超 |
| **社長の事業への応用** | **Web制作**：ShipFastと同じ「制作テンプレート販売」を愛知・東海地域のWeb制作会社向けに展開。「地域ビジネス特化のNext.js＋AI組み込みテンプレ」を5〜10万円で販売するマイクロSaaSを立ち上げられる |

ソース：[Solo Dev 35 Micro SaaS Apps $77K Month: Case Study](https://www.buildmvpfast.com/blog/solo-developer-35-micro-saas-apps-77k-month-portfolio-2026)

---

### 事例5：Bhanu Teja（インド・IIT出身） ── SiteGPT でエンタープライズ市場を攻略

| 項目 | 内容 |
|------|------|
| 誰が | Bhanu Teja（インド、IIT Madras卒、24歳時に起業） |
| 何を | SiteGPT ── 企業独自データで訓練するカスタムAIチャットボットSaaS |
| どうやって | 「汎用チャットボットはニーズに合わない」という中小企業の痛点を直撃。ノーコードでチャットボット設置→月額課金 |
| 使用AIツール | OpenAI API・自社ファインチューニング基盤・Intercom連携 |
| 稼ぎ | PMF後に急成長（具体的MRRは非公開だが、2026年時点でエンタープライズ契約複数）・VC調達なし |
| **社長の事業への応用** | **AI研修・Web制作**：中小飲食店・美容院・士業向けに「あなたのお店専用AIチャットボット月3万円」サービスを横展開。補助金（IT導入補助金）を組み合わせて初期費用ゼロ提案が可能。愛知の士業・リフォーム会社が主要ターゲット |

ソース：[AI SaaS Solo Founder Success Stories (2026)](https://dev.to/glad_labs/ai-saas-solo-founder-success-stories-2026-startup-journeys-of-solo-developers-who-built-jca)

---

## ③ 社長の事業に直結する実践AIアイデア 5選

### アイデア1：「Google検索AI化対応」AIO（AI最適化）コンテンツ制作サービス
**対象事業**：Web制作・AI研修

**背景**：Google検索がGemini 3.5 Flashで「リンクリスト→AIサマリーページ」に全面移行。SEO概念が根本的に変わるため、愛知の中小企業は今すぐ対応が必要。

**具体アクションプラン**
1. 「AIO（AI最適化）診断レポート」を1社15,000円で販売（既存クライアントに即アップセル）
2. Claude/ChatGPT WorkでAI検索に引っかかる「構造化コンテンツ＋FAQ形式」ページを月次制作するサブスクプランを月5万円で提供
3. 同内容をAI研修の新単元「AI時代のSEO実践」として12,000円/人で提供

**期待売上インパクト**
- 既存Webクライアント10社にAIO診断即販売 → 15万円（単発）
- 月次サブスク5社獲得 → 月25万円 → 年300万円
- AI研修追加単元 月2回開催×10名 → 月24万円

**合計概算：年間350〜400万円のアップサイド**

---

### アイデア2：ChatGPT Work × 補助金申請書自動生成サービス
**対象事業**：補助金支援

**背景**：ChatGPT Workが「目標を入れると数時間で完成ドキュメントを吐き出す」機能になった。補助金申請書（事業計画書）の初稿生成が劇的に効率化できる。

**具体アクションプラン**
1. 顧客のヒアリングシート（事業内容・強み・投資内容）をGoogleフォームで収集
2. ChatGPT Workに「補助金申請書テンプレ＋ヒアリング内容」を投入し初稿を自動生成（所要時間2〜3時間→人間の確認30分）
3. 仕上げ・提出代行を1件8万〜15万円で提供（現行価格から値上げ余地あり）

**期待売上インパクト**
- 月4件対応 → 月32万〜60万円
- 作業時間を従来比60%削減 → 利益率が30%→70%に改善
- **年間売上 380〜720万円**（一人でも対応可能な上限まで拡大）

---

### アイデア3：陰陽師/占い事業向け「AI鑑定下書き」プロダクト化
**対象事業**：陰陽師/占い

**背景**：占い鑑定文の80%はパターン化できる。Claude Sonnet 5に個人情報（生年月日・質問）を渡してカスタム鑑定文を生成→人間が感情・温かみを上乗せして納品するハイブリッドモデル。

**具体アクションプラン**
1. 過去の鑑定文50件をClaude に学習させ「鑑定文プロンプトテンプレ」を完成させる（作業：1〜2日）
2. Notion + Claude APIで「お客様情報入力→鑑定文下書き自動生成」のフォームを構築
3. 鑑定単価を現行の1.5〜2倍に設定しても受注できる品質にして、月対応件数を3倍に

**期待売上インパクト**
- 月対応件数：現行の3倍
- 単価維持のまま件数増でも → 月売上2〜3倍
- **年間+120〜200万円のアップサイド**（鑑定単価×件数による）

---

### アイデア4：飲食店向け「AI × メニュー最適化＋SNS自動投稿」月額パッケージ
**対象事業**：飲食

**背景**：飲食事業でのAI活用が最も費用対効果が高いのは「メニュー説明文×SNS投稿量産」。Claude Coworkのモバイル対応で、厨房からスマホで指示を出してSNS投稿を自動生成できる時代に。

**具体アクションプラン**
1. 週1回、食材・原価・売れ筋データをClaudeに投入→「今週のおすすめメニュー文案＋Instagram投稿3本＋Google Business更新文」を自動生成
2. Instagram・TikTok・Googleビジネスへの投稿をn8n＋各APIで自動化
3. 愛知の飲食店（自店舗以外）に月2.5万円のサブスクで横展開

**期待売上インパクト**
- 自店舗コスト削減効果：月5〜10万円分の人件費削減
- 外部販売：愛知5店舗獲得 → 月12.5万円 → **年150万円**

---

### アイデア5：水回りリフォーム × AI見積自動化＋LINE Bot 集客パッケージ
**対象事業**：水回りリフォーム

**背景**：リフォーム業の問い合わせ対応・見積作成は最も時間を食う工程。LINE Bot＋Claudeで「写真を送るだけでAI概算見積→翌日訪問アポ確定」の仕組みを作れる。

**具体アクションプラン**
1. LINE Official Account＋Claude API連携で「写真送信→部位判定→概算見積提示→アポ日程調整」Botを構築（初期制作費：Claude Code活用で2〜3日）
2. 愛知の水回りリフォーム会社5〜10社に月3万円のSaaS型サービスとして販売
3. 初期設定費+月額モデル（初期15万円＋月3万円）で、IT導入補助金の対象として提案

**期待売上インパクト**
- 10社獲得 → 月30万円サブスク収益
- IT導入補助金対象でクロージング率UP（補助後の顧客負担：月1.5万円）
- **年間360万円 ＋ 初期費収入150万円 = 年510万円**

---

次回：明日 7:30 AM

---
*情報ソース一覧*
- [OpenAI ChatGPT Work Launch](https://www.bloomberg.com/news/articles/2026-07-09/openai-unveils-chatgpt-work-agent-to-field-tasks-for-hours)
- [ChatGPT Work: Agent That Ships Finished Work](https://www.digitalapplied.com/blog/chatgpt-work-openai-agent-launch-2026)
- [Claude Reflect / TechCrunch](https://techcrunch.com/2026/07/09/anthropics-new-claude-feature-is-quietly-selling-you-on-ai/)
- [Anthropic Claude Consciousness Research](https://www.axios.com/2026/07/06/anthropic-claude-ai-conscious)
- [Claude Cowork Mobile & Web / TechCrunch](https://techcrunch.com/2026/07/07/the-coding-agent-wars-are-spilling-into-the-rest-of-the-office-claude-cowork/)
- [GPT-5.6 Release / Axios](https://www.axios.com/2026/07/09/ai-openai-gpt-release)
- [Gemini Enterprise Platform / dentro.de](https://dentro.de/ai/news/)
- [Pieter Levels $3.5M Solo Empire](https://filenux.com/news/how-pieter-levels-built-a-3-5m-ai-empire-as-a-solo-developer/)
- [AI SaaS Solo Founder Stories 2026](https://crazyburst.com/ai-saas-solo-founder-success-stories-2026/)
- [MatrixFlow 一人社長AI事例](https://www.matrixflow.net/case-study/150/)
