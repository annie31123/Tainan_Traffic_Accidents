# Tainan_Traffic_Accidents
視覺化題目:臺南市交通事故十大原因

動機&目的: 因為最近很多朋友在台南出車禍，因此很想了解臺南市交通事故的原因，
希望能藉這個圖表，讓大家思考臺南市的交通問題，和如何防治。

使用到的技術: javascript  css html php

設計流程: 
先用php parse(本地的)資料，整理之後打包成json檔回傳
javascript接收資料後，整理資料(排序)
再經由c3js去畫出圖表，
最後調整顏色、字型、排版
