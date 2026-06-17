# AI情報ブリーフィング R8-0618（2026-06-18）
作成：AI Company CTO（技術・AI担当）

---

## ① AIニュースTop5

### 1. OpenAI、ChatGPTに「スケジュールタスク」機能を本日投入——定期実行・監視タスクをAIに任せられる
**要約：**
OpenAIは6月17日、ChatGPTに「Scheduled Tasks」（スケジュールタスク）機能の本格展開を開始。サイドバーに新設された「Scheduled」ページから、リマインダー送信・定型業務の処理・状況監視を指定時刻または時間帯（朝・昼・夕方など）で予約実行できる。監視タスクはWeb検索や連携アプリの変化を自動チェックし、「報告すべき変化があったときだけ」通知する設計。Go・Plus・Pro・Business・Enterpriseの全プランでWeb／モバイルに展開済み。

**重要性：**
- **補助金支援事業**：締切管理・申請進捗の自動監視（「公募要領が更新されたら通知」等）をChatGPT単体で組めるようになり、追加ツール導入なしで業務効率化を提案できる。
- **AI研修事業**：「予約実行で人手を介さず定型業務を回す」という最も分かりやすいAI活用例として研修の初回デモに最適。Zapier等の外部ツール無しで体験させられるため導入障壁が低い。
- **飲食・マーメイド事業**：予約確認・在庫チェックリマインドなど社長自身の事業にもすぐ試せる規模の機能。

**ソース：** https://9to5mac.com/2026/06/17/openai-launches-scheduled-tasks-in-chatgpt-details-here/ | https://help.openai.com/en/articles/6825453-chatgpt-release-notes

---

### 2. Google、Gemini Omni・Gemini 3 Deep Thinkの本格展開を加速——マルチモーダル統合と高度推論モードが同時進行
**要約：**
Googleは5月のI/O 2026で発表した「Gemini Omni」（音声・画像・動画を統合的に扱うマルチモーダルAI）の一般展開を6月に拡大。Gemini AI Plus/Pro/Ultra利用者にGoogle FlowやYouTube Shorts Remix経由で提供範囲を広げている。同時に最上位の推論モード「Gemini 3 Deep Think」（数学・科学・論理など多段階の難問向け）をAI Ultra会員に展開開始。なお6月17日には一部ユーザーでGeminiの障害も報告された。

**重要性：**
- **動画・デザイン事業**：Gemini Omniによる音声・画像・動画の統合生成は、店舗メニュー動画や陰陽師事業の鑑定動画コンテンツ制作の自動化候補になる。
- **AI研修事業**：「軽量タスクはOmni、難問はDeep Think」という使い分けは、Claudeの階層型運用（Opus/Sonnet/Haiku）と同じ構造の教材として横展開できる。

**ソース：** https://blog.google/products/gemini/gemini-3/ | https://gemini.google/release-notes/ | https://community.designtaxi.com/topic/31198-is-google-gemini-down-june-17-2026/

---

### 3. Anthropic、Claude PlatformをAWSで一般提供開始——AWS Summit NYC 2026でClaude Code活用ワークショップを実施
**要約：**
AnthropicはAWS認証・課金・監視基盤を使ってClaudeのフルAPI機能（マネージドエージェント、コード実行、Web検索、プロンプトキャッシュ、Skills・MCPコネクタ等）に直接アクセスできる「Claude Platform on AWS」を一般提供開始。6月17日開幕のAWS Summit New York 2026（ジャビッツセンター）では、Claude Codeの実践ワークショップをオンライン・現地で実施。背景には、SpaceXとのコンピュート契約（Colossus 1データセンターの全キャパシティ利用、Nvidia GPU 22万基以上）や、Amazon・Google・Microsoftとの大型クラウド契約があり、Claudeの処理能力増強が続いている。

**重要性：**
- **AI研修事業**：「AWS経由でClaudeを使う」企業が増えると想定されるため、AWS基盤を前提にした研修・導入支援メニューの整備が次の差別化ポイントになる。
- **補助金支援事業**：AWS・Anthropicという大手の協業強化は「実績ある安定基盤」として補助金申請書の信頼性訴求材料に使える。

