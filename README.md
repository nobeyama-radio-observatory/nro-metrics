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
| [cost-electricity](series/cost-electricity.yaml) | 電気代 | 予算 | 年度 | 2025年度 |
| [cost-maintenance](series/cost-maintenance.yaml) | 装置の保守の費用 | 予算 | 年度 | 2025年度 |
| [cost-total](series/cost-total.yaml) | 観測所の運営に要る費用 | 予算 | 年度 | 2025年度 |
| [dev-projects](series/dev-projects.yaml) | 開発プログラムの進行中のプロジェクトの数 | 利用 | 年度 | 2023年度〜2024年度（2件） |
| [downtime-ratio](series/downtime-ratio.yaml) | 45m 鏡の観測の停止の割合（天候と技術的な故障） | 運用 | 年度 | 2019年度〜2020年度（2件） |
| [income-ads](series/income-ads.yaml) | 構内の広告の収入 | 予算 | 年度 | 2025年度 |
| [income-donation](series/income-donation.yaml) | 寄附の収入 | 予算 | 年度 | 2025年度 |
| [income-grant](series/income-grant.yaml) | 運営費交付金（観測所の分） | 予算 | 年度 | 2025年度 |
| [income-local-tourism](series/income-local-tourism.yaml) | 南牧村との連携による収入 | 予算 | 年度 | 2020年度〜2025年度（5件） |
| [income-telescope-charge](series/income-telescope-charge.yaml) | 有料の望遠鏡時間の収入 | 予算 | 年度 | 2024年度〜2025年度（2件） |
| [media-coverage](series/media-coverage.yaml) | 取材の対応の件数 | 広報 | 年度 | 2023年度〜2024年度（2件） |
| [observer-institutions](series/observer-institutions.yaml) | 45m 鏡の観測者の所属機関の数 | 利用 | 年度 | 2023年度〜2024年度（2件） |
| [observers-count](series/observers-count.yaml) | 45m 鏡の観測者の数 | 利用 | 年度 | 2023年度〜2024年度（2件） |
| [offered-hours](series/offered-hours.yaml) | 45m 鏡の観測の提供時間 | 運用 | 年度 | 2018年度〜2022年度（4件） |
| [open-day-onsite-visitors](series/open-day-onsite-visitors.yaml) | 特別公開（現地）の来場者数 | 広報 | 年度 | 2023年度〜2025年度（3件） |
| [paid-event-participants](series/paid-event-participants.yaml) | 南牧村との連携事業の参加者数 | 広報 | 年度 | 2023年度〜2025年度（3件） |
| [papers-45m-fy](series/papers-45m-fy.yaml) | 45m 鏡を使った査読論文の出版数（年度） | 成果 | 年度 | 2023年度〜2024年度（2件） |
| [papers-45m-list](series/papers-45m-list.yaml) | 45m 鏡を使った査読論文の数（観測所の論文の一覧、暦年） | 成果 | 暦年 | 2020〜2024（5件） |
| [papers-refereed-45m](series/papers-refereed-45m.yaml) | 査読論文の数（45m 鏡） | 成果 | 暦年 | 2013〜2021（9件） |
| [papers-refereed-all](series/papers-refereed-all.yaml) | 査読論文の数（観測所全体） | 成果 | 暦年 | 2013〜2021（9件） |
| [papers-refereed-nma](series/papers-refereed-nma.yaml) | 査読論文の数（ミリ波干渉計） | 成果 | 暦年 | 2013〜2021（9件） |
| [press-releases](series/press-releases.yaml) | プレスリリースの数 | 広報 | 年度 | 2023年度〜2024年度（2件） |
| [proposals-accepted](series/proposals-accepted.yaml) | 45m 鏡の共同利用の観測提案の採択件数 | 利用 | 年度 | 1982年度〜2021年度（40件） |
| [proposals-submitted](series/proposals-submitted.yaml) | 45m 鏡の共同利用の観測提案の件数 | 利用 | 年度 | 1982年度〜2021年度（40件） |
| [sns-followers-x](series/sns-followers-x.yaml) | X（旧 Twitter）のフォロワーの数 | 広報 | 時点 | 2024-04（2023年度の報告の時点）〜2025-06-03（2件） |
| [staff-admin](series/staff-admin.yaml) | 事務系の職員の数 | 人員 | 年度 | 2025年度 |
| [staff-technical-onsite](series/staff-technical-onsite.yaml) | 現地の技術系職員の数 | 人員 | 年度 | 2018年度〜2025年度（3件） |
| [staff-total](series/staff-total.yaml) | 観測所の職員の数（規模） | 人員 | 年度 | 2023年度 |
| [student-proposals](series/student-proposals.yaml) | 学生の無料の枠の応募の件数 | 利用 | 年度 | 2023年度〜2025年度（3件） |
| [telescope-hours-allocated](series/telescope-hours-allocated.yaml) | 45m 鏡の観測に割り当てた時間 | 運用 | 年度 | 2023年度〜2025年度（3件） |
| [telescope-proposals](series/telescope-proposals.yaml) | 45m 鏡の観測の応募の件数（有料の望遠鏡時間の期間） | 利用 | 年度 | 2023年度〜2025年度（3件） |
| [theses-doctor](series/theses-doctor.yaml) | 45m 鏡と観測所を使った博士論文の数 | 成果 | 暦年 | 1985〜2024（37件） |
| [theses-master](series/theses-master.yaml) | 45m 鏡と観測所を使った修士論文の数 | 成果 | 暦年 | 1984〜2024（39件） |
| [trouble-count](series/trouble-count.yaml) | 45m 鏡の障害の件数（観測期） | 障害 | 観測期 | 2026-2027年の観測期（2026-11-12 まで） |
| [visitors-monthly](series/visitors-monthly.yaml) | 見学者数（月） | 広報 | 月 | 2012-04〜2025-03（132件） |
| [visitors-yearly](series/visitors-yearly.yaml) | 見学者数（年度） | 広報 | 年度 | 1982年度〜2024年度（41件） |

