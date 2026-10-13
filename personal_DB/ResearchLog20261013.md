# Research / Work Log — 2026-10-13 (Tuesday)

## 日本語

### 今日の概要

10月13日（火）。

普通種の生息地チェックコードの修正から始まり、PNAS投稿予定原稿の確認、国際漁業学IIの提出締切の確定、予定外の事務処理、若手研究者との研究相談、Ecology and Evolutionの査読受諾、ニューカレドニアの研究者との意見交換を行った。

当初は、これらの仕事を終えてTMBSSの開発に戻る予定だったが、連休明けでメールや事務指示が多く、まとまった研究時間を確保できなかった。

**TMBSSの再開は10月14日に持ち越すこととした。**

一方、若手研究者との会話を通じて、安定同位体分析、資源評価、CPUE標準化など、現在進めている複数の研究テーマの接点について考える機会があった。

---

## 1. 普通種の生息地チェックプログラム

前日に作成した普通種の分布・生息地データのチェックプログラムについて、ChatGPTと修正作業を行った。

今回の作業は、データの確認・整理を目的としたものであり、解析結果の解釈や論文化にはまだ進んでいない。

今後の解析に向けたデータ処理環境の整備として位置づける。

---

## 2. PNAS原稿の確認

午前中に、共著のPNAS投稿予定原稿のチェックを完了した。

本日の予定では優先順位の高い仕事として位置づけており、午前中に確認を終えることができた。

原稿の具体的な修正内容については、本日の記録では詳細を残さない。

---

## 3. 広島大学・国際漁業学II

10月12日時点で未提出だった学生1名について、10月13日の朝まで提出を待った。

しかし、追加提出はなかったため、**国際漁業学IIのレポート提出を締め切った。**

1名が未提出のままとなったことは残念だが、これ以上は待たずに成績処理を進める。

今後は国際漁業学I・IIの採点結果を最終確認し、10月23日の成績提出期限までに処理する。

採点は引き続き自分自身で行う。

---

## 4. 予定外の事務処理

連休明けということもあり、メールや事務指示が多かった。

午後、新たな事務処理が1件発生したため、約1時間半かけて必要な作業を行った。

作成した内容は部下に確認を依頼した。

現在の状況は以下のとおり。

- 自分の作業：ひとまず完了
- 部下による内容確認：依頼済み
- 今後：確認結果を受けて再チェックし、提出

したがって、案件全体としてはまだ完了していないが、自分の作業はいったん区切りがついた。

こうした予定外の業務が断続的に発生するため、長時間の集中を必要とする研究作業への移行は難しかった。

---

## 5. Fisheries Research投稿論文のリジェクト

前日、共著のマサバ生物特性に関する論文がFisheries Researchでリジェクトされたとの連絡があった。

この論文は、近年約10年間のマサバの生物特性を丁寧に取りまとめた研究である。

リジェクトの主な理由は新規性の不足とされている。

データの蓄積や整理は丁寧に行われているが、掲載誌が求める新規性との間に隔たりがあったと考えられる。

今後は**Regional Studies in Marine Science（RSMA）に投稿する予定**とのこと。

RSMAの編集委員を務めているが、共著論文はシステム上、自分の担当には割り当てられない。

若手研究者には今回の結果を引きずらず、次の投稿へ進んでもらう。

また、RSMAのImpact FactorがFisheries Researchよりやや高い一方で、掲載論文の質については必ずしも同じ印象を持っていない。

Impact Factorと個々の論文の質、編集・査読の厳格さは必ずしも一致しないという問題を改めて考えた。

---

## 6. 若手研究者との研究交流

今日は、複数の若手研究者とネット・チャットを通じて研究上の意見交換を行った。

### 6.1 安定同位体分析と多次元解析

若手研究者とMixSIARについて議論した。

主な話題は、エンドメンバーや濃縮係数（TEF）の設定によって推定結果が大きく変わること、混合モデルの結果をどこまで識別できるかという問題であった。