**ソース：** https://www.anthropic.com/events/anthropic-at-aws-summit-nyc-2026 | https://thenewstack.io/anthropics-claude-platform-comes-to-aws/ | https://www.anthropic.com/news/higher-limits-spacex

---

### 4. Microsoft、OpenClaw基盤の自律エージェント「Scout」をMicrosoft 365に統合——Windowsを「AIエージェントのOS」に再定義
**要約：**
Microsoftは無償オープンソースの自律型AIエージェント「OpenClaw」（GitHubスター31万件超）の技術を基盤にした常時稼働型エージェント「Scout」を発表し、Teams・Outlook・OneDrive・SharePointと連携して会議調整・期限管理・リスク検知を自律的に行う。各エージェントは固有のEntra ID（個別認証情報）で管理され、操作ログが追跡可能な「ガバナンス型」設計が特徴。現在はFrontier組織向けの限定プレビュー。OpenClaw自体も2026.6.8版でTelegram/WhatsApp連携強化・モデルルーティングの安全性向上を実施し、大手3社（Microsoft・Google・Meta）が同様の機能を相次いで取り込む動きが継続中。

**重要性：**
- **AI研修事業**：「無償OSSのOpenClaw技術が大手の標準機能に格上げされた」という事例は、無料ツール導入の説得材料として説得力が高い。中小企業向け「OpenClaw実践研修」の企画価値が上がった。
- **業務効率化（COO領域）**：会議調整・期限管理の自動化は、自社の役員間連携や顧客対応の自動化設計にそのまま参考になる。

**ソース：** https://techcrunch.com/2026/06/02/microsoft-launches-scout-an-openclaw-inspired-personal-assistant/ | https://www.microsoft.com/en-us/microsoft-365/blog/2026/06/02/introducing-microsoft-scout-your-always-on-personal-agent/ | https://releasebot.io/updates/openclaw

---

### 5. Meta、Manus買収の白紙撤回を実行段階へ——データアクセス遮断・組織分離が完了
**要約：**
2025年12月に約2,000億円（20億ドル）で合意していたMetaによるManus（シンガポール発の自律型AIエージェント）買収は、中国当局の介入で4月に契約解消が命じられていたが、6月11日にMetaがManusとの業務分離を完了したとBloombergが報道。Metaは6月初めからManusおよびそのスタッフによる自社内部データシステムへのアクセスを遮断し、6月15日には正式に関係解消を発表した。Manusは単一モデルに依存せず、Claudeを中心に複数LLMをオーケストレーション（指揮制御）する設計を継続している。

**重要性：**
- **CTO/自動化事業**：2,000億円規模の買収が地政学リスクで完全に解体された事例は、「特定の海外プラットフォームに事業の中核を依存させない」設計思想の重要性を示す実例。自社の自動化エージェント設計（複数AI併用・データの自社管理）の方針強化材料になる。
- **AI研修事業**：「巨大買収が国家の介入で白紙撤回された」というニュース性の高い実例は、AIリスク管理研修のオープニング教材として使える。

**ソース：** https://www.bloomberg.com/news/articles/2026-06-11/meta-severs-manus-data-access-after-china-orders-buyout-unwound | https://en.wikipedia.org/wiki/Manus_(AI_agent)

---

## ② マイクロ法人 × AI活用で大きく稼いでる事例 5選

