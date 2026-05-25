# 抗凝固薬・抗血小板薬まとめ

!!! warning "免責"
    本ページは個人の学習メモです。実投与量・休薬期間・腎機能補正は **添付文書・JCS抗血栓療法ガイドライン・各学会推奨** を必ずご確認ください。

## クラス早見（色で覚える）

<span class="rx doac">DOAC</span> <span class="rx warfarin">ワルファリン</span> <span class="rx heparin">ヘパリン</span> 抗凝固（**赤系**）  
<span class="rx aspirin">アスピリン</span> <span class="rx p2y12">P2Y12</span> 抗血小板（**桃系**）

## 抗凝固薬 vs 抗血小板薬

| 区分 | ターゲット | 主な疾患 |
|---|---|---|
| <span class="rx anticoag">抗凝固</span> | 凝固カスケード | **静脈系・低せん断**: AF・VTE・機械弁 |
| <span class="rx antiplt">抗血小板</span> | 血小板凝集 | **動脈系・高せん断**: ACS・PCI後・脳梗塞・PAD |

!!! mnemonic "覚え方 — 静脈は赤（抗凝固）、動脈は桃（抗血小板）"
    AF の心源性塞栓は左房（静脈寄り）→ 抗凝固。  
    冠動脈血栓は動脈（プラーク + 血小板）→ 抗血小板。

## DOAC（直接経口抗凝固薬） { .rx-card .doac }

<span class="rx doac">DOAC</span>

| 薬 | 標的 | 用量目安 | 排泄 |
|---|---|---|---|
| ダビガトラン (プラザキサ) | トロンビン (IIa) | 150 mg × 2、減量 110 mg × 2 | **腎 80%** |
| リバーロキサバン (イグザレルト) | Xa | AF: 15 mg/日（本邦）、減量 10 mg | 腎 約 1/3 |
| アピキサバン (エリキュース) | Xa | 5 mg × 2、減量 2.5 mg × 2 | 腎 約 25% |
| エドキサバン (リクシアナ) | Xa | 60 mg/日、減量 30 mg | 腎 約 50% |

!!! mnemonic "減量基準 — アピキサバンは『2/3』、エドキサバンは『1/3』"
    **アピキサバン**: <span class="key-num">3 のうち 2 つ</span> → 2.5 mg × 2
    - 年齢 ≥ 80
    - 体重 ≤ 60 kg
    - Cr ≥ 1.5 mg/dL

    **エドキサバン**: <span class="key-num">3 のうち 1 つ</span> → 30 mg/日
    - CrCl 30–50
    - 体重 ≤ 60 kg
    - P糖蛋白阻害薬併用

### DOAC の使いどころ

- **非弁膜症性 AF (NVAF) の脳卒中予防**: ワルファリンより推奨
- **VTE 治療**: 初期治療から DOAC 単剤で可（リバーロキサバン・アピキサバンは負荷量あり）
- **がん関連 VTE**: エドキサバン / アピキサバンが選択肢（消化管・尿路がんは出血リスク高）

!!! pitfall "DOAC が **使えない / 慎重投与** な場面"
    - 機械弁・中等度以上の僧帽弁狭窄（**リウマチ性 MS**）→ <span class="rx warfarin">ワルファリン一択</span>
    - 重度腎機能低下: 各製剤の閾値を確認（ダビガトランは CrCl<30 で禁忌）
    - 抗リン脂質抗体症候群（特に triple positive）→ <span class="rx warfarin">ワルファリン</span> 推奨
    - 妊娠・授乳 → <span class="rx heparin">ヘパリン (LMWH)</span> へ

### DOAC の中和薬

| 薬 | 中和薬 |
|---|---|
| ダビガトラン | <span class="rx caution">イダルシズマブ (プリズバインド)</span> 5 g iv |
| Xa 阻害薬 | アンデキサネット alfa（国内承認あり）/ 緊急時 4F-PCC で代用 |

## ワルファリン { .rx-card .warfarin }

<span class="rx warfarin">ワルファリン</span>

- VKORC1 阻害 → 凝固因子 II/VII/IX/X とプロテイン C/S 産生抑制
- **PT-INR** で管理: NVAF 1.6–2.6（70歳以上）/ 2.0–3.0、機械弁 2.0–3.0〜3.0–4.0
- 食事 (ビタミン K)・薬物相互作用が多い → 食生活指導必須

!!! pitfall "初期の一過性 過凝固"
    プロテイン C 半減期が短いため **開始直後は過凝固に傾く**。  
    急性 VTE では <span class="rx heparin">ヘパリン併用</span> で開始する。

!!! mnemonic "ワルファリンの拮抗"
    - 軽度 → 休薬 / ビタミンK 経口
    - 重度出血 → ビタミンK iv + **4因子 PCC (ケイセントラ)** または FFP

## ヘパリン類 { .rx-card .heparin }

<span class="rx heparin">ヘパリン</span>

| 薬 | 特徴 |
|---|---|
| 未分画ヘパリン (UFH) | iv で即効、半減期短、**APTT** モニタ、HIT リスク、中和は **プロタミン** |
| LMWH（エノキサパリン、本邦は限定的） | 皮下注、用量予測性 ◯ |
| フォンダパリヌクス (アリクストラ) | Xa 阻害、HIT 既往例で有用 |

