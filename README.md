# 業務経歴書 / Data Analytics & Automation

Excel・Python・BIを用いて  
**属人化した集計業務を、再現可能なデータパイプラインに変える**  
データ分析・業務改善エンジニアです。

---

## 基本情報・実績リンク

- **ココナラ**：Excel業務代行・コンサル  
  - 検索順位：**2025年「エクセル」検索1位**
  - サービスURL：https://coconala.com/services/2041171
- **Qiita**：業務改善・データ処理に関する技術メモ
- **Zenn**：学習内容・実務知見の整理

---

## 得意分野

- Excel資産を活かした業務改善・自動化
- Python（pandas）によるETL・集計処理
- Power BIを用いたKPI可視化・更新設計
- 既存ツール（マクロ等）の解析・保守性改善

---

## Case Studies

## Case 01：Salesforce → Python → Power BI 更新パイプライン構築

> **背景 / 課題**  
> SalesforceからCSVを抽出し、ExcelやPower BI上で手作業加工していたため  
> 更新作業が属人化し、ミスや手戻りが発生していた。

### 制約条件
- Salesforce API権限なし（CSV抽出が前提）
- 現場ではExcel・Power BIの利用が必須

### 実施内容
- Python（pandas）でCSVを取り込み、型・欠損を整理
- 加工ロジックを関数化し、再利用可能なETLを構築
- 出力データをParquet形式で保存し、Power BIの更新負荷を軽減

### 成果
- 更新作業の標準化（担当者依存を解消）
- データ不整合の早期発見が可能に
- 改修時の影響範囲が明確になり、保守性が向上

### 使用技術
Python / pandas / Power BI / Power Query / SharePoint