### 事例1：Maor Shlomo（イスラエル）— 設立6ヶ月・社員8名のAIアプリ開発スタートアップをWixが約120億円で買収
- **誰が：** Maor Shlomo、31歳。イスラエル人エンジニア
- **何を：** Base44（プログラミング知識不要でWeb・アプリ・ゲームを自然言語の指示だけで作れるAI開発プラットフォーム＝「バイブコーディング」ツール）
- **どうやって：** 2025年初頭に1人で開発開始。LinkedIn・Xで開発過程を発信する「ビルディング・イン・パブリック」戦略でユーザーを広告に依存しない自然な拡散で獲得。数週間で25万〜30万ユーザーに到達し、eToro・SimilarWebなどB2B顧客も獲得。最終的に社員8名まで増員
- **何を活用：** 自社開発のAIコード生成基盤（プロンプトからアプリを自動生成）
- **どのように稼いだか：** ARR（年間継続収益）約3.5百万ドル（約5億2,500万円）。設立6ヶ月でWixが約80百万ドル（約120億円）の現金で買収。さらに業績目標達成時に追加90百万ドル（約135億円）の獲得が見込める。社員8名は買収額のうち25百万ドル（約37億円）をリテンションボーナスとして受領
- **社長の事業への応用：** **AI研修事業**→「ノーコードAIアプリ開発（バイブコーディング）」は中小企業の自社ツール開発研修として直接商品化できる。「6ヶ月で買収された」という実例はAI活用の投資対効果（ROI）訴求に使える

**ソース：** https://techcrunch.com/2025/06/18/6-month-old-solo-owned-vibe-coder-base44-sells-to-wix-for-80m-cash/ | https://www.calcalistech.com/ctechnews/article/hjm11dastwl

---

### 事例2：Pieter Levels（オランダ人・世界各地で活動）— 社員ゼロで複数のAIプロダクトを運営し年商4.5〜7.5億円
- **誰が：** Pieter Levels（通称levelsio）、オランダ人エンジニア。ノートPC1台で世界を移動しながら運営する「ノマド起業家」の代表格
- **何を：** PhotoAI（AIプロフィール写真生成）、NomadList（ノマド向け都市情報）、RemoteOK（リモート求人サイト）等、複数のAIプロダクトを並行運営
- **どうやって：** 70個以上のプロダクトを試作・失敗させてきた中で生き残った数本に絞り、社員を雇わず自分1人で開発・運用・カスタマーサポートまで対応。SNSでの発信を集客チャネルとして活用
- **何を活用：** 自社開発のAI画像生成パイプライン、SEO中心の集客設計
- **どのように稼いだか：** PhotoAI単体で月商約1,320万〜1,380万円（13.2万〜13.8万ドル）、ARR約1.6〜1.65億円。プロダクト全体では年商約3〜5百万ドル（約4.5〜7.5億円）
- **社長の事業への応用：** **Web制作事業**→「1人で複数の小規模AIプロダクトを並行運営し、当たった数本で稼ぐ」モデルは、陰陽師・占い事業や飲食事業向けの診断ツール・予約ツールを次々試作する社内の実験的開発方針として転用できる

**ソース：** https://www.indiehackers.com/post/photo-ai-by-pieter-levels-complete-deep-dive-case-study-0-to-132k-mrr-in-18-months-3a9a2b1579 | https://ppc.land/how-one-photo-ai-app-generates-132k-monthly-after-70-failed-startups/

---

### 事例3：Dana Snyder（米国）— ノーコード開発で「AIコンサルタント」を製品化し、社員ゼロで対応可能な顧客数を拡大
- **誰が：** Dana Snyder、米国人。非営利団体向けコンサルティング会社Positive Equationの創業者。プログラミング未経験
- **何を：** 寄付プログラム設計を自動化するAIプラットフォーム（自身のコンサルティングの型・知見をAIエージェントに組み込み、団体ごとに資金調達戦略・寄付者コミュニケーション計画・プログラム名まで自動生成）
- **どうやって：** Replit（ノーコードでアプリを作れるAI開発ツール）を使い、約6ヶ月かけて自分のノウハウをソフトウェア化。「専門コンサルタントを雇う予算のない非営利団体（米国の非営利団体の約93%が該当）」という、これまで相手にできなかった市場層に低価格でリーチ
- **何を活用：** ReplitのAIコーディング機能、自身の経験を組み込んだAIエージェント
- **どのように稼いだか：** 売上額は不明（公開情報なし）。ただし対応可能な顧客数が個人コンサル時代より大幅に拡大し、現在も社員はSnyder1人のまま運営継続中
- **社長の事業への応用：** **補助金支援事業**→「自分の申請ノウハウをAIに組み込んで製品化し、これまで断っていた低単価・小規模事業者層にもリーチする」モデルは、補助金支援の低価格プラン展開に直接応用できる（CLAUDE.mdの方針通り、売上額は推測せず「不明」と明示）

