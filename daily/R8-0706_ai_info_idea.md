# AI情報ブリーフィング R8-0706（2026-07-06）
作成：AI Company CTO（技術・AI担当）

---

## ① AIニュース Top5

### 1. Claude Fable 5 復活 ＆ Claude Sonnet 5 正式リリース
**要約**
Anthropicは7月1日、米政府の輸出規制（6/12発動）で停止していたFable 5を20日ぶりに復活。新しいサイバーセキュリティタスクを検出・ブロックするAIクラシファイアを追加して再展開。同時期にClaude Sonnet 5も正式リリース。1Mトークンコンテキスト・ネイティブ対応で、Claude Codeのデフォルトモデルとなった。8月31日まで$2/$10/Mtokの促進価格が適用される。

**重要性（事業への紐づけ）**
- **Web制作**：Claude Code（AIでコードを書くツール）がSonnet 5になり制作速度が一段階上がる。Claude Sonnet 5でLP・CMS実装の自動化精度が向上。
- **AI研修**：「なぜFable 5が止まり、どう再展開されたか」がAIガバナンス研修の最高の事例素材。中小企業への研修コンテンツに即転用可能。
- **補助金支援**：AI利活用に関する政府介入事例として、補助金申請の「AI活用の社会的位置づけ」説明に使える。

**ソース**
- https://www.anthropic.com/news/claude-new-constitution
- https://9to5google.com/2026/07/01/anthropic-fable-5-returns-to-claude/
- https://releasebot.io/updates/anthropic/claude

---

### 2. Claude Science 発表 ── 科学者向けAIワークベンチ
**要約**
AnthropicがClaude Scienceをベータ公開。研究者が日常的に使うツール・パッケージを統合し、監査可能な成果物を生成。計算リソースへの柔軟なアクセスも提供。Claude Pro/Max/Team/Enterprise向け。

**重要性（事業への紐づけ）**
- **AI研修**：「AIが専門職の仕事を変える」を実演するデモとして最適。「研究者でもAIで論文執筆・データ分析が変わる」という訴求でIT以外の業種にも研修展開できる。
- **補助金支援**：製造業・医療・食品系クライアントへのAI導入補助金提案で「Claude Scienceで研究開発コストを下げる」という事例として活用可能。

**ソース**
- https://www.anthropic.com/news/claude-science-ai-workbench
- https://aitoolsrecap.com/Blog/AINewsJuly2026.aspx

---

### 3. OpenAI GPT-5.6「Sol/Terra/Luna」& ultra モード登場
**要約**
OpenAIがGPT-5.6のプレビューを開始。3モデル（Sol/Terra/Luna）構成で、推論・コーディング・生物学・サイバーセキュリティの性能が向上。特にSolにはultra modeが追加され、複数のサブエージェントを使って複雑タスクを並列処理できる。ChatGPT Businessでは「Instant/Medium/High/Extra High/Pro Standard/Pro Extended」のモデルピッカーも刷新。

**重要性（事業への紐づけ）**
- **Web制作**：ultra modeで「競合調査→サイト設計→コーディング」を一括エージェント実行できる時代に。クライアントへの提案工数を大幅削減可能。
- **AI研修**：「ChatGPTはいつのまにかサブエージェントで動いている」を実演できる研修ネタ。企業のDX担当者が目を丸くするデモになる。
- **動画/デザイン**：Terraがクリエイティブ生成向けに最適化された可能性あり。プロンプト設計の研究素材として追いかける価値あり。

**ソース**
- https://openai.com/index/gpt-5-5-instant/
- https://releasebot.io/updates/openai
- https://www.kunalganglani.com/blog/chatgpt-biggest-upgrade-developers-june-2026

---

### 4. Gemini Spark ── Googleの「パーソナルAIエージェント」macOS版解禁
**要約**
GeminiアプリのmacOS版に、Sparkと呼ばれるパーソナルAIエージェントが追加。ローカルファイルを操作しフォルダ整理・文書作成・Google Workspace横断タスクを自律実行する。Google AI Ultraサブスクライバー（18歳以上）から展開。同時にGemini Omniも公開：テキスト・写真・動画を組み合わせて高品質動画を作成し、AIアバターで自分の顔・声を動画に差し込める。

**重要性（事業への紐づけ）**
- **動画/デザイン**：Gemini Omniは社長の動画制作事業に直撃。「顧客の顔・声でAIアバター動画を量産する」という新サービスラインが成立しうる。
- **AI研修**：「Googleが個人PCに自律エージェントを解禁した」という衝撃を研修の掴みに使う。DX担当者・経営者の関心を引くには最高のニュース。
- **Web制作**：Google Workspaceと連携するSparkは、クライアント企業の業務自動化提案（Googleドライブ整理・ドキュメント自動生成）のデモに使える。

