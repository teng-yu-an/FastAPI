## Text Similarity Analysis of FinTech development of various financial holding companies <br>
## 金融業各金控數位金融和金融科技發展 之文本相似度分析


- Abstract:<br>
在 [【人工智慧應用專題】語言學導向的NLP](https://www.youtube.com/watch?v=Z6KOlJ58Gfw)， 請到 [卓騰語言科技](https://www.droidtown.co/zh-tw/) 總經理 王文傑老師 介紹語言學導向的自然語言處理以及卓騰語言科技的產品。<br>
本專案實作目標為分析各家金控公司在數位金融發展的方向、產品上的差異，判斷方法為計算其文本相似度，並進一步針對各家文本做文字雲的視覺化呈現，觀察各家金控發展的重點。<br><br>

- 方法：<br>
Articut API 為卓騰語言科技之產品，利用語言學的角度頗析中文句法的規則去斷詞，並標記好POS taggint、Geo-Event Extraction、NER 等，<br>
欲使用Articut API 需在 [公司官網](https://www.droidtown.co/zh-tw/) 申請金鑰，若無則在```username``` 與```articut_key``` 輸入空字串，每日只有2000 字額度。<br>
參考程式碼：[Droidtown/NLP_Training/Unit04](https://github.com/Droidtown/NLP_Training/tree/main/Unit04)<br><br>
須引入自定義數位金融字典：FinTech_Dict.json

- 資料來源：<br>
各金控官網的數位金融發展介紹：fintech.csv

- 輸出：
各家金控兩兩比較的動名詞相似度：similarity_output.xlsx
