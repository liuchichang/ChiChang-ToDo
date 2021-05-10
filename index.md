# 2021/5/14

## 完成項目
#### Flow (Syncobox)
- ✅ &nbsp;&nbsp;執行Flow參數輸入的防呆機制
- ✅ &nbsp;&nbsp;增加Approval Step的設定參數：申請人欄位
- ✅ &nbsp;&nbsp;step引用的變數異動檢查機制(全部step完成)
- ⬜️ &nbsp;&nbsp;(bug)插入step後的藍色選取框會停留在原地
- ⬜️ &nbsp;&nbsp;Syncobox Main Page的陰影太多，是否扁平化設計？
- ⬜️ &nbsp;&nbsp;發布flow至portal
- ⬜️ &nbsp;&nbsp;新增step的時候會出現 "TypeError: Cannot read property 'Id' of undefined"


# 2021/5/7

## 完成項目
#### Flow (Syncobox)
- ✅ &nbsp;&nbsp;Approval頁面設計:表格那頁的簽核狀態改成流程狀態、人名的chip顏色改變、未簽核的icon改掉
- ✅ &nbsp;&nbsp;Approval頁面:調整css
- ✅ &nbsp;&nbsp;執行Flow的參數輸入功能與確認步驟
- ✅ &nbsp;&nbsp;移動既有 Step位置的功能
- ✅ &nbsp;&nbsp;Step菜單樣式調整 => 縮小，可容納更多step

#### Others
- ✅ &nbsp;&nbsp;調整 syncobox-style.css 內容，修正vuetify input行高問題

## 待辦項目
#### Flow (Syncobox)
- ⬜️ &nbsp;&nbsp;Definition Version可執行限制(討論)
- ⬜️ &nbsp;&nbsp;＊Step的版本機制


# 2021/4/29

## 完成項目
#### Flow (Syncobox)

- ✅ &nbsp;&nbsp;Approval頁面設計
- ✅ &nbsp;&nbsp;單元測試
- ✅ &nbsp;&nbsp;step引用的變數異動檢查機制
- ✅ &nbsp;&nbsp;Shared-Flow專案資料夾結構與程式碼整理(維護優化)

#### Markup (WeBIMSync)

- ✅ &nbsp;&nbsp;Viewer的對照模式產生顯示錯誤 & 各種優化與Bug排除
- ✅ &nbsp;&nbsp;Makrup Shared-ui 更新

## 待辦項目
#### Flow (Syncobox)

- ⬜️ &nbsp;&nbsp;Approval頁面設計:表格那頁的簽核狀態改成流程狀態、人名的chip顏色改變、未簽核的icon改掉
- ⬜️ &nbsp;&nbsp;Definition Version可執行限制(討論)
- ⬜️ &nbsp;&nbsp;＊移動既有 Step位置的功能(step的nextStepId與Design.startTaskId更改、drap拖移時頁面要自動往下scroll)
- ⬜️ &nbsp;&nbsp;＊Step的版本機制


# 2021/4/22

## 完成項目
#### Flow (Syncobox)

- ✅ &nbsp;&nbsp;step引用的變數異動檢查機制
- ✅ &nbsp;&nbsp;新增JSON editor傳送執行flow的data
- ✅ &nbsp;&nbsp;SetValue(Form) Step的{key:value}支援變數功能
- ✅ &nbsp;&nbsp;預防變更StepName重複的問題
- ✅ &nbsp;&nbsp;插入變數方式與型別判斷

#### Markup (WeBIMSync)

- ✅ &nbsp;&nbsp;Markup Viewer有現場照片的瀏覽功能
- ✅ &nbsp;&nbsp;Markup Viewer切換上下張的功能優化
- ✅ &nbsp;&nbsp;Loading機制 (Dialog Show -> Loading)
- ✅ &nbsp;&nbsp;「No Image」的預設顯示圖片統一
- ✅ &nbsp;&nbsp;Makrup Shared-api 更新

#### WeBIMSync官方網站

- ✅ &nbsp;&nbsp;語言切換按鈕
- ✅ &nbsp;&nbsp;中英文版網站樣式調整與內容更新

## 待辦項目
#### Flow (Syncobox)

- ⬜️ &nbsp;&nbsp;Approval頁面設計
- ⬜️ &nbsp;&nbsp;發布穩定版至靜態網站
- ⬜️ &nbsp;&nbsp;＊移動既有 Step位置的功能
- ⬜️ &nbsp;&nbsp;＊Step的版本機制

#### Markup (WeBIMSync)

- ⬜️ &nbsp;&nbsp;Makrup Shared-ui 更新

# 2021/4/15

#### 休假

# 2021/4/8

## 完成項目
#### Flow (Syncobox)

- ✅ &nbsp;&nbsp;新增SetValue Step (Form)、GetValue Step (Form)、Terminate Step
- ✅ &nbsp;&nbsp;修改流水號功能(從最小數字遞補)
- ✅ &nbsp;&nbsp;新增改變Step顯示名稱(同步修改StepName)
- ✅ &nbsp;&nbsp;優化插入Step功能( NextStepId 與 Design.startTaskId 自動修正)
- ✅ &nbsp;&nbsp; [Static Web](https://ashy-sea-0b1e0bb00.azurestaticapps.net/) 建立 (感謝柏硯、易修、軒竹協助)


## 待辦項目
#### Flow (Syncobox)

- ⬜️ &nbsp;&nbsp;插入變數方式與型別判斷(50%) (剩下email的body)
- ⬜️ &nbsp;&nbsp;預防變更StepName重複的問題
- ⬜️ &nbsp;&nbsp;刪除前面的Step，後方Step引用資料是否有效的檢查機制
- ⬜️ &nbsp;&nbsp;移動既有 Step位置的功能
- ⬜️ &nbsp;&nbsp;優化 Step Inputs Expression
- ⬜️ &nbsp;&nbsp;Step的版本機制

#### Markup (WeBIMSync)

- ⬜️ &nbsp;&nbsp;Loading機制 (Dialog Show -> Loading)
- ⬜️ &nbsp;&nbsp;Markup Viewer切換上下張的優化
- ⬜️ &nbsp;&nbsp;「No Image」的預設顯示圖片統一
