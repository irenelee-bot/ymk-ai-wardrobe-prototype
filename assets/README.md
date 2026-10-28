# Assets — 替換清單 / Replacement Checklist

把檔案放進對應資料夾、用下表的檔名命名即可，**不需要改任何程式碼**。
Drop the file into the matching folder using the filename below — no code changes needed.

狀態圖示：🟡 尚未提供（目前是截圖裁切或佔位） · ✅ 已替換為正式素材

## icons/

目前無（UI icon 皆為 inline SVG）。

## images/

| 檔名 | 用途 / 出現位置 | 尺寸 | 格式 | 狀態 |
|---|---|---|---|---|
| `img-photo-model-01.jpg` | 上方照片預覽 — 使用者原始照片 | 312×400 (≈3:4) | JPG | 🟡 截圖裁切 |
| `img-photo-result-01.jpg` | 試穿結果照片（Idea #1、#3 點 AI 單品後 / Idea #2 生成後） | 312×400 (≈3:4) | JPG | 🟡 截圖裁切，解析度低 |
| `img-ai-item-01.jpg` | AI 生成的單品（Idea #1 結果卡、衣櫃新格子、編輯縮圖） | 400×500 去背/白底 | JPG | 🟡 截圖裁切 |
| `img-wardrobe-item-01.jpg` | My Wardrobe 單品 #1（靴子） | 140×176 白底 | JPG | 🟡 截圖裁切 |
| `img-wardrobe-item-02.jpg` | My Wardrobe 單品 #2（米白裙） | 140×176 白底 | JPG | 🟡 截圖裁切 |
| `img-wardrobe-item-03.jpg` | My Wardrobe 單品 #3（豹紋外套） | 140×176 白底 | JPG | 🟡 截圖裁切 |
| `img-wardrobe-item-04.jpg` | My Wardrobe 單品 #4（金色洋裝） | 140×176 白底 | JPG | 🟡 截圖裁切 |
| `img-wardrobe-item-05.jpg` | My Wardrobe 單品 #5（針織外套） | 140×176 白底 | JPG | 🟡 截圖裁切 |
| `img-wardrobe-item-06.jpg` | My Wardrobe 單品 #6（咖啡色洋裝） | 140×176 白底 | JPG | 🟡 截圖裁切 |
| `img-wardrobe-item-07.jpg` | My Wardrobe 單品 #7（咖啡色長褲） | 140×176 白底 | JPG | 🟡 截圖裁切 |
| `img-hot-template-01.jpg` | HOT 模板 Shadow Sorceress | 140×152 | JPG | 🟡 截圖裁切 |
| `img-hot-template-02.jpg` | HOT 模板 Gothic Queen | 140×152 | JPG | 🟡 截圖裁切 |
| `img-hot-template-03.jpg` | HOT 模板 Dragon Empress | 140×152 | JPG | 🟡 截圖裁切 |
| `img-hot-template-04.jpg` | HOT 模板 Midnight Pixie | 140×152 | JPG | 🟡 截圖裁切 |
| `img-hot-template-05.jpg` | HOT 模板 Edgy Jack | 140×152 | JPG | 🟡 截圖裁切 |
| `img-hot-template-06.jpg` | HOT 模板 Punk Pumpkin | 140×152 | JPG | 🟡 截圖裁切 |
| `img-hot-template-07.jpg` | HOT 模板 Chic Contrast | 140×152 | JPG | 🟡 截圖裁切 |
| `img-hot-template-08.jpg` | HOT 模板 Preppy Pleats | 140×152 | JPG | 🟡 截圖裁切 |

> **Idea #3**（`idea3-prototype.html`）沿用上表同一批圖，無新增素材：Photo picker 用 `img-wardrobe-item-01`～`07`、`img-ai-item-01`、`img-hot-template-01/05/06/07`；Reference 參考圖用 `img-wardrobe-item-04`（替換鈕會輪換 `-06`、`-02`）。

## videos/

目前無。

## 規格建議 / Specs

- 圖片以 **2×** 尺寸輸出（表中為 CSS px），JPG 品質 80，單檔 < 300KB
- 影片 H.264 / MP4、無音軌、< 5 秒循環、單檔 < 2MB；必須同時提供同檔名的 `.jpg` poster
- SVG 請移除固定 `fill`，改由 CSS `currentColor` 控制顏色
- 檔名**不要改**；改了就要同步改 HTML
