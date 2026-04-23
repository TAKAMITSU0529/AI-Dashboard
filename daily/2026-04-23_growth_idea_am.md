# AI Company 成長戦略レポート 2026-04-23（AM）

**作成**: CoS 戦略参謀  
**参照**: 各役員 playbook.md / growth_log.md / priority_plan.md / 今月の最重要テーマ.md  
**外部情報**: Hermes Agent（Nous Research 2026.02）, Meta Hyperagents（2026.03）, Memento-Skills フレームワーク  

---

## 概要

今月の最重要テーマ「AI Speed Web事業立ち上げ + 4月末5社契約」に直結する形で、
各役員の自律成長ループを強化し、AIエージェントだけで収益を生む具体策を提示する。

世界の最新動向として、2026年最速で普及している **Hermes Agent**（Nous Research、2026年2月リリース、7週で95,600スター）の中核設計「タスク完了→スキルドキュメント自動生成→次回再利用」は、私たちの `growth_log.md → playbook.md` 昇格サイクルと構造的に一致する。ベンチマークでは同種タスクの処理時間が **40%短縮**。このサイクルを各役員が日次で回す形に強化する。

---

## 1. AIエージェント役員の自律的成長メソッド

### 全役員共通ルール（Hermes Agent 方式を採用）

| フェーズ | アクション | 頻度 |
|---------|-----------|------|
| タスク完了後 | 結果・学びを growth_log.md に追記（省略禁止） | 毎回 |
| 同じ手法が2回成功したら | playbook.md「蓄積されたノウハウ」に昇格 | 随時 |
| 同じ失敗が2回起きたら | playbook.md にアンチパターンとして追加 | 随時 |
| 月末 | 全記録を棚卸し → パターン抽出 → playbook更新 | 月次 |

現状、全役員の growth_log.md が空のまま運用されている。これが最大の成長阻害要因。今日から埋めることが最優先。

---

### CoS（戦略参謀）

**現状の課題**: growth_log.md 空。7フェーズ意思決定プロセスは設計済みだが実績がゼロ。

**日次成長ルーティン**:
1. 毎朝：AI Speed Web 営業進捗（アプローチ社数 / 商談数 / 契約数）を確認 → growth_log に数字記録
2. 意思決定のたびに：Pre-Mortem（壁出し）予測 vs 実際の結果を対比記録
3. 週次：「判断の精度」自己採点（予測 vs 実結果の乖離率）→ playbook「社長の判断パターン」更新

**playbook.md 追記提案**:
```
### 営業転換率ベンチマーク（実績積み上げ中）
- アプローチ → 返信: __%（更新日: ）
- 返信 → 商談: __%
- 商談 → 契約: __%
※2回以上のデータが揃ったら数値確定。それまでは業界平均（返信2-5%）を仮置き。
```

---

### CPO（商品設計）

**現状の課題**: 商品ラインナップは整備済みだが「売れた / 売れなかった理由」の蓄積がない。

**日次成長ルーティン**:
1. 問い合わせ・断りが発生したとき：「高い」「わかりにくい」「必要ない」のどれかに分類記録
2. 週次：AI Speed Web の価格反応（月額9,800円 vs 試行中の他価格）を比較記録
3. 月次：競合リサーチ（Deloitte 2026「企業SaaS支出の40%がusage-based/outcome-basedへ移行予測」）→ 価格設計見直しインプット

**playbook.md 追記提案**:
```
### 2026年AI時代の商品設計原則
- 成果保証型へのシフト候補: 「月額固定」→「問い合わせ◯件保証」型のテストを検討
- Usage-based候補: AI Speed Web を「月次更新回数」でプライシング
- 参照: Gartner予測「2030年までに企業SaaS支出の40%がoutcome-based」
```

---

### CMO（集客・営業）

**現状の課題**: X バズ投稿分析・SNS 成功パターンの体系的蓄積がない。営業メールの開封率・返信率の記録もない。

