作業二要求
===
使用自行找的資料內容 (CSV or JSON)  
將這組資料整理過後進行資料視覺化  
從圖中回答三個問題  

作業內容：  
現有一筆資料顯示了某餐廳小費收取記錄，而該資料欄位如下：  
Here's a description of each column in the dataset：

1. total_bill： The total bill amount, including the cost of food and drinks.

3. tip： The tip amount given by the customer.

4. sex： The gender of the customer (e.g., Male or Female).

5. smoker： Whether the customer is a smoker or not (e.g., Yes or No).

6. day： The day of the week when the transaction occurred (e.g., Sun, Sat, Thu, etc.).

7. time： The time of day when the transaction occurred, typically categorized as Lunch or Dinner.

8. size： The size of the party or group of customers.  

透過將json資料進行資料視覺化，本次作業使用了 matplotlib 中的 scatter（x,y）散點圖呈現 total_bill 和 tip 之間的關係  
[csv檔案來源](https://www.kaggle.com/datasets/sakshisatre/tips-dataset?resource=download&select=tip.csv)
