  # ChDict

[教育部《重編國語辭典修訂本》](http://dict.revised.moe.edu.tw/) Python 網路爬蟲 (即時資料查詢)  
A web crawler for the Chinese-Chinese dictionary published by the Ministry of Education in Taiwan.


### 需求 Dependencies

- Python 3
- 模組 Modules
    - re
    - requests
    - argparse
    - bs4 (BeautifulSoup 4)
    - urllib

### 使用方式 Usage

```
python3 chdict.py [<list of keywords separated by spaces> | -f <input file>] [-o <output file>]
```

#### 使用範例 Sample Usage

```
> python3 chdict.py 狗 貓 可愛
> python3 chdict.py -f input.txt -o output.txt
```

#### 範例輸出 Sample Output

```
狗：[名]食肉犬科動物的通稱。種類很多，嗅覺和聽覺都很靈敏，可訓練來追蹤、守衛、導盲、救生或飼為寵物，且性忠誠，為人類之友。姓。如漢代有狗未央。[動]諂媚奉承。如：「底下的人專會狗著他。」
貓：[名]動物名。哺乳綱食肉目。面圓齒銳，耳殼短小，眼大，瞳孔會因光線強弱而變大小，聽視覺都很敏銳，四肢較短，腳有銳爪，掌有肉墊，行動敏捷，善捕鼠。[動]北平方言。指躲藏。如：「他貓起來了，害大夥兒找不著。」
可愛：討人喜愛。《書經．大禹謨》：「可愛非君？可畏非民？」宋．陸游《老學庵筆記．卷四》：「荊棘中有崖石，刻樹石二大字，奇古可愛。」流行語。可憐沒人愛。如：「你說她長得可愛？哼！可憐沒人愛！」
```

### 授權 License

[The MIT License (MIT)](LICENSE.md)

Copyright © `2016` `Jasmine Chen`

#### 教育部公眾授權

[《重編國語辭典修訂本》公眾授權使用說明](http://resources.publicense.moe.edu.tw/reviseddict_10312.pdf)

中華民國教育部（Ministry of Education, R.O.C.）。《重編國語辭典修訂本》（版本編號：2015_20151208）網址：http://dict.revised.moe.edu.tw/
