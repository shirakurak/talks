---
marp: true
---

# A snapshot of my first month with F# and SharpLogic

This is the presentation material of the event [【第10回】FUN FAN F#](https://fun-fan-fsharp.connpass.com/event/282666/)

---

# I am

- 白倉賢一（SHIRAKURA Ken'ichi）
- [Link and Motivation Inc.](https://www.lmi.ne.jp/)
  - [Motivation Cloud](https://www.motivation-cloud.com/) Developer

---

# Why F#

- OSS activity
- [F# mathematical logic library](https://github.com/GeorgePlotnikov/SharpLogic)
- F#？ [Domain Modeling Made Functional](https://fsharpforfunandprofit.com/books/)...

---

# Explore F#

- F# doesn't seem to be very popular (especially in Japan)
- .NET, functional programming, ... ( •̀ω•́ ;  )
- System F

---

Well, let's do it!

---

# 最初にやったこと

- [Codewars](https://www.codewars.com/dashboard)の簡単な問題をいくつか解いた
- 色々なサイトをざっと読んだ

![tw](img/img1.png)

- [F# mathematical logic library](https://github.com/GeorgePlotnikov/SharpLogic) を読んでいこう（文法だけの勉強の飽きそうだし...）

---

# [F# mathematical logic library](https://github.com/GeorgePlotnikov/SharpLogic)

（TODO:もうちょっとちゃんと書く）

- 論理式の定義、解釈、深さの定義
- 真偽の計算

---

```sh
$ cd SharpLogicConsole
$ dotnet run
((P && Q) -> (R <=> ~(S))
...
Formula is acceptable: [True]
================
P       Q       R       S       ~(S     (P && Q)        (R <=> ~(S)     ((P && Q) -> (R <=> ~(S))
True    True    True    True    False   True            False           False
True    True    True    False   True    True            True            True
True    True    False   True    False   True            True            True
True    True    False   False   True    True            False           False
True    False   True    True    False   False           False           True
True    False   True    False   True    False           True            True
True    False   False   True    False   False           True            True
True    False   False   False   True    False           False           True
False   True    True    True    False   False           False           True
False   True    True    False   True    False           True            True
False   True    False   True    False   False           True            True
False   True    False   False   True    False           False           True
False   False   True    True    False   False           False           True
False   False   True    False   True    False           True            True
False   False   False   True    False   False           True            True
False   False   False   False   True    False           False           True

```

---

# 読んでいて勉強になったこと1

aaa

---

# 読んでいて勉強になったこと2

aaa

---

# 最後に

- Towards the second month !
- おすすめのnext stepあれば教えてください！
- 一緒にやれそうなことがあればぜひ！
  - OSS, 勉強会, コミュニティ運営, ...

---

# Thank you!
