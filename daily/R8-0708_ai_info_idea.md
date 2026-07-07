# AI情報ブリーフィング R8-0708（2026-07-08）
作成：AI Company CTO（技術・AI担当）

---

## ① AIニュース Top5

### 1. Claude Cowork がモバイル・Web対応に拡大、科学者向け「Claude Science」も発表

**要約**
Anthropicは、AIエージェント協働プラットフォーム「Claude Cowork」をMaxサブスクライバー向けにWebとモバイルへ開放した。デスクで作業を始め、スマホで進捗確認し、移動先で成果物を受け取るワークフローが実現。同時に研究者向けの専用ワークベンチ「Claude Science」も発表。科学分野の標準ツール・パッケージを統合し、監査可能なアーティファクトを生成する。

**重要性（事業への直結）**
- **AI研修事業**：「AIで働き方が変わる」を体感させる新教材として即活用可能。移動中も業務継続できるデモが受講者に強烈なインパクトを与える。
- **Web制作**：Coworkを使ったサイト制作ワークフロー自動化の提案材料になる。クライアントへの導入提案でCoworkのデモを使うと商談が加速する。

**ソース**
- [Claude Cowork expands to mobile and web | TechCrunch](https://techcrunch.com/2026/07/07/the-coding-agent-wars-are-spilling-into-the-rest-of-the-office-claude-cowork/)
- [Claude Science, an AI workbench for scientists | Anthropic](https://www.anthropic.com/news/claude-science-ai-workbench)

---

### 2. OpenAI、GPT-5.6（Sol / Terra / Luna）を限定プレビュー開始 ＋ Codex Remote GA

**要約**
OpenAIがGPT-5.6として3モデル（Sol：推論特化・Terra：コーディング特化・Luna：日常汎用）を限定公開。特にSolはサイバーセキュリティ・生物分野で突出した性能を示す。同時に「Codex Remote（コード実行をPC上でリモート継続するエージェント）」が全プランで一般提供（GA）開始。リアルタイム音声モデル gpt-realtime-2.1 も25%以上低レイテンシで更新。

**重要性（事業への直結）**
- **AI研修**：「ChatGPT 5.6が来た。GPT-4と何が違うのか？」という研修コンテンツとして直結。モデルの使い分け（Sol/Terra/Luna）を教えるだけで研修カリキュラムが一本作れる。
- **Web制作**：Codex Remoteを使ったサイト制作の一部自動化により、制作コストを30〜40%削減できる可能性がある。

**ソース**
- [OpenAI Release Notes - July 2026 | Releasebot](https://releasebot.io/updates/openai)
- [ChatGPT Updates by OpenAI - July 2026 | Releasebot](https://releasebot.io/updates/openai/chatgpt)

---

### 3. Google「Gemini Spark」がmacOSに対応、Canva・Dropbox・OpenTableと連携

**要約**
GoogleのAIエージェント「Gemini Spark」がMac向けベータ版を公開。Canva（デザイン）、Dropbox（ファイル）、Instacart（食料品）、OpenTable（レストラン予約）、Zillow（不動産）と連携し、AIが日常タスクを横断して実行できるようになった。Google AI Ultraサブスクライバー向け（米国限定）だが、日本展開も時間の問題。

**重要性（事業への直結）**
- **動画・デザイン**：Canva連携により「AIが自動でデザインを調整→Canvaで仕上げ」のパイプラインが完成しつつある。動画制作の企画・台本生成→デザイン自動化のワークフローを先行して構築すると差別化になる。
- **飲食**：OpenTable連携で予約・顧客管理AIとの統合ユースケースが広がる。将来的に飲食店のAI受付・予約自動化として転用できる。

**ソース**
- [Gemini Spark, Google's agentic assistant, is now available on Mac | TechCrunch](https://techcrunch.com/2026/07/01/gemini-spark-googles-agentic-assistant-is-now-available-on-mac/)
- [Google I/O 2026 Announcements and Gemini AI Updates](https://aadhunik.ai/blog/google-io-2026-announcements-gemini-ai-updates/)

---

### 4. OpenClaw、GitHubスター数347,000件突破 ─ iOS/Androidアプリも登場

**要約**
オープンソースのローカルAIエージェント「OpenClaw」がGitHub史上最多スター数（347,000件）を記録。2026年1月に公開後わずか半年で爆発的に普及。ローカルPC上でファイル読み書き・ターミナル実行・WhatsApp/Discord連携が可能。iOSとAndroidアプリも登場し、スマホからエージェントへのリモート承認もできるようになった。

**重要性（事業への直結）**
- **CTO視点（自動化）**：有料SaaSを使わずローカルで動くAIエージェントが手に入る。社長自身の業務自動化（問い合わせ対応・ファイル整理）をゼロコストで試せる。
- **AI研修**：「ChatGPTを超えたオープンソースエージェント」という切り口で研修コンテンツが1本作れる。無料で試せるため受講者のハードルが低い。

**ソース**
- [OpenClaw Explained: The Free AI Agent Tool Going Viral in 2026 | KDnuggets](https://www.kdnuggets.com/openclaw-explained-the-free-ai-agent-tool-going-viral-already-in-2026)
- [OpenClaw — Personal AI Assistant](https://openclaw.ai/)

---

### 5. 中国アリババ、従業員にClaude（Anthropic）の使用を禁止

**要約**
アリババは7月10日付けで、従業員がAnthropicのAIツール（Claude）を業務利用することを禁止した。理由はバックドア（セキュリティ上の抜け道）のリスク懸念。同時にMeta社によるManus AI（中国発エージェント）の買収計画も中国当局によって6月に正式阻止された。AI覇権をめぐる米中対立がAIツールの利用制限というレイヤーにまで波及している。

**重要性（事業への直結）**
- **AI研修**：「日本企業が中国企業に販売する場合のAIコンプライアンス（法令遵守）」という新研修テーマとして使える。製造業や商社向けに響く。
- **補助金支援**：デジタルAI補助金申請において「クラウドサービスの安全性審査」の重要性を説く際の事例として活用可能。

**ソース**
- [China's Alibaba bans Anthropic AI for employees after 'distillation attack' accusation | CNBC](https://www.cnbc.com/2026/07/06/alibaba-anthropic-ai-ban-claude-china.html)

---

## ② マイクロ法人 × AI活用で大きく稼いでる事例 5選

### 事例1：Matthew Gallagher（米国）／テレヘルス「Medvi」で年商401億円

| 項目 | 内容 |
|------|------|
| **誰が** | Matthew Gallagher（米国・元マーケター）、弟1名のみの2人体制 |
| **何を** | GLP-1（肥満治療薬）テレヘルス（遠隔医療）スタートアップ「Medvi」 |
| **どうやって** | 初期資金$20,000（約300万円）・2024年9月創業。外部資金調達なし |
| **使用AIツール** | ChatGPT・Claude・Grok（コード＆コピー）、Midjourney・Runway（広告クリエイティブ）、ElevenLabs（音声対応） |
| **どのように稼いだか** | 初年度年商$401M（約580億円）、2026年は$1.8B（約2,600億円）ペース。利益率は従来の医療スタートアップの3倍 |
| **社長の事業への応用** | **補助金支援×AI**：GLP-1のような社会的需要が高い分野に特化した「スポット型サービス×AI自動化」モデル。補助金診断×AI自動書類作成を組み合わせて「補助金ワンストップSaaS」として水平展開できる |

**ソース**：[The One-Person Billion-Dollar Company Is Here | PYMNTS](https://www.pymnts.com/artificial-intelligence-2/2026/the-one-person-billion-dollar-company-is-here/)

---

### 事例2：Danny Postma（オランダ）／AIヘッドショット「HeadshotPro」で月商3,000万円

| 項目 | 内容 |
|------|------|
| **誰が** | Danny Postma（オランダ・インディーハッカー）、完全ソロ運営 |
| **何を** | AIで本物のようなビジネスプロフィール写真を生成するSaaS「HeadshotPro」 |
| **どうやって** | 外部資金なし。Southeast Asiaのノマドスタイルで2023年に立ち上げ |
| **使用AIツール** | Stable Diffusion（画像生成）、Stripe（決済）、独自ファインチューニング |
| **どのように稼いだか** | MRR $300K（月商約4,400万円）＝年商3.6億円。アフィリエイトプログラム単体で月$50K超。前作「Headlime」はローンチ8ヶ月で$100万で売却 |
| **社長の事業への応用** | **動画・デザイン事業**：「AI証明写真」「AIアバター生成」を動画・デザインのオプションとして追加するだけで単価+3〜5万円が狙える。制作コストはほぼゼロ |

**ソース**：[HeadshotPro: How One Developer Earns $300K/Month with AI Headshots | AI Business](https://aibusiness.vc/solo/headshot-pro-300k-month)

---

### 事例3：Pieter Levels（オランダ）／NomadList・PhotoAI で年商5億円超、純資産60億円超

| 項目 | 内容 |
|------|------|
| **誰が** | Pieter Levels（@levelsio・オランダ）、正社員ゼロ |
| **何を** | NomadList（ノマド向けコミュニティ）、PhotoAI（AI写真生成）、RemoteOK（リモート求人）など複数SaaS |
| **どうやって** | VC資金調達ゼロ。タイ・バリを拠点にしたデジタルノマドスタイル。年間12プロダクト公開戦略 |
| **使用AIツール** | Claude・Cursor（コーディング）、Midjourney（アセット）、Stripe（決済）、自動化スクリプト |
| **どのように稼いだか** | NomadListの年商は$5.3M（約7.7億円）。PhotoAIは月$100K到達後も成長中。推定純資産$40〜60M（約60〜87億円）。外部資金調達なし |
| **社長の事業への応用** | **陰陽師・占い事業**：「占いコミュニティ＋有料会員制サイト」という形で、NomadListのビジネスモデルをそのまま転用できる。月980〜1,980円の会員費×1,000人で月収100〜200万円 |

**ソース**：[How Pieter Levels Built a $3M/Year Business with Zero Employees | Fast SaaS](https://www.fast-saas.com/blog/pieter-levels-success-story/)

---

### 事例4：Maor Shlomo（イスラエル）／「Base44」をWixに$80M（約117億円）で売却

| 項目 | 内容 |
|------|------|
| **誰が** | Maor Shlomo（イスラエル・元エンジニア）、最小チーム |
| **何を** | AIでWebアプリを自動生成するノーコードプラットフォーム「Base44」 |
| **どうやって** | 創業6ヶ月以内に25万ユーザー獲得、黒字化達成 |
| **使用AIツール** | Claude・GPT（コード生成）、自社AI生成エンジン |
| **どのように稼いだか** | 2025年にWixへ$80M（約117億円）でEXIT（バイアウト＝企業売却）。月次ユーザー数は6ヶ月で25万人突破 |
| **社長の事業への応用** | **Web制作事業**：「AIでWebアプリを自動生成→クライアントに納品」という新サービスラインを追加できる。Base44のような仕組みを自社制作の差別化として訴求すると単価が上がる |

**ソース**：[7 Solo Founders Building $1M+ AI Businesses in 2026 | Grey Journal](https://greyjournal.net/hustle/grow/solo-founders-million-dollar-ai-businesses-2026/)

---

### 事例5：日本のIT支援事業者／デジタルAI補助金2026を軸に年間15件超の新規契約

| 項目 | 内容 |
|------|------|
| **誰が** | 日本全国のIT支援事業者（登録事業者約12,000社のうち上位30%） |
| **何を** | 中小企業向けデジタルAI補助金2026（経産省・中小機構）の申請代行＋AI導入コンサル |
| **どうやって** | 登録IT支援事業者として国の公式DBに掲載→補助金を探す中小企業から直接問い合わせが来る仕組み |
| **使用AIツール** | Claude・ChatGPT（申請書類の草案生成）、Zapier（問い合わせ自動応答） |
| **どのように稼いだか** | 申請支援コンサル1件10〜30万円×15件/年 ＝ 最大450万円/年。補助金予算総額は約84億円（前年比1.4倍）に拡大 |
| **社長の事業への応用** | **補助金支援事業**：すでに社長が取り組んでいる事業の「最速の売上柱」になりうる。IT支援事業者への登録＋Claude活用で申請書類の作成時間を80%短縮できる |

**ソース**：[Complete Guide to Digital AI Subsidy 2026 | Oflight Inc.](https://www.oflight.co.jp/en/columns/digital-ai-subsidy-2026-guide-for-it-vendors)

---

## ③ 社長の事業に直結する実践AIアイデア 5選

### アイデア1：「AI補助金ワンストップ診断」でWeb制作×補助金支援の複合受注

**対象事業**：Web制作 ＋ 補助金支援  
**具体アクション**
1. LP（ランディングページ＝集客ページ）に「30秒AI補助金診断」を設置。チャットボット（Claude API）で業種・従業員数・課題を入力させ、使える補助金を自動判定する
2. 診断完了後に「AI対応Webサイト制作（補助金対象）をセットで提案」するCTA（行動喚起ボタン）を配置
3. 補助金申請サポート費用をWeb制作費に内包し「実質負担ほぼゼロ」として提案

**期待売上インパクト**  
Web制作1件50万円 ＋ 補助金申請代行20万円 ＝ 70万円/件 × 月2件 ＝ **月商140万円**（年商1,680万円）

---

### アイデア2：「中小企業AI活用研修 × デジタルAI補助金2026」パッケージ販売

**対象事業**：AI研修 ＋ 補助金支援  
**具体アクション**
1. IT支援事業者（ITベンダー支援者）に登録し、国の公式DBへ掲載。補助金を使いたい中小企業から問い合わせが自動で入ってくる状態を作る
2. 研修費用（1社あたり20〜30万円）の最大50%が補助金でカバーされることを前面に出したLPを作成
3. 研修内容は「ChatGPT / Claude 実務活用3時間ワークショップ」に絞り、資料はClaude自動生成で制作コストゼロにする

**期待売上インパクト**  
研修1社25万円 × 月3社 ＝ 月商75万円（年商900万円）。補助金申請代行も込みなら月商120〜150万円

---

### アイデア3：AI動画で「顔出しなし占いYouTubeチャンネル」を開設

**対象事業**：陰陽師・占い ＋ 動画・デザイン  
**具体アクション**
1. Claude + ElevenLabs（AI音声）+ Runway（AI動画生成）で「今週の運勢・星座占い」動画を1本30分で量産。顔出し不要
2. YouTubeチャンネルを毎日1本投稿で90日間継続。キーワードは「星座 今週 運勢 2026」「算命学」「陰陽師 占い」
3. 収益化解放後はAdSense ＋ 個別鑑定（30分3万円〜）へ誘導するCTAを各動画末尾に設置

**期待売上インパクト**  
チャンネル登録1万人達成後：広告収益月2〜5万円 ＋ 個別鑑定5件/月×3万円 ＝ **月商17〜20万円**（副次的キャッシュフロー）

---

### アイデア4：LINE占いAIチャットボット × サブスクで占い事業を自動化

**対象事業**：陰陽師・占い  
**具体アクション**
1. Claude APIをLINE Messaging APIに接続し、生年月日・名前を入力するだけで四柱推命（しちゅうすいめい）の自動鑑定を返すLINEボットを構築（開発費：外注20〜30万円 or 自作で無料）
2. 月980円のサブスク（月1回鑑定）と単発3,000円の詳細鑑定をラインナップ
3. X（旧Twitter）で「今日の星座運勢」を毎日自動投稿（Claude自動生成）してLINE追加へ誘導

**期待売上インパクト**  
サブスク200人 × 980円 ＝ 月収196,000円 ＋ 単発鑑定 ＝ **月商25〜40万円**（完全自動化、稼働ゼロ）

---

### アイデア5：飲食店向け「AI集客パック」で動画・SNS・Googleマップを一括支援

**対象事業**：飲食 ＋ 動画・デザイン  
**具体アクション**
1. 飲食店の料理写真をスマホで撮影→ Midjourney / Canva Magic Studioで高品質加工→ Googleビジネスプロフィール・インスタ・食べログを月10投稿分まとめて自動生成（Claude+Canva API）
2. TikTok / Instagram Reels向けに「仕込み動画・調理風景15秒ショート」をRunwayで自動編集。月4本納品
3. Googleマップ口コミ返信もClaudeで自動下書き生成し、オーナーが1クリック承認するだけのフローを構築

**期待売上インパクト**  
月3万円/店舗 × 10店舗 ＝ **月商30万円**（年商360万円）。初期構築費別途10万円で収益化加速

---

## まとめ：今日の最重要アクション

| 優先度 | アクション | 事業 |
|--------|-----------|------|
| ★★★ | IT支援事業者への登録を今週着手（補助金84億円の受け口を確保） | 補助金支援 |
| ★★★ | Claude API × LINE でAI占いボット構築を検討（完全自動化の最速柱） | 陰陽師・占い |
| ★★ | Claude Cowork を自分の業務フローに組み込み（AI研修の教材にもなる） | AI研修 |
| ★★ | GPT-5.6のSol/Terra/Lunaの違いを把握し研修カリキュラムに追加 | AI研修 |
| ★ | 飲食店向けAI集客パックの料金表を作成してテスト営業 | 飲食 |

---

次回：明日 7:30 AM
