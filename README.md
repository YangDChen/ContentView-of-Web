## iOS 整合學習 App / iOS Learning Hub App - 整合多平台華語教學資源、降低使用者學習成本

這是一個以**SwiftUI**開發的iOS整合學習App，其目的在於把分散在多個平台的華語教學資源（Google Sites / Google Classroom / YouTube Channel / 官方 LINE）整合成單一學習動線，降低使用者在學習時，因跨平台跳轉問題，而造成的學習成本。

若想瞭解詳細操作流程與理念，歡迎您瀏覽此影片：

## APP設計理念與使用導覽。/ Design concepts and usage guidance of our APP.

影片連結：https://youtu.be/gvvv4g6evAg?si=fiuQ_nOHB_eQN6ri

## 1. 為什麼需要這個App? (Why this App?)

由於在既有的非同步線上教學設計中，使用者多以 PC/筆電開啟學習網站，但是，使用者常常會不斷在多個分頁/平台間切換，例如以我們的華語學習網站為例：

(1) Google Site：課程主要網站（教材專區 / 課程架構專區）
(2) Google Classroom：課程進度 / 作業繳交區
(3) YouTube：暖身影片、句型影片、作業示範影片、補充教材影片
(4) LINE：官方通知 / 學員互動

這種「多平台跳轉與資訊分散」的問題，容易造成使用者的學習流程中斷，並增加學習成本。  
因此，這個App以「單一入口」整合所有資源，讓使用者可用手機快速進入課程學習、繳交作業、瀏覽教學影片。

## 2. 特色 (Features)

(1) **Start Learning按鈕**：以彈出式視窗顯示延伸學習平台入口。
   
  (a) **跨平台整合功能**：
  
    (i) Google Site（課程主要網站）
    (ii) Google Classroom（課程進度 / 作業繳交區）
    (iii) YouTube Channel（教學影片區）
    (iv) LINE 官方帳號
    
(2) **指定課程icon連結**：

  (a) 在主畫面中點選課程 icon（如：Ch1_臺北 / Ch2_臺中 / Ch3_臺南 / Ch4_高雄 / Ch5_宜蘭）可直接跳轉到Google Site之對應課程連結。
  

---

## 3. App結構 (Structures)

(1) 主畫面

  (a) App 主畫面：課程標題 / 簡介 / 課程入口 / 延伸學習、課程資訊按鈕。

(2) 基礎功能與定義頁面

  (a) 定義基礎變數。 e.g. 課程清單、平台連結（Google Site / Google Classroom / YouTube / LINE）
    
(3) 延伸學習頁面

  (a) 設計延伸學習頁面之背景與圖片。 e.g. Google Site, Google Classroom, Youtube, Line，用以提升使用者體驗。
    
(4) Line Shape頁面

  (a) 其目的是使用在「主畫面」最下方Experience欄的左方圖形，用途為標示出此專題之經歷，用以提升使用者體驗。

---

## 4. 如何使用此App? (How it works?)

(1) 點選App icon後，進入主畫面
(2) 點選 **Start Learning**按鈕，可點選icon後，自行選擇進入：主要教學網站 / 作業繳交網站 / 課程影片網站 / 官方Line App。

---

會有這個作品的存在，我要感謝Jane from ChaoCode給了我非常多的學習資源與鼓勵：）

Jane的Youtube Channel：https://youtube.com/@chaocode?si=g5MSzOKEuvIIlUAc
(3) 或者，您也可以在**Lectures**點選城市icon後，將會直接跳轉到指定課程連結。

---

