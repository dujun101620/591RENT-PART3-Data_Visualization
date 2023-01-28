# 591租屋網「租金補貼」分析專案 Part3-Power BI資料視覺化　　
  
## 專案背景
　　身為經營管理專員，我為了加強自己在數據分析領域的工具與技能，自學基礎的Python、MYSQL程式語言，以及Power BI視覺化工具。同時，身為社工師的親友經常需要協助案主找尋合適且適用「租金補貼」申請的租屋，並致力於弱勢租屋議題的研討。因此藉此機會，我希望能運用所學的基礎能力，實作關於「租金補貼」的程式專案，**分析租屋市場樣貌，並在過程中學習解決程式問題並產出成果的能力，累積經驗與作品**。  
    
## 分析目的與對象
　　為瞭解適用「租金補貼」之案件在租屋市場上與一般租屋之樣貌差異，截取2022年12月20日591租屋網上的台北市與新北市的租屋案件作為分析資料。後續按以下三種租屋類別進行分析：　　
1. **一般租屋**：包含全部資料，意為租屋市場整體樣貌。
2. **租補**：包含在「標題」與「屋主說」中有租補相關關鍵字之資料，意為能申請租補之案件的整體樣貌。
3. **租補且非社宅**：因租補與社會住宅屬性不同，但在租屋網上常有同時存在或混用的狀況，因此將社會住宅篩除，以「租補且非社宅」類別分析較純粹的租補樣貌。  
    
## 作法架構  
1. [資料取得與儲存：Python](https://github.com/dujun101620/591RENT-PART1-Web_Crawler)
2. [資料清理與處理：MYSQL](https://github.com/dujun101620/591RENT-PART2-Data_Processing)
3. **視覺化圖表分析：Power BI (本篇內容)**

## 圖表內容──視覺化圖表分析：Power BI
經過MYSQL資料處理後，將可用的19,648筆*34個欄位的資料導入Power BI，並利用內建基本功能(非企業戶功能)產出可視化的圖表。
進而從中解讀分析，瞭解適用租金補貼之租屋與一般租屋有何條件、組成上的不同，並提供研討弱勢租屋議題之素材。

以下為產出之圖表內容：

![視覺化圖表-1](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0001.jpg?raw=true)
![視覺化圖表-2](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0002.jpg?raw=true)
![視覺化圖表-3](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0003.jpg?raw=true)
![視覺化圖表-4](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0004.jpg?raw=true)
![視覺化圖表-5](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0005.jpg?raw=true)
![視覺化圖表-6](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0006.jpg?raw=true)
![視覺化圖表-7](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0007.jpg?raw=true)
![視覺化圖表-8](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0008.jpg?raw=true)
![視覺化圖表-9](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0009.jpg?raw=true)
![視覺化圖表-10](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0010.jpg?raw=true)
![視覺化圖表-11](https://github.com/dujun101620/591RENT-PART3-Data_Visualization/blob/main/591%E9%9B%99%E5%8C%97%E7%A7%9F%E9%87%91%E8%A3%9C%E8%B2%BC%E5%B0%88%E6%A1%88_page-0011.jpg?raw=true)
  
## 心得總結

