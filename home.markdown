---
title: 課程資訊
---
## 最新消息

  * [2021/12/23] [講義與投影片 11、練習 11](pages/syllabus.html)上網。
  * [2021/12/20] [練習 10 與參考解答](pages/syllabus.html)追加題目。
  * [2021/12/16] [講義、投影片 8,9 與練習 6,7,8,9 參考解答](pages/syllabus.html)錯誤更新版上網。
  * [2021/12/16] [講義與投影片 10、練習 10 與參考解答](pages/syllabus.html)上網。
  * [2021/12/16] 講義 9 關於 swaps 內容更正並移至講義 10.
  * [2021/12/10] [講義、投影片、練習、與參考解答 6, 7, 8](pages/syllabus.html)錯誤更新版上網。感謝同學幫忙除錯！
  * [2021/12/08] [講義與投影片 9、練習 9 與參考解答](pages/syllabus.html)上網。
  * [2021/12/02] 參考資料新增[Edsger W. Dijkstra Archive](pages/refs.html).
  * [2021/12/02] [練習 5, 6, 8 與期中考參考解答](pages/syllabus.html)更新。
  * [2021/12/01] [講義與投影片 8、練習 8 與參考解答, 及相關 GCL 練習檔](pages/syllabus.html)上網。
  * [2021/11/24] [講義與投影片 7、練習 7 與參考解答, 及相關 GCL 練習檔](pages/syllabus.html)上網。
  * [2021/11/18] [練習題 GCL 檔案](pages/syllabus.html)上網。
  * [2021/11/17] [講義與投影片 6、練習 6 與參考解答](pages/syllabus.html)上網。
  * [2021/11/11] [期中考參考解答](pages/syllabus.html)上網。
  * [2021/11/11] [練習 5 參考解答](pages/syllabus.html)更正。
  * [2021/11/09] [練習 2, 4 參考解答](pages/syllabus.html)筆誤更正。
  * [2021/11/07] [練習 1 參考解答](pages/syllabus.html)更正。
  * [2021/11/05] [講義與投影片 5、練習 5 與參考解答](pages/syllabus.html)更正/更新，[GCL 範例](pages/syllabus.html)上線。
  * [2021/11/02] [講義與投影片 5、練習 5 與參考解答](pages/syllabus.html)上線。
  * [2021/11/02] [Guarded Command Language 梗概](pages/syllabus.html)小幅更正。
  * [2021/10/27] [Guarded Command Language 梗概](pages/syllabus.html)上線。
  * [2021/10/27] [Guabao](pages/tools.html)資料上線。
  * [2021/10/27] [講義與投影片 4、練習 4 與參考解答](pages/syllabus.html)上線。
  * [2021/10/27] [練習0, 練習3](pages/syllabus.html)更新。
  * [2021/10/20] [講義與投影片 3、練習 3 與參考解答](pages/syllabus.html)上線。
  * [2021/10/13] [講義與投影片 2、練習 2 與參考解答](pages/syllabus.html)更新。
  * [2021/10/07] [練習 1 與參考解答、講義與投影片 2](pages/syllabus.html)更新、[練習 2 與參考解答](pages/syllabus.html)上線]。
  * [2021/10/02] [練習 0 參考解答](pages/syllabus.html)更新。
  * [2021/10/01] [練習 1 與參考解答](pages/syllabus.html)上線。
  * [2021/09/30] [講義與投影片 2, 命題邏輯公理與定理](pages/syllabus.html)上線。
  * [2021/09/23] [講義與投影片 0 & 1, 練習 0 與參考解答](pages/syllabus.html)上線。
  * [2021/09/23] 學期開始。

## 時間、地點

  * 課號: IM 2013
  * 學分: 3
  * 時間: 星期四 2,3,4
  * 地點: 管一101

## 目標

將嚴謹的、形式化的邏輯思考帶入程式設計中。訓練學生由問題的規格開始，一邊推導出解決該問題的程式，一邊做該程式為何正確的證明。由此培養對於程式正確性的要求、對於「程式設計是什麼」提出一個不同的觀點。

## 概述

「命令」(imperative) 程式語言意指把程式視為「給電腦一個個指令」的語言。我們常用的 C, Python, Java 等語言都可歸屬在此類別下。這類程式語言中，該怎麼寫程式、該怎麼證明程式的正確性？

本課程為「程式語言(Programming Languages)」系列課程之一，著眼點並不是教特定程式語言，而是討論設計程式解決問題的思考方式、設計程式使用的數學與邏輯基礎、以及程式語言與形式符號在其中扮演的角色。本課程以命令程式為主角，其核心概念包括：

 * 程式語言是一種形式語言，作為思考的工具。我們用程式語言表達概念，也用程式語言中的形式規則檢驗程式的正確性。


 *「寫程式」不只是把程式碼生出來的動作 --- 我們還得確定程式是「對」的。而確定程式正確的唯一方法是證明。

 * 「程式推導」：由問題的規格開始，一邊推導出解決該問題的程式，一邊做該程式為何正確的證明。

 * 當我們不知一個程式該怎麼寫，「這個程式該怎麼證明」這件事可以反過來透露一些「這個程式該怎麼寫」的提示。

 * 「寫程式」是一個數學行為。

 * 為了討論使用指標的程式，我們發明了相對應的「分離邏輯」，藉以證明這類程式的正確性。

本課程將討論的具體工具包括

 * Dijkstra 的 Guarded Command Language.
 * 命題邏輯 (propositional logic)、一階邏輯 (first-order logic)
 * Hoare Logic.
 * The "weakest precondition" predicate transformer.
 * Separation logic.

本課程與「程式語言：函數程式設計」有可呼應之處，但兩者都可獨立修習。本課程亦與「軟體規格與驗證（Software Specification and Verification）」非常相關：命題邏輯、Hoare Logic, predicate transformer 等都是兩堂課共同的元素。該課程談驗證 (verification), 本課程則較注重推導(derivation)，有較多手動計算與演算法問題的推導，而不會嚴謹地談到語意、函數呼叫、concurrency 等課題。

**關鍵字**： 命令程設 imperative programming, 程式推導 program derivation, 歸納法 induction, 證明 proofs, 邏輯 logic.

## 評分

僅採計期中考、期末考成績，比率機動調整。課堂中將發習題，但不計入學期分數。出席不計。

## 講師、助教

 * 講師：穆信成 scm [AT] iis.sinica.edu.tw
 * 助教：齊安浩 r09725055 [AT] ntu.edu.tw