**ソース**
- https://gemini.google/release-notes/
- https://blog.mean.ceo/google-gemini-news-july-2026/
- https://aadhunik.ai/blog/google-io-2026-announcements-gemini-ai-updates/

---

### 5. OpenClaw ── GPT-5.6対応 ＆ Telegram Codexペアリング強化
**要約**
自律AIエージェントハーネスのOpenClawが大型アップデート。GPT-5.6（Sol/Terra/Luna）を全面サポート。Telegramから`/login`で開始し、Codexの稼働・操作・回復が可能に。複数ユーザーが同じGatewayを共有しながら、DMの相手ごとに別モデルを割り当てる機能も追加。なお同ツールはMetaによる買収交渉が中国規制当局にブロックされた後も、単独で開発・提供を継続している。

**重要性（事業への紐づけ）**
- **AI研修**：OpenClaw × Telegramの構成で「スマホから複数AIを使い分ける」実演ができる。経営者層に「AIは難しくない」を見せる最高のデモ。
- **Web制作**：OpenClawをGatewayとして使い、複数クライアントの制作ジョブを並列管理する自動化が現実的に。制作単価を維持しながら案件数を増やすインフラになる。
- **陰陽師/占い**：Telegramボットとの連携が簡単になったことで、占い結果を自動返信するボットをOpenClaw経由で構築できる可能性がある。

**ソース**
- https://releasebot.io/updates/openclaw
- https://www.kdnuggets.com/openclaw-explained-the-free-ai-agent-tool-going-viral-already-in-2026
- https://www.infoq.com/news/2026/06/microsoft-scout-openclaw-build/

---

## ② マイクロ法人 × AI活用で大きく稼いでる事例 5選

### 事例1：Matthew Gallagher（米・LA在住）／ Medvi
**誰が**：Matthew Gallagher（米ロサンゼルス在住、個人起業家）。唯一の採用は実兄Elliot。実質2名体制。

**何を**：GLP-1（肥満治療薬）遠隔医療スタートアップ「Medvi」。処方・フォローアップ・患者コミュニケーションを自動化。

**どうやって**：初期投資$20,000のみ、自宅オフィスから開始。12種類以上のAIツールを組み合わせてカスタムエージェントを構築し、患者対応・コンテンツ・広告を全自動化。

**使用ツール**：ChatGPT・Claude・Grok（コード＆コピー）、Midjourney・Runway（広告クリエイティブ）、ElevenLabs（音声対応）、カスタムAIエージェント（システム間連携）。

**どのように稼いだか**：初年度$4億1,000万ドルの売上。純利益率16.2%。2026年は$18億ドル（約2,700億円）追跡ペース。

**社長の事業への応用**
→ **AI研修**に直結。「2人でも年商400億円が可能」は、愛知県の中小企業経営者に対して「なぜAI研修が必要か」を一発で説得できる最強の事例。研修の冒頭スライドに入れるべき数字。
→ **補助金支援**：医療・介護系クライアントへのAI導入提案で「GLP-1テレヘルスのロジック＝AIエージェントで問い合わせ〜契約〜フォロー一気通貫」という構造を参考に提案資料を作れる。

**ソース**：https://wearepresta.com/ai-agent-startup-ideas-2026-15-profitable-opportunities-to-launch-now/

---

### 事例2：Maor Shlomo（イスラエル・31歳）／ Base44 → Wix買収 $80M
**誰が**：Maor Shlomo（イスラエル、31歳、元兵役直後の個人エンジニア）。完全ソロ。

**何を**：AI no-codeアプリビルダー「Base44」。自然言語プロンプトだけでDB設計・権限設定・デプロイまで完結。

**どうやって**：わずか5桁ドル（百万円未満）の初期投資で6ヶ月でゼロから構築。イスラエルとイランの戦争が始まった朝に契約締結という極限状況でEXIT成立。

**使用ツール**：Claude（コーディング・アーキテクチャ設計）、GPT系（コンテンツ生成）、セルフホスト型デプロイ基盤。

**どのように稼いだか**：EXIT時点で350,000ユーザー・月収$200,000。Wixへ$80M（約120億円）でEXIT。Q1 2026時点で200万ユーザー・ARR約$100M。

**社長の事業への応用**
→ **Web制作**：「AI no-codeビルダーで中小企業が自分でサイト更新できる仕組みを提供する」という新サービスラインのヒント。Base44的なビルダーをクライアントに提供し、月額保守費を取るモデルが成立。
→ **AI研修**：「6ヶ月・1人・120億円EXIT」を研修の事例として使う。「AIを使えば個人でも組織に勝てる」という動機付けに最強。