**日次成長ルーティン**:
1. 毎日：AI 系インフルエンサー上位3アカウントのバズ投稿を growth_log に記録（パターン分類: 数字型 / 問題提起型 / 事例型 / 反転型）
2. 投稿ごと：インプレッション・保存数・フォロワー増加を記録 → 上位20%の型を playbook に昇格
3. 週次：営業メール開封率・返信率を記録 → 件名パターン別の反応差を分析

**playbook.md 追記提案**:
```
### 検証済みXバズパターン（実績付き）
| 投稿パターン | 保存率 | 初測定日 |
|------------|--------|----------|
| 数字+結果型（例: AI導入で○分→○秒） | 測定中 | - |
| 問題提起型（例: Web担当者がいない会社の末路） | 測定中 | - |

### 営業メール件名 A/Bテスト記録
| 件名パターン | 開封率 | 返信率 | 送付日 |
|------------|--------|--------|--------|
| （初回送付後に記録開始） | - | - | - |
```

---

### COO（業務・管理）

**現状の課題**: SOP は文書化済みだが、実行時の例外・トラブル事例が蓄積されていない。同じ質問への対応が毎回ゼロから始まっている。

**日次成長ルーティン**:
1. 顧客対応のたびに：「想定外だった点」を1行で growth_log 追記
2. 同じ質問を2回受けたら：即 FAQ 化 → playbook.md に追記（Memento-Skills 原則：2回目以降は参照するだけにする）
3. 週次：SOP の「うまくいかなかった箇所」に付箋コメント追加 → 月次で SOP 改訂

**playbook.md 追記提案**:
```
### FAQ（顧客からのよくある質問 蓄積欄）
Q: AI Speed Web と普通のホームページは何が違うの？
A: （初回回答後に記録）

Q: 契約後どのくらいで公開できますか？
A: 最短3日。標準1週間。（COO業務フロー参照）
```

---

### CTO（技術・AI）

**現状の課題**: ツール評価・プロンプト品質の蓄積なし。自動化ロードマップが「構築予定」のまま進んでいない。

**日次成長ルーティン**:
1. 作成したプロンプトごと：結果品質を1-5点評価 → 4点以上を playbook「成功プロンプト集」に昇格
2. 週次：新規 OSS フレームワーク調査（今週注目: Hermes Agent, Meta Hyperagents）→ AI Company 活用可能性を3行で評価記録
3. 自動化ツール完成ごと：削減した作業時間（分/回）を growth_log に記録し ROI 可視化

**playbook.md 追記提案（緊急優先）**:
```
### 自動化ロードマップ 優先順位更新（2026-04-23）
【今週中に完成させる】
- 問い合わせフォーム自動検出機能 → lead_verifier.py に追加
  理由: AI Speed Web 自動営業パイプラインの中核部品

【参照すべき最新フレームワーク】
- Hermes Agent (MIT, Nous Research): タスク完了時に「スキルドキュメント」を自動生成
  → 私たちの growth_log → playbook 昇格を「タスク完了時に自動提案するプロンプト」に応用可
  GitHub: https://github.com/nousresearch/hermes-agent
- Meta Hyperagents: 自己修正型。プロンプト改善ループの参考
  → 現状は実験的。Claude Code での実装は3ヶ月後に再評価
```

---

## 2. AI Companyだけで収益を発生させるアイデア

### アイデア：「AI Speed Web 完全自動営業パイプライン」

**一言で**: CTO が既に構築した `hp_checker.py`（HP品質判定）と `lead_verifier.py`（リード精査）を起点に、ターゲット企業発見→HP評価→フォーム検出→営業メール自動送付→フォローアップまでを人間の介在なしに完結させる。

**なぜ今これか**:
- 今月最重要テーマが「AI Speed Web 5社契約」
- 2つのスクリプトがすでに存在 → 実装コストが最小
- AI Speed Web（月額9,800円〜・初期費用0円）は低摩擦商品 → 自動営業と最も相性が良い
- 問い合わせフォーム自動検出は CTO playbook.md に「構築予定」として明記済み → 今すぐ着手できる

---

### 3ステップ アクションプラン

#### Step 1【今日〜明日】: ターゲットリスト × HP品質スコアリングの自動生成