## 出典の略記

| 略記 | 所在 |
|---|---|
| 40周年記念誌 | 『野辺山宇宙電波観測所40周年記念誌』2022年2月（国立国会図書館 請求記号 MB12-M7）。p.N はそのページ。書誌の詳細はハブの [history/README.md](https://github.com/nobeyama-radio-observatory/nro-context/blob/main/history/README.md) |
| 外部評価2023 | 国立天文台 外部評価（2023年度）野辺山宇宙電波観測所の報告書 https://www.nao.ac.jp/contents/about/reports/external-review/external-review-2023-nro.pdf 。p.N は PDF のページ |
| データで見る2023年度 | 観測所「データで見る野辺山宇宙電波観測所（2023年度）」2024年4月11日 https://www.nro.nao.ac.jp/news/2024/0411-data.html 。旧サーバー（www2）の証明書の期限が切れているため、Internet Archive の写し https://web.archive.org/web/20251005130729/https://www.nro.nao.ac.jp/news/2024/0411-data.html で確かめた |
| データで見る2024年度 | 同（2024年度）2025年6月4日 https://www.nro.nao.ac.jp/news/2025/0604-data.html 。写し https://web.archive.org/web/20260501095251/https://www.nro.nao.ac.jp/news/2025/0604-data.html |
| UM2024 | ALMA/45m/ASTE Users Meeting 2024 の観測所の報告「Status of Nobeyama Observations 2024」https://www2.nao.ac.jp/~eaarc/Meetings/ALMAUM2024/program/presen/nroum.20241218.pdf |
| UM2025a | ALMA/45m/ASTE Users Meeting 2025 の観測所の報告「Status of Nobeyama observations」https://www2.nao.ac.jp/~eaarc/Meetings/ALMAUM2025/PresentationFiles/NRO_UM_Current_Status.pdf |
| UM2025b | 同「Nobeyama plan for 2026」https://www2.nao.ac.jp/~eaarc/Meetings/ALMAUM2025/PresentationFiles/nroum.20251217s2.pdf |
| 論文の一覧 | 観測所の 45m 鏡の論文の一覧 https://www.nro.nao.ac.jp/~nro45mrt/html/publications/ 。写し https://web.archive.org/web/20250210092548/https://www.nro.nao.ac.jp/~nro45mrt/html/publications/ （2025年2月10日の時点） |
| 学位論文の一覧 | 観測所の学位論文の一覧 https://www.nro.nao.ac.jp/~nro45mrt/html/publications/thesis/ 。写し https://web.archive.org/web/20250418232345/https://www.nro.nao.ac.jp/~nro45mrt/html/publications/thesis/ （2025年4月18日の時点） |
| 技術シンポ2019 | 国立天文台 技術シンポジウム2019 の発表資料「45m 電波望遠鏡の現状」https://www2.nao.ac.jp/~open-info/engipromo/draftparts_2019/gk/tecsym19_Miyazawa_Chieko.pdf |

## まだ入っていないもの

2022年度の有料の望遠鏡時間の実績、2023年度以前の収入、稼働率（観測期ごと）、過去の観測期の障害の件数、2021・2022年度の見学者数、2026年度以降の値、2002〜2012年の論文数（30周年記念誌）、観測提案の国内と海外の内訳（40周年記念誌 p.167）。

## 進め方

進め方の決まりの正本は、ハブの [CONTRIBUTING.md](https://github.com/nobeyama-radio-observatory/nro-context/blob/main/CONTRIBUTING.md) です。

- 人数は、個人が特定できるほど細かくしない。1〜2人のチームの内訳は出さず、グループ単位でまとめる。
- 主ブランチに直接書き込まず、プルリクエストを出す。AI が作ったものにはラベル `AI作成` を付ける。

担当：未定（決まるまでは、ハブの担当が預かる）

## 利用許諾

- コード：BSD 3-Clause License（[LICENSE](LICENSE)）
- 文書とデータ：クリエイティブ・コモンズ 表示 4.0 国際（CC BY 4.0、[LICENSE-docs](LICENSE-docs)）
