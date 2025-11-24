# 自由記述問題AI採点システム
このドキュメントへのリンク  
https://github.com/endo0507/AIScoringApp/blob/main/README.md

[![README.mdのQRコード](https://github.com/endo0507/AIScoringApp/blob/main/QRcodes/README_QR.png "README.md")](https://github.com/endo0507/AIScoringApp/blob/main/README.md)
## 使い方
0. 問題用紙サンプル.docx をあらかじめWordで開いておく。
1. 「ファイルを選択」(Choose File)を押し、解答サンプル画像を開く。
2. ~~「問題・採点条件」のところにある、「認識」を押す。~~
3. 問題用紙の問題文と採点条件を「問題・採点条件」のテキストボックスにコピペ。  
   （教員が問題用紙のデータからコピペするのを想定）
4. 「解答」のところにある、「認識」を押す。
5. 該当する部分を画像内から範囲選択する。
6. ~~「問題・採点条件」と~~「解答」の文字認識が正しく行えていることを確認する。
7. 「採点開始」を押して、AIによる採点を行う。
8. 「採点結果」欄の内容を確認する。
## 既知の不具合
- 問題・解答文の文字認識完了まで30秒程度以上かかる。
- （特に手書き文字の）認識精度が低い。（誤認識した場合は、手入力で修正可能です）

現時点で判明しているこれらの不具合については、将来的に改善・解決する予定です。
## 調査アンケート
以下のリンクから、調査アンケートへのご協力をお願いします。  
この調査では、本システムの有用性という観点で主に評価して頂きます。  
改善点等記入の際は、なるべく既知の不具合以外の部分について回答頂けると有難いです。  
https://docs.google.com/forms/d/e/1FAIpQLSc8oyr41E0AhvauGewNaRTHkXRNQ4rWSW5cnsMP2B4HNk0qMg/viewform

[![アンケートのQRコード](https://github.com/endo0507/AIScoringApp/blob/main/QRcodes/enquete_QR.png "卒業研究調査アンケート")](https://docs.google.com/forms/d/e/1FAIpQLSc8oyr41E0AhvauGewNaRTHkXRNQ4rWSW5cnsMP2B4HNk0qMg/viewform)
