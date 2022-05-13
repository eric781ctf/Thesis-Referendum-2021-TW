# Thesis-Referendum-2021-TW

逢甲大學碩士學位論文

論文題目: Content and Strategy Analysis in Online Image Propaganda Using AI and Vision Recongnition

指導教授: 王銘宏教授、蔡國裕教授

## 簡介

[2021年臺灣公投四大議題](https://2021.cec.gov.tw/articleList.html?cate=C19#gsc.tab=0):

1. 您是否同意核四啟封商轉發電？
2. 你是否同意政府應全面禁止進口含有萊克多巴胺之乙型受體素豬隻之肉品、內臟及其相關產製品？
3. 你是否同意公民投票案公告成立後半年內，若該期間內遇有全國性選舉時，在符合公民投票法規定之情形下，公民投票應與該選舉同日舉行？
4. 您是否同意中油第三天然氣接收站遷離桃園大潭藻礁海岸及海域？(即北起觀音溪出海口，南至新屋溪出海口之海岸，及由上述海岸最低潮線往外平行延伸五公里之海域)

我們蒐集FB上不同陣營討論的貼文對於其中的圖片色彩、物件及文字設計上的量化分析。

## 資料蒐集

**平台: Facebook**

**時間: 2021/4/1~2021/12/18**

蒐集到的圖片皆依照 "粉專ID"\_"TimeStamp"\_"數量" 的格式儲存在[資料夾](https://github.com/eric781ctf/Thesis-Referendum-2021-TW/tree/main/Image%20Data)中[^1]。
[^1]:因Github對於單個檔案上傳的大小限制，我將資料依據25MB進行拆分壓縮上傳，資料並無先後順序問題。

蒐集的詳細資料以 : "Post ID", "Fanspage ID", "Political", "Post time", "Reaction", "Image_file name" 的欄位方式存在meta_data.csv