**ソース**
- https://www.wix.com/press-room/home/post/wix-further-expands-into-vibe-coding-with-acquisition-of-base44-a-hyper-growth-startup-that-simplif
- https://nocodeexits.substack.com/p/how-maor-shlomo-sold-base44-for-80m

---

### 事例3：Pieter Levels（オランダ・ノマド）／ PhotoAI・NomadList・RemoteOK 他
**誰が**：Pieter Levels（オランダ人、デジタルノマド、雇用ゼロ）。

**何を**：PhotoAI（AIヘッドショット生成）、RemoteOK（リモート求人掲示板）、NomadList（ノマド向けコミュニティ）、fly.pieter.com（ブラウザ飛行シム）など複数プロダクト群。

**どうやって**：1プロダクトずつビルドインパブリック（開発過程をX/SNSでリアルタイム公開）。fly.pieter.comは17日でARR$100万達成。Cursor＋Three.jsで開発。

**使用ツール**：Cursor、Claude、Midjourney（広告素材）、Stripe（決済）、シンプルなVPS（サーバー）。

**どのように稼いだか**：ポートフォリオ全体でARR$310〜350万ドル（約5億円）。PhotoAI単独で月収$132,000。RemoteOKで月収$41,000。

**社長の事業への応用**
→ **Web制作**：「ビルドインパブリック」戦略は愛知で全く普及していない。「制作過程をXで公開→集客→受注」モデルを真似するだけで差別化になる。
→ **陰陽師/占い**：PhotoAIのように「占い師向けプロフィール画像AI生成」サービスを作れば国内ニッチで先行者になれる。月額サブスクで安定収益。

**ソース**
- https://www.fast-saas.com/blog/pieter-levels-success-story/
- https://www.indiehackers.com/post/photo-ai-by-pieter-levels-complete-deep-dive-case-study-0-to-132k-mrr-in-18-months-3a9a2b1579

---

### 事例4：Marc Lou（フランス人・ノマド）／ ShipFast・CodeFast・DataFast
**誰が**：Marc Lou（フランス人、インディーハッカー、従業員ゼロ）。

**何を**：ShipFast（Next.js SaaSスターターキット）、CodeFast（プログラミング教材）、DataFast（アナリティクスツール）の3プロダクト。

**どうやって**：徹底的にノーコード寄りの開発＋SNS発信。2025年の年間売上$103万ドルを達成後も成長継続。2026年3月に月収$78,000を記録。

**使用ツール**：Claude Code（コーディング）、Cursor、Next.js、Stripe、Lemon Squeezy（決済）。

**どのように稼いだか**：2025年累計$1,032,000（年商約1.5億円）。2026年3月月収$78,000（年換算約1.4億円ペース）。全プロダクトのLTV合計で成長中。

**社長の事業への応用**
→ **AI研修**：「ShipFast的な研修スターターキット」を作れる。愛知の中小企業向けに「AIで業務フロー設計テンプレ」を月額サブスクで販売するモデルに転用。
→ **Web制作**：制作でよく使うコンポーネント・テンプレートをShipFast的に商品化し、制作会社向けに販売。受注以外の収益柱が生まれる。

**ソース**
- https://greyjournal.net/hustle/grow/solo-founders-million-dollar-ai-businesses-2026/
- https://aiinsider.in/ai-learning/chatgpt-new-features-2025-2026/

---

### 事例5：匿名ソロ開発者（国籍不明）／ 35本のマイクロSaaS群
**誰が**：30歳のソロ開発者（実名非公開、SNSベースで判明）。

**何を**：35本の異なるマイクロSaaSを同時運営。各アプリは特定のニッチ課題だけを解く小粒ソフトウェア。

**どうやって**：1アプリ＝1問題を徹底。Claude Code・Cursor・v0.devで開発工数を最小化し、多数の小さな収益源を束ねるポートフォリオ戦略。SNS公開で有機的集客。

**使用ツール**：Claude Code、Cursor、v0.dev（UI生成）、Stripe、Vercel（ホスティング）。

**どのように稼いだか**：2026年に1ヶ月で$77,000（約1,150万円）を達成。MRR（月次経常収益）モデルで安定収入化。

**社長の事業への応用**
→ **Web制作**：「35本」という発想を参考に、「小さなWebツール（補助金チェッカー/AI見積ツール/占いbot）を次々作って副収益ポートフォリオを積む」戦略が社長の事業に完全適合。
→ **補助金支援**：補助金種別を自動判定する診断ツールを作り無料で公開→問い合わせ獲得→有料コンサル受注、という流れを35本モデルで量産できる。

**ソース**
- https://www.buildmvpfast.com/blog/solo-developer-35-micro-saas-apps-77k-month-portfolio-2026
- https://crazyburst.com/ai-saas-solo-founder-success-stories-2026/

---

## ③ 社長の事業に直結する実践AIアイデア 5選

