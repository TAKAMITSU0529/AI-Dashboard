# AI情報ブリーフィング R8-0730（2026-07-30）
作成：AI Company CTO（技術・AI担当）

---

## ① AIニュース Top5

### 1. MCP（モデルコンテキストプロトコル）が過去最大のアップデート「2026-07-28仕様」を正式リリース

**要約**
AIエージェント間の通信規格MCPが、Anthropicとアジャイル人工知能財団（AAIF／Linux Foundation傘下）の主導で大幅刷新。ステートレス（状態を持たない）アーキテクチャへの移行、OAuth/OIDCによる認証強化、12ヶ月の廃止猶予ポリシーの制定、そして「インタラクティブUI」「長時間非同期タスク」の公式拡張機能化が柱。エンタープライズ向けに丸ごとリデザインされた。

**重要性**
- **AI研修事業に直結**：「MCPとは何か・どう使うか」が中小企業向けAI研修の核心テーマになる。最新仕様を理解している講師は稀少で、差別化教材になる
- **Web制作事業に直結**：AI-powered Webサービス構築時のシステム設計標準として採用必須。Claude CoworkやChatGPT Workとの接続が簡単になる
- **CTO業務への直結**：現在の社内MCP設定を新仕様（2026-07-28）に対応させる必要がある

**ソース**
- https://venturebeat.com/orchestration/mcp-just-got-its-biggest-update-ever-heres-what-changes-for-ai-agents
- https://blog.modelcontextprotocol.io/posts/2026-07-28/
- https://techcrunch.com/2026/07/20/ais-most-important-protocol-is-getting-a-little-bit-easier-to-use/

---

### 2. Claude Voice Mode が Gmail・Slack・Canva と音声接続、Opus/Sonnet/Haikuで選択可能に

**要約**
AnthropicがClaude Voice Modeを大幅強化。会話中にGmail・Slack・Canvaなど主要ツールに直接アクセスし、11言語でリアルタイム操作が可能になった。モデルはOpus/Sonnet/Haikuから用途に応じて選択できる。合わせて「Reflect」ダッシュボードも導入、自分のAI利用状況を可視化できる。

**重要性**
- **AI研修事業**：「声でメール作成・送信」「声でスライド編集」など、中小企業オーナーが一番驚くデモシナリオに最適。商談・研修のオープニングデモとして即採用できる
- **動画・デザイン事業**：Canvaとの音声連携は動画制作・バナー作成のワークフロー自動化に直結。クライアントへの納品速度が向上
- **陰陽師/占い事業**：音声でコンテンツ量産（占い解説動画のナレーション生成など）の自動化ラインが描けるようになった

**ソース**
- https://blog.mean.ceo/anthropic-claude-news-july-2026/
- https://releasebot.io/updates/anthropic/claude
- https://www.anthropic.com/news

---

### 3. GPT-5.6（Sol/Terra/Luna）正式GA＋ChatGPT Workが全プランで展開

**要約**
7月9日、OpenAIがGPT-5.6を3段階（Sol: $5/$30、Terra: $2.50/$15、Luna: $1/$6 per Mトークン）で一般公開。同日「ChatGPT Work」も全プランにロールアウト。1,400以上のコネクタと接続し、自然言語で指示するだけでスプレッドシート・プレゼン・Webサイト・ダッシュボードを生成する。

**重要性**
- **Web制作事業**：クライアントから「ChatGPT Workで作れるのでは？」という問いが必ず来る。「AIが作るサイトの限界」と「人間×AIが作るサイトの価値」を明確化し、差別化トークを整備する緊急性が高い
- **AI研修事業**：「ChatGPT Workで業務書類を10倍速で作る」研修コンテンツが今すぐ作れる。中小企業の総務・経理担当者向けに需要大
- **補助金支援事業**：「GPT-5.6を補助金申請書作成に使う支援」として単価アップの余地がある

**ソース**
- https://aibusinessweekly.net/p/chatgpt-new-features-2026
- https://www.bovo-digital.tech/en/blog/gpt-5-6-chatgpt-work-smb-guide-2026
- https://digitalstrategy-ai.com/gpt-5-6-chatgpt-work-analysis

---

### 4. Google、デフォルト検索をGemini 3.5 Flashに全面切り替え――「青いリンク」が消えた

**要約**
7月10日、Googleは全世界の検索クエリに対しデフォルト回答をGemini 3.5 Flashが生成するよう変更。1998年以来続いた「10件の青リンク」は標準表示から外れた。7月21日にはGemini 3.6 Flashも投入。動画生成・物理演算・色補正の品質が向上。

