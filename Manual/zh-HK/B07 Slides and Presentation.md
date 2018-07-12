---
flag: blue
---
# 幻燈片及演示播放

有時文檔的內容就是幻燈片的內容，那麼為什麼要重複勞動再做一個 PPT 呢？Yu Writer 支持以幻燈片的形式播放文檔。

## 見證魔術的時刻

現在就點擊工具欄上的 `View` 按鈕然後選擇 `Toggle Presentation` 開始播放幻燈片吧！

## 書寫上的約定

如果要製作美觀的幻燈片，只需遵循很少的書寫的約定即可。其中最基本的是：每個二級標題就會形成一張新的幻燈片。

## 支持的元素

* 字體格式（粗體、斜體等）
* 列表
* 圖片
* 表格、圖表
* 腳註
* 數學公式
* 語法加亮的代碼塊

其實所有文檔支持的元素都能在幻燈片上顯示 😄。

## 顯示錶格的例子

| Category   | Series 1 | Series 2 | Series 3 |
| ---------  | -------- | -------- | -------- |
| Category 1 |      4.3 |      2.4 |        2 |
| Category 2 |      2.5 |      4.4 |        2 |
| Category 3 |      3.5 |      1.8 |        3 |
| Category 4 |      4.5 |      2.8 |        5 |

在表格下方仍可以添加説明文字。

## 顯示數學公式的例子

$$
x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}
$$

## 兩欄式

作為幻燈片，一頁內容不宜過長，文字儘量簡明扼要。通常用兩欄式可以容納更多的內容。

如果要用兩欄式，只需用分隔符 `- - -` 分開兩部分即可。

比如接下來的圖片將會顯示在右欄。

- - -

![Bookstore](images/bookstore.jpg)

## 顯示圖表的例子

@chart
type: pie
size: small

| Qtr     | Sales |
| ------- | ----- |
| 1st Qtr |   8.2 |
| 2nd Qtr |   3.2 |
| 3rd Qtr |   1.4 |
| 4th Qtr |   1.2 |

- - -

* 圖表指令 `@chart` 的參數依然可用；
* 如果一頁的內容過長，可以通過滾動條查看一屏幕顯示不完的內容；
* 所以，其實放長篇代碼塊也是沒問題的。

## 所以這裏來一段代碼

```scss
.slide-style {
  font-family: $viewFontFamily;
  font-size: 24px;
  line-height: 1.5em;
  
  h1, h2, h3, h4, h5, h6 {
    font-weight: 500;
    line-height: 1.3em;
    color: rgba($viewFontColor, .8);
    margin-top: 24px;
    margin-bottom: 16px;
  }
}
```

使用滾動條就可以看到我了。

## 頁面內容留空，標題居中

## 設置背景圖片

只要把圖片代碼的 `title` 部分寫成 `background`，那麼這幅圖片就會自動變成全屏顯示的背景。

![background](images/desktop.jpg)

## 設置全部頁面的背景圖片

你可以在文檔的 Front Matter 中使用 `background` 字段設置所有頁面的背景圖片或者背景色，比如

    ---
    background: images/black.jpg
    ---

或者

    ---
    background: #f1f1f2
    ---

有關 Front Matter 的內容，詳細請參見 [B06 Front Matter](b06-front-matter)

## 套用幻燈片樣式

返回文檔編輯狀態，然後點擊工具欄的 `View` 再點擊 `Toggle Slides` 可以一覽所有頁面的縮略圖，同時還可以選擇不同的幻燈片樣式。

## 演示結束555}+{`Q` AA