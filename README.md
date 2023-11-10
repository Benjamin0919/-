# 猜數字遊戲

這是一個簡單的猜數字遊戲，玩家需要在指定的範圍內猜測目標數字。

## 遊戲規則

1. 遊戲開始時，系統會隨機生成一個目標數字，通常在 x1 到 x2 之間。
2. 玩家將猜測一個數字，並提交它。
3. 系統會提供一些反饋，告訴玩家他們的猜測是太高或太低，或者是否正確。
4. 玩家將繼續猜測，直到他們猜對目標數字或已經猜了 n 次。

## 遊戲設定

遊戲的設定可以通過 `setting.xml` 文件進行調整，其中包括目標數字的範圍（x1 到 x2）和最大猜測次數（n）。