自分自身は最近、2次元ガウス混合モデル（2D-GMM）の識別性について検討していることを伝えた。

さらに、アミノ酸組成や脂肪酸組成などの多次元データを利用した解析にも関心がある。

多次元解析については、単純に変数を増やすだけではなく、データ構造に適した統計モデルを考える余地がある。

候補としては、多変量混合モデル、潜在因子モデル、組成データ解析などが考えられるが、具体的な方法はデータの性質を確認してから検討する。

特に重要なのは、**統計的に分類できることと、その分類を生み出した生態学的過程を理解できることは異なる**という点である。

この問題はGMCSやIsoMoveとも共通する。

### 6.2 資源評価、体長組成、CPUE標準化

別の若手研究者とは、マダイの資源評価について意見交換した。

主な話題は以下のとおり。

- マダイの体長組成データの再確認
- 成長などの生物特性の見直し
- 生物特性の設定がCAA（年齢別漁獲尾数）に及ぼす影響
- 漁業種類別の体長組成の利用
- CPUEの精度と資源評価への影響
- CPUE標準化と状態空間モデルの関係

特に、体長組成や成長パラメータの設定によってCAAが大きく変わる可能性について議論した。

資源評価モデルを高度化しても、入力データの作成過程が不明確であれば、結果の解釈は難しくなる。

また、CPUE標準化については、標準化された年指数が必ずしも資源量そのものを正確に反映するとは限らない点を議論した。

漁業者の操業行動や漁獲効率の変化などがCPUEに影響するためである。

### 6.3 CPUE標準化と状態空間モデル

今回の会話から、CPUE標準化モデルと資源評価モデルの接続についても考えた。

**CPUE標準化に用いる状態空間モデルと、資源評価に用いる状態空間モデルは同一ではない。**

両者は異なる観測過程や潜在状態を扱う場合があり、その接続方法が重要となる。

今後の検討課題として、

1. 標準化CPUEを外部で推定し、資源評価モデルに入力する二段階推定
2. 漁獲量・努力量などの元データを資源評価モデルに直接組み込む統合推定
3. 推定誤差や年効果の相関をどこまで適切に引き継げるか
4. 漁獲効率の変化と資源量変化をどこまで識別できるか

などが考えられる。

これらは直ちにTMBSSへ実装するという意味ではなく、今後の研究上のヒントとして位置づける。

### 6.4 研究交流の意義

こうした若手研究者とのチャットは、日常業務の合間の気分転換にもなっている。

研究上の疑問を気軽に交換できることは、ネット・チャットの利点である。

一人でじっくり考える時間を大切にする一方、少数の研究者との意見交換から新しい発想を得ることも重要である。

---

## 7. Ecology and Evolution — 査読依頼受諾

本日、**Ecology and Evolutionの査読依頼を受諾した。**

現時点では受諾のみであり、査読作業は完了していない。

今後、他の研究・編集業務との兼ね合いを見ながら対応する。

---

## 8. ニューカレドニアの研究者との意見交換

午後、ニューカレドニアの研究者とも意見交換を行った。

具体的な研究内容については本日の記録に詳細がないため、研究交流を行った事実のみ記録する。

---

## 9. GMCS・IsoMove・SS・TMBSSの研究上の関係

今日は、これまで別々に進めてきた研究プロジェクトの相互関係についても整理した。

年末にかけて取り組むStock Synthesis関連の課題は次の4つである。

1. **SS作業部会の主宰**
   - 会議場の確保や各種手続きは完了している。

2. **海域間で成長などが異なる場合のSSファイル作成**
   - 優先順位が高い。
   - SS作業部会のメインテーマ。
   - 特にmovementの設定と成長履歴の扱いを理解する必要がある。

3. **TMBSS**
   - 科研費申請済み。
   - 今後のモデル開発を継続する。

4. **マダイStock Synthesis論文**
   - 年内に新たな論文を書く場合の候補。
   - ただし、投稿を急ぐことは優先しない。

