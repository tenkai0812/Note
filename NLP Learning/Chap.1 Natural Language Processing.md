___
date : 2023-03-23 20:00<br>
aliases : []<br>
Source URL : https://www.analyticsvidhya.com/blog/2021/06/part-1-step-by-step-guide-to-master-natural-language-processing-nlp-in-python/
Topics : [[Natural Language Processing]]
___
## part1. Step by Step Guide to Master NLP – Introduction
### Introduction of NLP
自然語言處理屬於人工智慧的其中一個分支，為何會出現這樣特別的一個區塊呢?我們都知道計算機在處理數字與表格上面是非常方便且有效的，但是人類所創造的多種語言並非有結構化的表格或是數據，因此向計算機解釋這些語言並非一件容易的事。所以NLP就是讓計算機理解非結構化的文本並從中抓到關鍵訊息並與人類溝通。

### Table of Contents
**1.** What is Natural Language Processing (NLP)?
什麼是自然語言處理（NLP）？

**2.** Applications of Natural Language Processing.
自然語言處理的應用

**3.** Understanding Natural Language Processing.
理解自然語言處理

**4.** Difference between Rule-based NLP and Statistical based NLP.
Rule-based NLP 和 Statistical based NLP 的區別

**5.** Components of Natural Language Processing.
自然語言處理的組成部分

**6.** Ambiguity and Uncertainty in Natural Language Processing.
自然語言處理中的歧義和不確定性

### What is Natural Language Processing?
自然語言處理(NLP)是CS和AI的一個子領域，它處理計算機和人類（自然）語言之間的交互。當我們想要將機器學習或深度學習算法應用於包含文本和語音的數據集時，這一點變得至關重要。
例如我們可以用NLP創造AI系統，像是:
-   語音識別
-   文件摘要
-   機器翻譯
-   垃圾郵件檢測
-   姓名真假識別
-   問答
-   自動完成文章
-   預測打字等

### Difference between Rule-based NLP and Statistical based NLP.
-  Rule-based Natural Language Processing
	運用常識推理來處理任務，例如:
	- 極冷的溫度會導致凍傷甚至死亡
	- 熱咖啡會灼傷人的皮膚
	- 其他常識推理性任務
	但是這些過程可能需要更多時間，並且要手動操作
	
-  Statistical Natural Language Processing
	使用大量數據並從中得出結論。為了訓練NLP models，因此使用ML，在完成大量數據的訓練後，經過訓練的模型將具有推導的正向結果
-  Comparison (Pros and Cons)
| Rule Based NLP        | Statistical NLP     |
| --------------------- | ------------------- |
| +1.有彈性的           | +1.便於擴展         |
| +2.除錯簡單           | +2.自主學習         |
| +3.不需要太多訓練     | +3.快速發展         |
| +4.理解語言           | +4.覆蓋率高         |
| +5.精準度高           |                     |
| -1.需要熟練的開發人員 | -1.需要大量數據     |
| -2.分析緩慢           | -2.除錯困難         |
| -3.覆蓋緩慢           | -3.並不理解文字內容 |


### Components of Natural Language Processing
NLP由兩個基礎部分所組成:
- Natural Language Understanding (NLU) (自然語言理解)
	NLU其中又包含:
	- Lexical Ambiguity (詞意雙關)
	- Syntactical Ambiguity (語句雙關)
	- Referential Ambiguity (省略主詞)
- Natural Language Generation (NLG) (自然語言生成)
	NLG其中又包含:
	- Text Planning（文本規劃)
	- Sentence Planning（語句規劃）
	- Text Realization（文本實現）
#### Natural language Understanding(NLU)
NLU的任務自然比NLG困難,想像我們正在學習或解釋一種語言實，存在很多歧義（雙關），例如:
	Sentence: He is looking for a match
	這句話中的match是指一個伴侶還是一場球賽你並不清楚
- Lexical Ambiguity

- 
	

