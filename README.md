# PyCrawlerMarathon

## Day 01

1.（簡答題）檔案、API、爬蟲三種取得資料方式有什麼不同？
   
   (Short Q&Ar) What is the difference between file, API, and cawler for fetching the data?
   
2.（實作）完成一個程式，需滿足下列需求：

「下載指定檔案到 Data 資料夾，存成檔名 Homework.txt」的檔案網址：https://www.w3.org/TR/PNG/iso_8859-1.txt 或任一個 .txt 的檔案網址
檢查 Data 資料夾是否有 Homework.txt 檔名之檔案
將「Hello World」字串覆寫到 Homework.txt 檔案
檢查 Homework.txt 檔案字數是否符合 Hello World 字數

   (Practice) A project that matches the requirements below:
	- Download the file from https://www.w3.org/TR/PNG/iso_8859-1.txt to your Data folder, and save as Homework.txt
	- Check whether the Homework.txt is in your Data folder
	- Rewrite the file with "Hellow World" into Homework.txt
	- Check whether the length of content in the Homework.txt matches the length of "Hello World"


## Day 02

比較一下範例檔案中的「File I/O」與「CSV Reader」讀出來的內容有什麼差異

Compare the difference between File I/O and CSV Reader

根據範例檔案的結果：

According to the result from example:

1. 取出班次一的每一個時間，印出來就好

   - Fetch the schedule of "班次1" and print out

2. 將班次一的每一個時間用一個變數保存

   - Store the data of "班次1" into a variable

3. 將所有班次和其每一個時間用一個變數保存

   - Store all of "班次" data  into a variable

(Hint： 2&3 要想一下用什麼的資料型態做整理比較適合)


## Day 03

比較一下範例檔案中的「File I/O」與「xmltodict」讀出來的內容有什麼差異

Compare the difference between File I/O and xmltodict


根據範例檔案的結果：
According from the file in Data:

1. 請問高雄市有多少地區有溫度資料？
   - How many district are there in Kaohsiung that has temperature data?
2. 請取出每一個地區所記錄的第一個時間點跟溫度
   - Gather the time and temperature from each district in Kaohsiung
3. 請取出第一個地區所記錄的每一個時間點跟溫度
   - Gather all of the time and temperatur from the first district in Kaohsiung


## Day 04
比較一下範例檔案中的「r.text」與「json.loads(r.text)」讀出來的內容有什麼差異

Compare the difference between r.text and json.loads(r.text)


自行尋找一個合適的 API 接口做練習，並且查看其回傳內容

Find a API and check the response content