### 研究プロジェクト間の接点

海域ごとに成長が異なり、個体が移動する場合のSSの設定方法は、GMCSを始めた動機の一つでもあった。

GMCSでは、成長履歴の混合が年齢別体長分布にどのように現れるかを検討している。

IsoMoveでは、安定同位体比から個体の由来や移動をどこまで推定できるかを検討している。

TMBSSでは、資源評価モデルの構造を自ら実装し、既存のSS系モデルを発展させることを目指している。

ただし、**GMCSやIsoMoveの最終目標が必ずしもSSへの応用であるわけではない。**

各プロジェクトには独立した研究目的があり、その過程で得られた知見や疑問が別の研究と結びつく。

共通する重要な問題は、

**観測データから、直接観測できない生態学的過程をどこまで識別できるか**

ということである。

特に、成長、移動、環境履歴、観測過程などを区別することは、多くの研究に共通する課題である。

今後も個々の研究の独立性を保ちながら、相互の接点を探っていく。

---

## 10. TMBSS — 10月14日に持ち越し

今日はTMBSSのレポートを読み直し、研究を再開する予定だった。

しかし、連休明けの事務指示、予定外の事務処理、原稿確認、研究相談などが続き、集中できる時間を十分に確保できなかった。

そのため、**TMBSSの再開は明日、10月14日に持ち越すこととした。**

再開時には、まず既存のレポートを読み、

- どこまでモデルを検証したか
- どの問題が未解決か
- 次に検証すべき問いは何か

を確認する。

新しいコードをすぐに書き始めるのではなく、これまでの研究内容を整理してから次の段階に進む。

---

## 11. 今日の評価

今日は、予定していた仕事を順番に進める一方で、連休明け特有の事務処理やメール対応によって集中が分断された。

主な進捗は以下のとおり。

- 普通種生息地チェックコードの修正
- PNAS原稿の確認完了
- 国際漁業学IIの提出締切確定
- 予定外の事務処理を約1時間半で実施し、内容確認を依頼
- マサバ生物特性論文のリジェクトと次の投稿方針を把握
- 若手研究者との安定同位体・多次元解析に関する議論
- 別の若手研究者との資源評価・CPUE標準化に関する議論
- Ecology and Evolutionの査読依頼を受諾
- ニューカレドニアの研究者との意見交換
- GMCS・IsoMove・SS・TMBSSの研究上の接点を整理

TMBSSの開発そのものは進められなかった。

一方、若手研究者との会話では、現在の研究課題とつながる科学的な疑問をいくつか考えることができた。

今日は**研究開発を本格的に進めた日というより、既存の仕事を処理しながら研究上の問題意識を取り戻していく日**だった。

---

## 次の予定 — 10月14日（水）

### 最優先

**TMBSSのレポートを読み直し、研究を再開する。**

まずは現状把握と未解決課題の整理を行う。

### その他

- 部下による事務書類の確認結果を受け、再チェックして提出
- 国際漁業学I・IIの採点結果の最終確認
- Ecology and Evolutionの査読への対応
- 必要なRSMA編集業務
- SS作業部会のメインテーマである海域間成長差とmovementの設定について、別途検討を進める

### 年末までの研究方針

Stock Synthesis関連の研究を中心に据えるが、GMCSやIsoMoveなどの独立した研究も継続する。

各プロジェクトを無理に一つの目標へ統合するのではなく、共通する疑問や方法論を通じて相互に発展させる。

---

# Research / Work Log — 13 October 2026

## Overview

Tuesday, 13 October 2026.

The day began with revisions to a habitat-checking program for common-species distribution data. Other activities included checking a PNAS manuscript, closing submissions for International Fisheries II, handling an unexpected administrative task, discussing research with younger colleagues, accepting a review invitation from *Ecology and Evolution*, and exchanging views with a researcher in New Caledonia.

The original intention was to resume TMBSS development after completing these responsibilities.