**重要性**
- **Web制作事業（SEO）**：Google検索のあり方が根本的に変わったため、従来のSEO対策（キーワード最適化・被リンク）だけではトラフィックを確保できなくなった。クライアントへの「AI時代のSEO戦略提案」が新規受注トリガーになる
- **SNS事業**：検索からSNS流入へのシフトを補強する提案が強まる。Instagram・YouTube・X等への注力をクライアントに強く推奨できる根拠ができた
- **コンテンツ事業全般**：「AI検索に引っかかるコンテンツ設計」（構造化データ・E-E-A-T強化）を研修・Web制作のオプションとして提供できる

**ソース**
- https://www.techtimes.com/articles/320298/20260713/google-replaced-its-default-search-ai-how-get-blue-links-back.htm
- https://indianai.in/the-gemini-revolution-inside-googles-boldest-ai-update-yet-everything-you-need-to-know-in-july-2026/
- https://releasebot.io/updates/google/gemini

---

### 5. Manus、中国政府のMeta買収ブロック後も独立継続——Web Appビルダーで自律的サービス展開

**要約**
2025年3月にデビューした中国発の自律AIエージェント「Manus」は、2026年4月にNDRC（中国国家発展改革委員会）がMeta社による買収をブロック、独立企業として活動を継続。Gmail・Google Drive・Notion・GitHubへのコネクタ追加と、データベース・Stripe・SEO統合を内包した「Webアプリビルダー」機能を2026年前半に追加。単一プロンプトから完全なWebサービスを構築できる。

**重要性**
- **Web制作事業**：Manus経由で「プロトタイプサイトを10分で作って見せる」デモが可能。初回商談で圧倒的な印象を与えられる
- **AI研修事業**：「日本でまだ知られていない中国産AIエージェントの実力」として研修の差別化コンテンツになる
- **補助金支援事業**：Manus＋Stripe連携で「AIで申請書作成→決済も自動化」という付加価値サービスのプロトタイプが描ける

**ソース**
- https://www.fm-magazine.com/issues/2026/jul/part-1-manus-ai-and-the-emergence-of-autonomous-agents/
- https://en.wikipedia.org/wiki/Manus_(AI_agent)
- https://en.ai-pedias.com/blog/manus-ai-complete-guide-2026

---

## ② マイクロ法人 × AI活用で大きく稼いでる事例 5選

### 事例1：Ben Cera（米国・ソロ起業家）――Polsia：AIエージェントが自動で会社を経営

- **誰が**：Ben Cera氏（米国・1人）
- **何を**：AIが毎晩自社の状況を判断し、翌朝レポートする「自動経営プラットフォーム」Polsiaを開発・運営
- **どうやって**：AIエージェントが7,600社以上の顧客企業のエンジニアリング・マーケティング・cold outreach・SNS・Meta広告を無人で執行。社員ゼロ、自分は意思決定と製品改善のみ
- **使用AI**：Claude + GPTベースのマルチエージェント、Stripe連携、Make/Zapier
- **収益**：5ヶ月で約10億円ARR（$10M ARR）達成。Series A 30億円調達、評価額250億円（$250M）。月次$500K超のMRR
- **社長の事業への応用**：
  - **補助金支援**：「補助金採択後の申請書管理・報告書作成をAIに任せる」サービスの設計参考
  - **AI研修**：「社員ゼロで10億円」を研修冒頭のフックとして使い、中小企業経営者の関心を一気に引く

**ソース**
- https://aiweekly.co/alerts/polsia-solo-founder-raises-30m-at-250m-valuation
- https://www.contextstudios.ai/blog/polsia-how-a-solo-founder-hit-1m-arr-in-30-days-with-ai-agents

---

### 事例2：Daojie（国籍・属性不明・マーケター）――Claude AIエージェント70体で顧客売上12億円

- **誰が**：Daojie（マーケター、1人）
- **何を**：複数クライアントのマーケティング業務を、Claude AIエージェント群で完全自動化
- **どうやって**：Claude AIエージェントを70体構築・並列稼働。コンテンツ作成・A/Bテスト・広告運用・レポートを全自動化。期間2ヶ月
- **使用AI**：Claude（Anthropic）・ワークフロー自動化ツール（詳細非公開）
- **収益**：2ヶ月で顧客向け売上$1.25M（約1億8,000万円）を創出
- **社長の事業への応用**：
  - **SNS・Web制作**：クライアントのInstagram・X投稿・LP改善をAIエージェントで並列処理し、対応クライアント数を3倍以上に増やせる
  - **AI研修**：「AIエージェントを使ったマーケ自動化」の実践ワークショップを開催し、研修収益を高単価化できる

**ソース**
- https://widejournal.com/business/entrepreneurship/ai-solopreneur-one-person-business-2026/
- https://crazyburst.com/ai-saas-solo-founder-success-stories-2026/