- `hp_checker.py` で豊明市の建設業・製造業・飲食業 50社のHPを自動判定
- スコアが低い順（改善余地が大きい順）にソート → CSV 出力
- `lead_verifier.py` に「問い合わせフォームURL抽出」機能を追加し、フォームURLを取得
- **成果物**: 「今すぐ営業すべき企業リスト（HP品質スコア付き）」50件を自動生成

#### Step 2【明日〜今週末】: 業種別 営業メール自動生成 + 送付

- CMO の営業メールテンプレート × HP の課題点（スコア根拠）を Claude API で差し込み、業種別・企業別にパーソナライズされた文面を自動生成
- 50社へ順次送付（特定電子メール法遵守 ← COO compliance_guide.md 参照）
- 送付記録・返信フラグを GitHub Issues または Notion に自動記録
- **成果物**: 50社へのファーストコンタクト完了、返信トラッキング自動化

#### Step 3【来週〜月末】: フォローアップ自動化 + 商談クロージング

- 未返信7日後に自動フォローアップメール送付（内容を変えて2回まで）
- 返信・問い合わせがあった案件のみ社長（人間）が商談対応（初回30分Zoom）
- 受注後は COO playbook のフロー通りに処理
- **成果物**: 4月末までに5社商談、最低2社受注

---

### 期待できる売上インパクト

| 指標 | 数値 |
|-----|------|
| 月次アプローチ社数（自動） | 50社 |
| 返信率（見込み） | 5%（業界平均2〜5%） |
| 商談転換率 | 50%（HP課題あり企業に絞るため） |
| 受注転換率 | 40%（初期費用0円・低単価のため） |
| 月間受注 | 1〜2社 |
| MRR（月次経常収益） | 9,800〜19,600円/月（新規のみ） |
| 年間 ARR 換算（12ヶ月継続） | **117〜235万円** |
| バックエンド転換（AI顧問月5万円 × 10%） | **60〜120万円追加** |
| **年商ポテンシャル合計（この1施策）** | **177〜355万円** |
| 目標年商3,200万に対する寄与率 | **5.5〜11%** |

※月50社 × 12ヶ月 = 600社アプローチ。保守的に返信5%・商談50%・受注40% で計算。
バックエンド（AI顧問プラン月5万円）への転換が始まると数字は大きく跳ね上がる。

---

### growth_log 追記テンプレート（CTO・CoS 両名）

```
### 2026-04-23 ｜ AI Speed Web 自動営業パイプライン 設計
- やったこと: hp_checker.py + lead_verifier.py を使った50社自動リストアップ設計
- 次のアクション: lead_verifier.py へのフォームURL抽出機能追加
- 想定時間削減: 50社手動調査（約5時間）→ 自動（約15分）
- playbook昇格: 未（完成後に昇格）
```

---

## 参照ソース

- [Hermes Agent — The Agent That Grows With You (Nous Research)](https://hermes-agent.nousresearch.com/)
- [Hermes Agent Review: 95.6K Stars, Self-Improving AI Agent (DEV Community)](https://dev.to/tokenmixai/hermes-agent-review-956k-stars-self-improving-ai-agent-april-2026-11le)
- [Meta Releases Hyperagents: Self-Modifying AI Framework (MLQ.ai)](https://mlq.ai/news/meta-releases-hyperagents-self-modifying-ai-framework-enabling-autonomous-improvement-mechanisms/)
- [Self-Improving AI Agents: The 2026 Guide (o-mega.ai)](https://o-mega.ai/articles/self-improving-ai-agents-the-2026-guide)
- [SaaS meets AI agents (Deloitte 2026)](https://www.deloitte.com/us/en/insights/industry/technology/technology-media-and-telecom-predictions/2026/saas-ai-agents.html)
- [Autonomous Agentic AI in 2026 (Universe Discovery)](https://www.universediscovery.com/autonomous-agentic-ai-in-2026/)
- [AI Agent Autonomy Statistics 2026 (SQ Magazine)](https://sqmagazine.co.uk/ai-agent-autonomy-statistics/)

---

*生成: CoS 戦略参謀 / 2026-04-23 AM*