However, numerous emails and administrative requests following the long weekend interrupted concentration throughout the day.

**The restart of TMBSS was therefore postponed until 14 October.**

Nevertheless, conversations with younger researchers provided opportunities to reconsider several scientific questions connecting stable-isotope analysis, CPUE standardization, and stock assessment.

---

## 1. Common-species habitat-checking program

The habitat-checking program developed previously was revised with assistance from ChatGPT.

The work focused on checking and organizing distribution data.

No final ecological conclusions were drawn from this work today.

---

## 2. PNAS manuscript

The review of a coauthored manuscript intended for submission to PNAS was **completed during the morning**.

Specific revisions were not documented in today's log.

---

## 3. Hiroshima University — International Fisheries II

One student had not submitted the required report by 12 October.

I waited until the morning of 13 October, but no additional submission was received.

The submission process was therefore closed.

It is disappointing that one student did not submit the report.

The remaining task is to finalize grading for International Fisheries I and II before the **23 October deadline**.

All grading decisions remain my own.

---

## 4. Unexpected administrative work

A new administrative task arose during the day.

Approximately **1.5 hours** were spent preparing the required material.

The material was then sent to a subordinate for checking.

The remaining steps are to review the feedback, perform a final check, and submit the completed material.

The task is therefore not yet fully closed, but the initial preparation has been completed.

Repeated administrative interruptions made it difficult to secure uninterrupted time for research.

---

## 5. Rejection of a coauthored Fisheries Research manuscript

A coauthored manuscript summarizing approximately ten years of biological characteristics of chub mackerel was rejected by *Fisheries Research* on 12 October.

The principal reason reported was insufficient novelty.

The study contains carefully organized biological information, but its contribution apparently did not meet the journal's expectations for novelty.

The authors plan to submit the manuscript to *Regional Studies in Marine Science* (RSMA).

Although I serve as an editor for RSMA, the editorial system prevents my own coauthored manuscripts from being assigned to me.

The immediate objective is to encourage the younger researcher to move forward with the next submission.

The case also prompted reflection on the distinction between journal Impact Factors and the scientific quality or novelty of individual manuscripts.

---

## 6. Research discussions with younger colleagues

### 6.1 Stable isotopes and multidimensional analysis

One discussion concerned MixSIAR, particularly the sensitivity of mixing-model results to end-member definitions and trophic enrichment factors.

I also discussed recent work on the identifiability of two-dimensional Gaussian mixture models.

Potential applications of multidimensional analysis to amino-acid and fatty-acid composition were considered.

Possible approaches include multivariate mixture models, latent-factor models, and compositional data analysis, depending on the data structure.

A central issue is the distinction between statistical classification and the ecological processes generating the observed patterns.

This question also connects with GMCS and IsoMove.

### 6.2 Stock assessment, length composition, and CPUE

Another discussion focused on red seabream stock assessment.

Topics included:

- Length-composition data
- Biological characteristics and growth
- Catch-at-age estimation
- Fishery-specific sampling information
- CPUE reliability
- CPUE standardization and state-space models

Changes in biological assumptions or length-composition data may substantially affect catch-at-age estimates.

The reliability and transparency of input data are therefore essential, regardless of the sophistication of the assessment model.

### 6.3 Connecting CPUE models with assessment models

The discussion also raised an important distinction:

**A state-space model used for CPUE standardization is not necessarily the same as the state-space model used for stock assessment.**

Potential future questions include:

1. Two-stage estimation using externally standardized CPUE
2. Integrated estimation using original catch and effort data
3. Propagation of uncertainty between models
4. Identifiability of changes in catchability and stock abundance

These are research questions rather than immediate implementation plans for TMBSS.

### 6.4 Value of informal research communication

Informal online discussions provide opportunities to exchange ideas without arranging formal meetings.

They also serve as a useful change of pace during fragmented working days.

Independent thinking remains important, but conversations with a small number of colleagues can stimulate new questions and connections among research projects.

---