### アイデア1：AI補助金診断ボット for 愛知中小企業
**対象事業**：補助金支援

**具体アクションプラン**
1. 愛知県・経産省の最新補助金情報（ものづくり補助金・IT導入補助金・省エネ補助金）をClaudeに学習させたチャットボットを1週間で構築（v0.dev＋Claude API）
2. LPに「無料で30秒診断」として設置。SNS・経営者コミュニティで拡散
3. 診断完了後に「詳細サポートは弊社へ」という相談導線を入れ、有料コンサル（5〜10万円/件）へ誘導

**期待売上インパクト**
月50件診断→コンサル転換率10%→5件×7万円＝月35万円（年420万円）。ツール自体を他の補助金支援士に横展開すれば別途ライセンス収益も発生。

---

### アイデア2：AIで「3日で納品」Web制作パッケージ
**対象事業**：Web制作

**具体アクションプラン**
1. Claude Code＋v0.dev＋Vercelで、ヒアリング→デザイン→コーディング→デプロイを72時間以内に完結するワークフローを自社で確立（Claude APIの費用は月1〜2万円程度）
2. 「3日納品・10万円〜」という差別化パッケージをSNS＋経営者コミュニティで告知。「普通の制作会社は1〜2ヶ月」との対比で訴求
3. 月5件限定でスロット制にして希少性を演出。リピート・紹介サイクルを回す

**期待売上インパクト**
月5件×15万円＝月75万円（年900万円）。AI活用で制作時間を1/3に圧縮できれば利益率80%以上も可能。

---

### アイデア3：AI動画自動生成サービス for 飲食・マーメイド事業
**対象事業**：動画/デザイン・飲食・マーメイド事業

**具体アクションプラン**
1. Gemini Omni（またはRunway Gen-3）＋ElevenLabs（音声）を使い、「メニュー写真→15秒Reels動画」を自動生成するパイプラインを組む
2. まず自社のマーメイド事業・飲食店で試験運用。ビフォーアフターをSNSで公開してサービスとしての実績を積む
3. 愛知の飲食店・美容室・エステに月3〜5万円のサブスク型で横展開

**期待売上インパクト**
月20クライアント×3万円＝月60万円（年720万円）。動画生成コストはAIで激減しているため、粗利率70%以上を維持できる。

---

### アイデア4：AI陰陽師 占いLINEボット（月額サブスク）
**対象事業**：陰陽師/占い

**具体アクションプラン**
1. Claude APIをバックエンドに、LINE Messaging APIで動く占いボットを構築。四柱推命・九星気学・方位学など複数占術を実装（月開発費5〜10万円、Claude APIは月2〜3万円）
2. 「毎朝7:00にAI陰陽師から今日の運勢が届く」月額980円サブスクで販売。Stripe＋LINE公式で完結
3. SNS（X/Instagram）でシャドーバン回避しながら「無料占いで集客→有料化」のファネルを設計。陰陽師コンテンツはアルゴリズムに乗りやすい

**期待売上インパクト**
300人サブスク×980円＝月294,000円（年352万円）。1,000人達成で年980万円。コンテンツは一度作ればランニングコストが低い。

---

### アイデア5：AI研修「1日5万円パッケージ」for 愛知中小企業
**対象事業**：AI研修

**具体アクションプラン**
1. 「ChatGPT/Claude/Geminiを使った業務効率化」半日研修（3時間）を人事・総務担当者向けに設計。Medvi事例・Pieter Levels事例・Marc Lou事例を実例として組み込み、「AI=難しい」という心理的ハードルを壊す構成にする
2. 愛知県商工会議所・ロータリークラブ・BNI等の経営者コミュニティで先行無料登壇し実績作り。ヒト補助金（人材開発支援助成金：研修費用75%補助）対象として打ち出す
3. 月4回開催（週1）で法人向け：1社5万円×4社＝月20万円スタート。継続でスケール

**期待売上インパクト**
月4社×5万円＝月20万円（年240万円）。オンライン展開・動画コース化に移行すれば年1,000万円以上の射程圏。ヒト補助金対象にすると中小企業側の実質負担が25%になり成約率が上がる。

---

## 本日のサマリー
| カテゴリ | キーワード | 緊急度 |
|--------|---------|------|
| Claude Sonnet 5 & Fable 5 | コード生成・研修素材 | 高 |
| GPT-5.6 ultra mode | エージェント並列処理 | 高 |
| Gemini Omni | 動画生成サービス化 | 中 |
| Medvi 2名$400M | 研修事例の最強ネタ | 即使用 |
| Base44 $80M EXIT | AI no-code事業 | 中 |
| 補助金診断ボット | 今月中に着手推奨 | 高 |

---

次回：明日 7:30 AM