**ソース：** https://fortune.com/2026/05/18/solo-founders-ai-automation-entire-teams-entrepreneurs/ | https://positiveequation.com/about

---

### 事例4：Noah Morris（米国）— 19歳で開始した「フェイスレスYouTube」を20チャンネル・250万人規模に拡大し7桁ドルの売上
- **誰が：** Noah Morris、米国人。YouTube自動化スクール「NexLev」運営者
- **何を：** 顔を出さない「フェイスレスYouTube」チャンネルを20チャンネル運営（裁判事件解説・ナレーション動画など）
- **どうやって：** 本人は出演せず、AI音声・AI字幕生成・自動動画編集を組み合わせ、40名超の外部スタッフ（脚本・編集・ナレーション担当の業務委託）を統括する「司令塔型」運営。1本あたりの制作費は約250ドル（約3.7万円）に圧縮しながら、ある裁判動画は500万再生・2万ドル（約300万円）の収益を記録
- **何を活用：** AI音声合成、AI動画編集ツール、AI字幕・多言語吹き替え
- **どのように稼いだか：** 月商約8万〜15万ドル（約1,200万〜2,250万円）、年商は7桁ドル（1億円超）規模
- **社長の事業への応用：** **動画・デザイン事業**→「自分は出演せず、AIツール＋少人数の業務委託で動画を量産する司令塔モデル」は、陰陽師事業の鑑定解説動画やマーメイド事業の集客動画を社長自身が出演せずに量産する設計として転用できる

**ソース：** https://www.nexlev.io/youtube-automation | https://miraflow.ai/blog/faceless-youtube-channel-explosion-ai-million-subscriber-creators-2026

---

### 事例5：Matthew Gallagher（米国・ロサンゼルス）— 自己資金20万円・社員2名のテレヘルス事業が2026年に2,700億円規模へ
- **誰が：** Matthew Gallagher、米国人起業家。2024年9月、自宅から2万ドル（約300万円）の自己資金で起業
- **何を：** Medvi（GLP-1（肥満治療薬）のオンライン処方・配送サービス）
- **どうやって：** 規制対象の医療部分（医師診察・処方・薬局配送・コンプライアンス）はCareValidate・OpenLoop Healthに外部委託し、自社は顧客接点のみ保持。社員は実弟Elliotの1名のみ（合計2名）で運営
- **何を活用：** ChatGPT・Claude・Grokでコード生成・マーケティング文章作成・Webサイト構築・カスタマーサポートまで対応
- **どのように稼いだか：** 初年度売上4億1,000万ドル（約601億円）、顧客25万人、純利益率16.2%。2026年は18億ドル（約2,700億円）規模に到達見込み
- **社長の事業への応用：** **陰陽師・占い事業／マーメイド事業**→鑑定・施術など「資格・専門スキルが必要な核心業務」は提携パートナー（霊視者・専門スタッフ）に任せ、社長自身はAIで集客・予約・顧客対応の仕組み化に専念する「ハイブリッド外部委託モデル」をそのまま転用できる

**ソース：** https://www.pymnts.com/artificial-intelligence-2/2026/the-one-person-billion-dollar-company-is-here/ | https://wealthytent.com/one-person-billion-dollar-startup-ai

---

## ③ 社長の事業に直結する実践AIアイデア 5選

### アイデア1：ChatGPT「スケジュールタスク」で無料AI業務診断のフォローアップを自動化し、商談化率を上げる
**対象事業：** AI社員導入事業（今月の最優先）