## 7. Ecology and Evolution — Review invitation accepted

A peer-review invitation from *Ecology and Evolution* was **accepted today**.

The review itself has not yet been completed.

It will be scheduled alongside existing research and editorial responsibilities.

---

## 8. Exchange with a New Caledonian researcher

Later in the day, I exchanged views with a researcher based in New Caledonia.

The specific scientific content was not recorded, so this entry documents the exchange without further interpretation.

---

## 9. Connections among GMCS, IsoMove, SS, and TMBSS

The day also provided an opportunity to clarify the relationships among several ongoing research projects.

Four Stock Synthesis-related activities are planned toward the end of 2026:

1. **Organizing and leading the Stock Synthesis working group**
   - Venue arrangements and administrative procedures have already been completed.

2. **Configuring Stock Synthesis for area-specific biological characteristics**
   - A high-priority technical issue and the main theme of the working group.
   - Particular attention will be given to growth differences and movement.

3. **TMBSS development**
   - A research grant application has already been submitted.
   - Model development will continue.

4. **Red seabream Stock Synthesis manuscript**
   - A potential manuscript project, without an immediate year-end submission requirement.

### Broader research connections

The question of how Stock Synthesis handles movement among areas with different growth characteristics was one motivation for initiating GMCS.

GMCS examines how mixtures of growth histories are reflected in age-specific length distributions.

IsoMove examines how stable-isotope information may help infer origin and movement.

TMBSS aims to develop and extend stock-assessment modeling approaches.

However, **GMCS and IsoMove are independent research projects, not merely components intended for future incorporation into Stock Synthesis**.

Each project addresses its own scientific questions.

Their connections emerge through shared methodological and ecological problems, particularly the extent to which unobserved ecological processes can be identified from observed data.

Maintaining the independence of these projects while exploring their conceptual connections remains an important research approach.

---

## 10. TMBSS — Postponed until 14 October

I intended to restart TMBSS by reviewing the existing project reports.

However, administrative interruptions, manuscript checking, and research discussions prevented a sustained period of concentration.

The restart was therefore postponed until **Wednesday, 14 October**.

The first steps will be to review:

- What has already been implemented and verified
- Which problems remain unresolved
- Which specific question should be addressed next

The immediate objective is to recover the current state of the project before expanding or modifying the code.

---

## 11. Evaluation

Today involved substantial fragmentation of working time.

Completed or advanced activities included:

- Revising the common-species habitat-checking code
- Completing the PNAS manuscript check
- Closing International Fisheries II submissions
- Preparing an administrative document and requesting internal checking
- Discussing the rejected chub mackerel manuscript and its next submission
- Exchanging ideas on stable isotopes and multidimensional analysis
- Discussing stock assessment and CPUE with another younger researcher
- Accepting an *Ecology and Evolution* review invitation
- Exchanging views with a researcher in New Caledonia
- Clarifying conceptual connections among GMCS, IsoMove, SS, and TMBSS

TMBSS model development did not progress directly.

However, the scientific discussions helped reconnect ongoing projects with their underlying research questions.

The day was therefore primarily one of **handling ongoing responsibilities while gradually returning to research-oriented thinking**, rather than a day of concentrated model development.

---

## Next steps — 14 October

### Main priority

**Resume TMBSS by reading the existing reports and identifying the next specific modeling question.**

### Other responsibilities

- Review internal feedback on the administrative document and submit it
- Finalize grading for International Fisheries I and II
- Begin work on the *Ecology and Evolution* review as appropriate
- Handle necessary RSMA editorial assignments and decisions
- Continue the separate technical investigation of growth and movement configurations in Stock Synthesis

### Research direction toward year-end

Stock Synthesis-related research will remain a major focus.

At the same time, GMCS, IsoMove, and other independent projects will continue to develop according to their own scientific objectives.

The broader goal is not to force all projects into a single framework, but to identify and explore meaningful connections among their questions, data, and methods.

---

**End of work log — 13 October 2026**