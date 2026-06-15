# 欄位順序（Note Type: German Vocab Anki）

`demo/notes.tsv` 為 **Tab 分隔**，匯入時請依此順序對應 17 個欄位：

| # | 欄位 | 說明 |
|---|------|------|
| 1 | `entry` | 條目（含詞性標記，如 `der Tisch`、`[V] lernen`） |
| 2 | `article` | 冠詞 `der/die/das`；非名詞放 `[V]`/`[Adj]` 等標記 |
| 3 | `word` | 單字本身（正面只顯示這個） |
| 4 | `plural` | 複數（名詞用） |
| 5 | `pos` | 詞性（Noun / Verb / Adjective …） |
| 6 | `gender` | masculine / feminine / neuter（只有名詞有） |
| 7 | `chinese` | 中文意思 |
| 8 | `english` | 英文意思 |
| 9 | `sentence_de` | 德文例句（目標字用 `<b>…</b>` 粗體） |
| 10 | `sentence_zh` | 例句中譯 |
| 11 | `conjugation_3sg` | 第三人稱單數變位（動詞用，如 `er geht`） |
| 12 | `phrase` | 常用片語 |
| 13 | `frequency_tag` | 頻率標籤（high / normal …） |
| 14 | `confusion_note` | 易混淆提醒 |
| 15 | `color_tag` | 顏色標籤（見下） |
| 16 | `source_note` | 來源備註 |
| 17 | `perfekt` | 完成式（動詞用，如 `ist gegangen`） |

## 顏色系統（`color_tag`）

正面只顯示單字（中性色，不洩漏性別）；背面依 `color_tag` 上色：

| color_tag | 顏色 | 用於 |
|-----------|------|------|
| `blue` | 藍 | 陽性名詞 der |
| `red` | 紅 | 陰性名詞 die |
| `green` | 綠 | 中性名詞 das |
| `verb` | 紫 | 動詞 |
| `adj` | 橘 | 形容詞 |
| `adv` | 青 | 副詞 |
| `prep` | 橙 | 介系詞 |
| `phrase` | 天藍 | 片語 |
| `other` | 灰 | 其他 |