**具体アクションプラン：**
1. **今週：** 無料AI業務診断を実施した相手ごとに、ChatGPTのScheduled Tasksで「診断3日後に状況確認メッセージ案を自動生成」するタスクを設定し、商談化への動線を仕組み化する
2. **来週：** 知人経営者4名への声かけ後、未回答者へのフォロー文面案を毎週自動生成させ、声かけの取りこぼしを防ぐ
3. **来月：** 車屋案件のクロージング後、契約後フォロー（運用状況確認・追加提案タイミング）もスケジュールタスク化し、運用支援への自然な移行を作る

**期待売上インパクト：** 今月のKPI（無料診断3〜5件・商談1〜2件）の達成率を上げる仕組みのため、直接の売上換算は不可。本命の車屋クロージング（提案中の金額帯：お試しパック10〜30万円）の確度を上げる位置づけ

---

### アイデア2：Base44型「バイブコーディング」をAI社員お試し導入パックのデモに組み込み、即日で「動くもの」を見せる
**対象事業：** AI社員導入事業（今月の最優先）

**具体アクションプラン：**
1. **今週：** 車屋向けの商談で、Claude Codeを使い「予約受付フォーム」や「車検見積もりチェッカー」など即日で動くミニツールをその場で生成し、口頭提案ではなく「動くデモ」を見せる
2. **来週：** 知人経営者4名への診断時も同様に、診断結果をもとに5分でミニツールのプロトタイプを生成し、「導入後の姿」を具体的に体感してもらう
3. **来月：** お試し導入パックの標準フローに「初回商談でその場デモ生成」を組み込み、型化する

**期待売上インパクト：** 「資料だけ」より成約率が上がる想定（業界経験則で1.5〜2倍）。車屋案件（お試しパック10〜30万円）の受注確度向上に直結

---

### アイデア3：Manus型「複数AI併用設計」を車屋AI社員導入パックの安心材料として明記する
**対象事業：** AI社員導入事業（今月の最優先）

**具体アクションプラン：**
1. **今週：** 車屋向け提案書に「特定の海外AI企業1社に依存しない設計（Claude＋必要に応じ他モデル併用）」という一文を追加し、ベンダーロックインへの懸念に先回りで答える
2. **来週：** 知人経営者への診断資料にも同様の「依存リスク対策」記載を追加し、専門性の高さを訴求する
3. **来月：** Mac mini AI役員パッケージ（社長の頭の中メモにある車屋オーナーの2つ目の要望）の提案書にも同じ考え方を組み込む

**期待売上インパクト：** 直接の売上増ではなく、契約への心理的ハードルを下げる効果。車屋クロージングの確度向上に寄与

---

### アイデア4：Dana Snyder型「自分の診断ノウハウのAI製品化」を無料AI業務診断ツールの型として横展開
**対象事業：** AI社員導入事業（今月の最優先）

**具体アクションプラン：**
1. **今週：** 既存の診断MVP（Googleフォーム＋Notion＋Claude）に、過去の診断結果から見えた「業種別のAI化候補パターン」をプロンプトに組み込み、診断精度を上げる
2. **来週：** 知人経営者4名への診断で実際に使い、回答の質と商談への転換率を記録する
3. **来月：** 診断後の「優先順位リスト」生成を自動化し、社長が手を動かさずに診断件数を増やせる体制にする

**期待売上インパクト：** 診断対応可能件数が増えることで、今月目標（診断3〜5件→来月以降は件数拡大）の土台を作る。直接の売上はお試し導入パック成約（10〜30万円）に連動

---

### アイデア5：Noah Morris型「AI×外部委託の司令塔モデル」を陰陽師・マーメイド事業の集客動画に試験導入
**対象事業：** 陰陽師・占い事業／マーメイド事業（7月以降の事業化検討・今月は軽量対応のみ）

