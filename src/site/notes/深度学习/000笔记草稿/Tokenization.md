---
{"dg-publish":true,"permalink":"//000/tokenization/","dg-note-properties":{}}
---

词的拆分，转成数字化
样本文字：input
转化成的数字：token
tiktoken：利用库来进行文字对应。有时候一个字可能对应多个数字，也就是它可能独立或与别的文字组成新单词，叫做subword。
如何拆分是编码的事，但最后分割成token的数量才被称为context_length