!!! pitfall "HIT (heparin-induced thrombocytopenia)"
    投与 **5–10 日後** の血小板半減 + 血栓は HIT を疑う。  
    **ヘパリン全停止**、アルガトロバンへ切替。

## 抗血小板薬

### アスピリン { .rx-card .antiplt }

<span class="rx aspirin">アスピリン</span>

- COX-1 不可逆阻害（低用量 81–100 mg/日）
- 一次予防の適応は **狭まっている**（出血リスクで打ち消される例が多い）
- 二次予防（ACS、脳梗塞、PAD）は引き続き中核

### P2Y12 阻害薬

<span class="rx p2y12">P2Y12</span>

| 薬 | 特徴 |
|---|---|
| クロピドグレル (プラビックス) | プロドラッグ、**CYP2C19 多型で効果不安定** |
| プラスグレル (エフィエント) | 強力で速効、本邦用量は欧米より小（3.75 mg 維持） |
| チカグレロル (ブリリンタ) | 可逆的、1日2回、**呼吸困難・徐脈** の副作用 |

!!! mnemonic "覚え方 — P2Y12 三兄弟"
    **ク**ロピドグレル: 遅い・効果不安定（古株）  
    **プ**ラスグレル: 強い・速い・出血多い  
    **チ**カグレロル: 可逆・呼吸困難という独特の副作用

### その他

- <span class="rx antiplt">PDE3</span> シロスタゾール (プレタール) — PAD・脳梗塞
- ジピリダモール、サルポグレラート(5-HT2A) — 二次選択

## DAPT (Dual Antiplatelet Therapy)

PCI 後・ACS 後の標準。期間は **出血リスク・血栓リスクのバランス**。

| シナリオ | DAPT 期間 |
|---|---|
| ACS + PCI（出血低） | 12か月 → SAPT |
| ACS + PCI（出血高） | 3–6か月 → SAPT |
| 待機的 PCI (SIHD) | 1–6か月（出血高なら 1か月もあり） |
| **AF + PCI** | 短期 triple → <span class="rx doac">DOAC</span> + クロピドグレル → DOAC 単剤 |

!!! pearl "AF + PCI の組み合わせ"
    AUGUSTUS / ENTRUST-AF PCI 等で **DOAC + クロピドグレル** が標準。  
    退院時に triple → dual への切替プランを明記する。

## 抗血栓薬の休薬・周術期

### 出血リスクの低い処置（抜歯・白内障・体表小手術など）

- 抗血小板薬・DOAC・ワルファリンとも **基本休薬しない**（個別判断）

### 出血リスクの高い処置

| 薬 | 休薬目安 |
|---|---|
| <span class="rx aspirin">アスピリン</span> | 7日（継続のままで施行することも多い） |
| <span class="rx p2y12">クロピドグレル / プラスグレル</span> | 5–7日 |
| <span class="rx p2y12">チカグレロル</span> | **3–5日**（半減期短い） |
| <span class="rx warfarin">ワルファリン</span> | 3–5日前中止、INR ≤ 1.5 確認、必要なら **ヘパリン bridging** |
| <span class="rx doac">DOAC</span> | **腎機能と出血リスクで <span class="key-num">24–48 時間</span>（高リスク手術は 48–72 時間）** |

!!! pitfall "Bridging はもう原則しない"
    BRIDGE 試験以降、NVAF の通常リスク例では **ヘパリンブリッジ不要**。  
    出血が増えるだけ。**機械弁・最近の塞栓症例** のみ検討。

## 出血時対応の早見

| 薬 | 緊急対応 |
|---|---|
| <span class="rx warfarin">ワルファリン</span> | ビタミンK iv 5–10 mg + **4F-PCC（ケイセントラ）** が第一選択、FFP は代替 |
| <span class="rx doac">ダビガトラン</span> | **イダルシズマブ** |
| <span class="rx doac">Xa-DOAC</span> | アンデキサネット alfa / 4F-PCC（off-label） |
| <span class="rx heparin">UFH</span> | プロタミン（1mg で 100 units 中和） |
| <span class="rx antiplt">抗血小板</span> | 血小板輸血の効果は限定的、トラネキサム酸 + 圧迫 + 原疾患治療 |

## CHA₂DS₂-VASc / HAS-BLED

抗凝固開始の判断は **CHA₂DS₂-VASc ≥ 2（男性）/ ≥ 3（女性）** がベース。HAS-BLED は出血リスクの **可逆要因の修正** に使う（点数だけで抗凝固を見送るのは ✗）。

!!! mnemonic "CHA₂DS₂-VASc"
    **C** ongestive HF (1)　**H** ypertension (1)　**A** ge ≥75 (**2**)　**D** M (1)　**S** troke/TIA (**2**)　**V** ascular disease (1)　**A** ge 65–74 (1)　**S** c = female (1)

## 参考

- 日本循環器学会『2020年 JCS/JHRS ガイドラインフォーカスアップデート版 不整脈薬物治療 / 抗血栓療法』
- ESC Guidelines on Atrial Fibrillation / Acute Coronary Syndromes
- 各薬剤の添付文書