---

### 事例3：Pieter Levels（オランダ・デジタルノマド）――Nomad List＋Remote OKで年収約4.5億円

- **誰が**：Pieter Levels（@levelsio、オランダ出身、1人）
- **何を**：Nomad List（デジタルノマド向けコミュニティ・データSaaS）＋Remote OK（リモートジョブボード）を運営
- **どうやって**：コード・SEO・UI改善にClaude/GPTを活用。チームゼロで全ての運営を自動化。VC調達ゼロのブートストラップ経営
- **使用AI**：Claude、GPT-5系、Cursor（コード補助）
- **収益**：年収$3.2M（約4.5億円）。Nomad List: $700K ARR、Remote OK: $2M+ ARR。純資産推定40〜60億円
- **社長の事業への応用**：
  - **SNS・Web制作**：「特定ニッチに特化したコミュニティSaaS」モデルは愛知・東海圏の業界特化版として横展開可能（例：東海圏飲食店特化の情報サービス）
  - **マーメイド事業**：マーメイドの活動や海外事例データを集約したコンテンツサイト化からマネタイズする切り口として参考になる

**ソース**
- https://www.starterstory.com/stories/nomad-list-breakdown
- https://unnetworth.com/pieter-levels-net-worth/

---

### 事例4：Matthew Gallagher（米国・起業家）――GLP-1テレヘルス「Medvi」で初年度売上560億円

- **誰が**：Matthew Gallagher（米国・1人でスタート）
- **何を**：GLP-1（肥満治療薬）特化のテレヘルス（遠隔医療）スタートアップ「Medvi」
- **どうやって**：2024年9月に自宅・$20,000の自己資本でスタート。AIで問診・カルテ・処方提案を自動化。250,000人の顧客獲得
- **使用AI**：GPT-4o、Claude（問診・コミュニケーション自動化）、Make（ワークフロー）
- **収益**：初年度売上$401M（約560億円）。極少人数チームで達成
- **社長の事業への応用**：
  - **飲食・マーメイド事業**：ニッチな顧客層（ダイエット・健康意識層）に特化したデジタルサービス＋AI自動化の組み合わせが有効。食×健康×AI導線の設計が参考になる
  - **補助金支援**：医療・ヘルスケア分野のIT補助金申請支援への参入余地を示唆

**ソース**
- https://www.techpluto.com/how-one-person-companies-are-becoming-million-dollar-businesses/
- https://lonelyentrepreneur.com/million-dollar-one-person-business/

---

### 事例5：Chris Lee（米国・AIオートメーションフリーランサー）――月収85万円、ツールコスト月2,800円

- **誰が**：Chris Lee（米国・AI自動化フリーランサー、1人）
- **何を**：中小企業向けのAI自動化コンサルティング・実装サービス
- **どうやって**：Make・Zapier・GPT API等を使い、クライアントの業務プロセスを1〜2週間でAI化。月1〜3社の受注で運営
- **使用AI**：Claude API、GPT-4o API、Make（Integromat）、n8n
- **収益**：月収$6,000（約85万円）。ツールコストは月$20（約2,800円）のみ。粗利率99%以上
- **社長の事業への応用**：
  - **AI研修事業**：「まず自分がChris Leeモデルをやってみせ、その実装手順を研修コンテンツにする」という実績＋教材の二重活用が最速
  - **Web制作事業**：Web制作×AI自動化のセットパッケージとして「制作費+自動化設定費+月次保守費」の3層課金モデルを構築できる

**ソース**
- https://widejournal.com/business/entrepreneurship/ai-solopreneur-one-person-business-2026/
- https://entrepreneurloop.com/ai-tools-to-scale-solo-business/

---

## ③ 社長の事業に直結する実践AIアイデア 5選

### アイデア1：「AI × 補助金申請パック」――デジタル化・AI導入補助金2026に乗る

- **対象事業**：補助金支援事業
- **背景**：中小企業庁「デジタル化・AI導入補助金2026」は6,440件の申請に対し2,982件採択（採択率46%）。7,500億円規模の大型予算が動いている
- **具体アクションプラン**：
  1. 補助金申請書の草案をClaudeで自動生成するテンプレートを整備（1〜2日作業）
  2. 「AIで申請書をほぼ自動作成＋プロが仕上げる」パッケージを15〜30万円で販売
  3. 愛知県内の中小企業に対してGoogleビジネスプロフィール＋ダイレクトメールで案内→月3〜5件受注
- **期待売上インパクト**：月3件×25万円＝75万円／月（年間900万円）

**ソース**
- https://hojyokin-portal.jp/columns/ai-agent-hojyo
- https://www.chusho.meti.go.jp/koukai/hojyokin/kobo/2026/260310001.html

