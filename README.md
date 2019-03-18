# 目的

把 FreeBSD FAQ 從英文翻成中文！

# 進度(已完成)

Abstract, CHAPTER_19

# 進度(進行中)

CHAPTER_4
CHAPTER_5

## 英文原文
https://www.freebsd.org/doc/en_US.ISO8859-1/books/faq/index.html

## 目前有的中文
https://www.freebsd.org/doc/zh_TW/books/faq/index.html

其他的大家歡迎邊認領邊翻囉！

# 方法

- 找到想翻的章節（例如：Chapter 17. The FreeBSD Funnies）
  - 確定有沒有人在翻，有的話應該會有一個叫做 CHAPTER_17 的檔案，直接加入吧！
  - 沒有的話就開一個新的叫做 CHAPTER_17 的檔案，並把英文原文複製進去
- 接下就一條一條翻囉！請盡量以一組 Q&A 為單位，方便校對

# 校對
- 校對會開在另一個 branch (review_chXX) 
- 在對應章節中，會逐條進行校對，並提供前後版本參考
- 校對到一個段落後，會開啟一個 Pull Reqeust 給原翻譯者 review
- 如果覺得校對 ok ，請留下校對後的版本直接 merge 回 master 就可以
- 如果覺得有新的想法或翻法，可以再繼續加上 v3, v4 ... 到校對完畢為止
- 其他人也可以一起來看