**具体アクションプラン：**
1. **今週：** AI音声・AI字幕で鑑定内容を解説する短尺動画を1本試作し、社長自身は出演せず仕組みだけ作る（今月方針「AI社員導入1本」に支障が出ない範囲の軽量対応に限定）
2. **来週：** 反応を見て、霊視パートナーの実績紹介動画にも同フォーマットを展開
3. **7月以降：** 反応が良ければ業務委託（編集者1名）を加えて量産体制を検討。6月中の新規事業化はしない

**期待売上インパクト：** 今月は実験のみのため売上インパクトは限定的（0〜数万円規模）。7月以降の事業化判断材料として位置づけ、今月の最優先（車屋クロージング・知人診断）を阻害しない範囲で実施

---

*次回：明日 7:30 AM*

---
> 情報ソース一覧
> - 9to5Mac（ChatGPT Scheduled Tasks）: https://9to5mac.com/2026/06/17/openai-launches-scheduled-tasks-in-chatgpt-details-here/
> - OpenAI Help Center（ChatGPT Release Notes）: https://help.openai.com/en/articles/6825453-chatgpt-release-notes
> - Google Blog（Gemini 3）: https://blog.google/products/gemini/gemini-3/
> - Google（Gemini Apps Release Notes）: https://gemini.google/release-notes/
> - DesignTAXI Community（Gemini障害報告）: https://community.designtaxi.com/topic/31198-is-google-gemini-down-june-17-2026/
> - Anthropic（AWS Summit NYC 2026イベント）: https://www.anthropic.com/events/anthropic-at-aws-summit-nyc-2026
> - The New Stack（Claude Platform on AWS）: https://thenewstack.io/anthropics-claude-platform-comes-to-aws/
> - Anthropic（SpaceXコンピュート契約・利用上限緩和）: https://www.anthropic.com/news/higher-limits-spacex
> - TechCrunch（Microsoft Scout発表）: https://techcrunch.com/2026/06/02/microsoft-launches-scout-an-openclaw-inspired-personal-assistant/
> - Microsoft 365 Blog（Scout紹介）: https://www.microsoft.com/en-us/microsoft-365/blog/2026/06/02/introducing-microsoft-scout-your-always-on-personal-agent/
> - Releasebot（OpenClawリリースノート）: https://releasebot.io/updates/openclaw
> - Bloomberg（Meta、Manusとのデータ連携遮断）: https://www.bloomberg.com/news/articles/2026-06-11/meta-severs-manus-data-access-after-china-orders-buyout-unwound
> - Wikipedia（Manus AI agent）: https://en.wikipedia.org/wiki/Manus_(AI_agent)
> - TechCrunch（Base44のWix買収）: https://techcrunch.com/2025/06/18/6-month-old-solo-owned-vibe-coder-base44-sells-to-wix-for-80m-cash/
> - Calcalistech（Base44創業者Maor Shlomoの追加報酬）: https://www.calcalistech.com/ctechnews/article/hjm11dastwl
> - Indie Hackers（Pieter Levels／PhotoAI事例）: https://www.indiehackers.com/post/photo-ai-by-pieter-levels-complete-deep-dive-case-study-0-to-132k-mrr-in-18-months-3a9a2b1579
> - PPC Land（PhotoAI月商詳細）: https://ppc.land/how-one-photo-ai-app-generates-132k-monthly-after-70-failed-startups/
> - Fortune（Dana Snyder／Positive Equation事例）: https://fortune.com/2026/05/18/solo-founders-ai-automation-entire-teams-entrepreneurs/
> - Positive Equation（公式サイト）: https://positiveequation.com/about
> - NexLev（Noah Morris公式・YouTube自動化）: https://www.nexlev.io/youtube-automation
> - Miraflow（フェイスレスYouTube動向）: https://miraflow.ai/blog/faceless-youtube-channel-explosion-ai-million-subscriber-creators-2026
> - PYMNTS（Medvi／Matthew Gallagher事例）: https://www.pymnts.com/artificial-intelligence-2/2026/the-one-person-billion-dollar-company-is-here/
> - Wealthy Tent（Medvi詳細）: https://wealthytent.com/one-person-billion-dollar-startup-ai