---

### アイデア2：「Google AI検索対策パック」――SEO崩壊後の新トラフィック設計

- **対象事業**：Web制作事業
- **背景**：Googleがデフォルト検索をGemini 3.5 Flashに全面切り替え。従来のSEO設計が通用しなくなった。クライアントのWeb担当者が「どうすればいいか」を探している
- **具体アクションプラン**：
  1. 「AI時代のSEO診断レポート」を1〜2時間のClaudeワークフローで自動生成（構造化データ・E-E-A-T評価・AI検索露出スコア）
  2. 既存Web制作クライアントへ無料診断→「AI検索対応リニューアル提案」として50〜100万円の追加受注を狙う
  3. SNS（X/Instagram）で「AI検索でGoogle青リンクが消えた理由」解説コンテンツを量産し、新規リード獲得導線を作る
- **期待売上インパクト**：既存クライアント5社×60万円＝300万円の追加受注（3ヶ月以内）

---

### アイデア3：「Claude Voiceで占い自動コンテンツ量産」――陰陽師/占い事業のSNS集客加速

- **対象事業**：陰陽師/占い事業
- **背景**：Claude Voice ModeがCanvaと接続可能になり、音声→コンテンツ→画像まで一気通貫で生成できる
- **具体アクションプラン**：
  1. 毎日の「今日の運勢」「今月の九星気学解説」をClaude Voiceに口述→台本・字幕・Canvaビジュアルまで自動生成するパイプラインを構築（構築期間：1週間）
  2. TikTok・Instagram Reels・YouTube Shortsに週10〜15本ペースで投稿（ほぼ自動）
  3. フォロワー増加後、LINE友だち登録→鑑定予約への導線を整備し、月次鑑定収入を積み上げる
- **期待売上インパクト**：SNS経由で月30〜50件の鑑定予約→月10〜15万円の安定収入基盤。長期的にファネルが育てば月50万円以上も射程圏

---

### アイデア4：「ChatGPT Work × 中小企業向け書類自動化」研修

- **対象事業**：AI研修事業
- **背景**：ChatGPT Workが全プランに展開。1,400コネクタ接続・自然言語指示で資料・Webサイトを自動生成。「使いこなし方がわからない」中小企業が急増
- **具体アクションプラン**：
  1. 「ChatGPT Workで議事録→報告書→提案書を10分で作る」半日ワークショップを設計（教材作成1日）
  2. 愛知県内の商工会議所・法人会・士業（税理士・社労士）に提携を打診し、会員向け研修として開催
  3. ワークショップ参加者に「月次AI活用サポートプラン」（月3〜5万円）としてアップセル
- **期待売上インパクト**：研修1回10人×3万円＝30万円。月2〜3回開催で60〜90万円／月。アップセル含め年間1,000〜1,500万円射程

---

### アイデア5：「Manus Webアプリビルダー × 飲食店DXプロト納品」

- **対象事業**：飲食事業・Web制作事業
- **背景**：ManuのWebアプリビルダーはStripe・DB・SEO統合を内包し、単一プロンプトでWebサービスが動く。飲食店の「オンライン予約・テイクアウト注文・顧客管理」をプロトタイプレベルで超速納品できる
- **具体アクションプラン**：
  1. 自社飲食事業にManus Webアプリビルダーを適用し、予約・注文・顧客管理の自動化プロトを1週間で構築（自社実験）
  2. 「試作事例」をデモとして持ち込み、愛知県内の飲食店2〜3社に月3〜10万円の保守込みパッケージで提案
  3. 「AIで作ったのに本格的」という口コミ・SNS投稿でWeb制作の新規リードに転換
- **期待売上インパクト**：飲食店DXパッケージ5社×月5万円保守＝月25万円の継続収入。制作初期費も1社30〜50万円で取れれば初年度200万円以上

---

## まとめ・今日の最重要アクション

| 優先度 | アクション | 対象事業 | 目安工数 |
|--------|-----------|---------|---------|
| ★★★ | MCP 2026-07-28仕様を確認し、現在の社内Claude設定を更新 | CTO業務 | 2〜3時間 |
| ★★★ | 「AI × 補助金申請パック」の営業資料を作成 | 補助金支援 | 半日 |
| ★★ | 既存Web制作クライアントに「AI検索対応診断」のオファーメール送付 | Web制作 | 1〜2時間 |
| ★★ | Claude Voice × Canvaの占いコンテンツ自動生成パイプラインを試作 | 陰陽師/占い | 半日 |
| ★ | ChatGPT Work研修のコンテンツ設計開始 | AI研修 | 1日 |

---

次回：明日 7:30 AM
