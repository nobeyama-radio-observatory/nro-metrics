# nro-metrics

国立天文台 野辺山宇宙電波観測所の**数値**の系列です。文脈基盤のハブ [nro-context](https://github.com/nobeyama-radio-observatory/nro-context) から参照されます（ハブの判断記録 [0007](https://github.com/nobeyama-radio-observatory/nro-context/blob/main/decisions/0007-業務と数値を区分ごとのリポジトリに置き数値から始める.md)）。

- **項目の定義の正本は、ハブの [metrics/README.md](https://github.com/nobeyama-radio-observatory/nro-context/blob/main/metrics/README.md) です。** 系列ごとに1ファイルで、何をどう数えたか（`definition`）を値と一緒に持ちます。
- **値ごとに出典があります。** グラフから読み取った値や見積もりには `estimate: true` が付いています。範囲しか分からない値は `range` です。
- **値のない年は書いていません。** 0 と「記録がない」を区別するためです。

## 系列

| id | 名称 | 分類 | 区切り | 期間 |
|---|---|---|---|---|
| [budget-operations](series/budget-operations.yaml) | 観測所の予算（規模） | 予算 | 年度 | 2023年度 |
| [charge-per-hour](series/charge-per-hour.yaml) | 有料の望遠鏡時間の単価 | 料金 | 時点 | 2026-11-18 時点（国内の機関の研究代表者）〜2026-11-18 時点（国外の機関の研究代表者）（2件） |
| [downtime-ratio](series/downtime-ratio.yaml) | 45m 鏡の観測の停止の割合（天候と技術的な故障） | 運用 | 年度 | 2019年度〜2020年度（2件） |
| [offered-hours](series/offered-hours.yaml) | 45m 鏡の観測の提供時間 | 運用 | 年度 | 2018年度〜2022年度（4件） |
| [papers-refereed-45m](series/papers-refereed-45m.yaml) | 査読論文の数（45m 鏡） | 成果 | 暦年 | 2013〜2021（9件） |
| [papers-refereed-all](series/papers-refereed-all.yaml) | 査読論文の数（観測所全体） | 成果 | 暦年 | 2013〜2021（9件） |
| [papers-refereed-nma](series/papers-refereed-nma.yaml) | 査読論文の数（ミリ波干渉計） | 成果 | 暦年 | 2013〜2021（9件） |
| [proposals-accepted](series/proposals-accepted.yaml) | 45m 鏡の共同利用の観測提案の採択件数 | 利用 | 年度 | 1982年度〜2021年度（40件） |
| [proposals-submitted](series/proposals-submitted.yaml) | 45m 鏡の共同利用の観測提案の件数 | 利用 | 年度 | 1982年度〜2021年度（40件） |
| [staff-technical-onsite](series/staff-technical-onsite.yaml) | 現地の技術系職員の数 | 人員 | 年度 | 2018年度〜2019年度（2件） |
| [staff-total](series/staff-total.yaml) | 観測所の職員の数（規模） | 人員 | 年度 | 2023年度 |
| [trouble-count](series/trouble-count.yaml) | 45m 鏡の障害の件数（観測期） | 障害 | 観測期 | 2026-2027年の観測期（2026-11-12 まで） |
| [visitors-monthly](series/visitors-monthly.yaml) | 見学者数（月） | 広報 | 月 | 2012-04〜2021-03（108件） |
| [visitors-yearly](series/visitors-yearly.yaml) | 見学者数（年度） | 広報 | 年度 | 1982年度〜2020年度（39件） |

## 出典の略記

| 略記 | 所在 |
|---|---|
| 40周年記念誌 | 『野辺山宇宙電波観測所40周年記念誌』2022年2月（国立国会図書館 請求記号 MB12-M7）。p.N はそのページ。書誌の詳細はハブの [history/README.md](https://github.com/nobeyama-radio-observatory/nro-context/blob/main/history/README.md) |
| 外部評価2023 | 国立天文台 外部評価（2023年度）野辺山宇宙電波観測所の報告書 https://www.nao.ac.jp/contents/about/reports/external-review/external-review-2023-nro.pdf 。p.N は PDF のページ |
| 技術シンポ2019 | 国立天文台 技術シンポジウム2019 の発表資料「45m 電波望遠鏡の現状」https://www2.nao.ac.jp/~open-info/engipromo/draftparts_2019/gk/tecsym19_Miyazawa_Chieko.pdf |

## まだ入っていないもの

有料の望遠鏡時間の申し込みと販売の実績、稼働率（観測期ごと）、過去の観測期の障害の件数、予算の内訳、2021年度以降の見学者数、2002〜2012年の論文数（30周年記念誌）、観測提案の国内と海外の内訳（40周年記念誌 p.167）。

## 進め方

進め方の決まりの正本は、ハブの [CONTRIBUTING.md](https://github.com/nobeyama-radio-observatory/nro-context/blob/main/CONTRIBUTING.md) です。

- 人数は、個人が特定できるほど細かくしない。1〜2人のチームの内訳は出さず、グループ単位でまとめる。
- 主ブランチに直接書き込まず、プルリクエストを出す。AI が作ったものにはラベル `AI作成` を付ける。

担当：未定（決まるまでは、ハブの担当が預かる）

## 利用許諾

- コード：BSD 3-Clause License（[LICENSE](LICENSE)）
- 文書とデータ：クリエイティブ・コモンズ 表示 4.0 国際（CC BY 4.0、[LICENSE-docs](LICENSE-docs)）
