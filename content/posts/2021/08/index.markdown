---
title: ""
tags: ["iOS","android","Flutter"]
date: "2021-08-15T00:00:00"

---

今年の上半期は仕事として主に、既存のiOS/AndroidネイティブアプリをFlutterでリニューアルするというプロジェクトに集中して取り組んでいた。 途中まで bloc + freezed で実装していたものを、急遽、 riverpod + freezed + state_notifier に書き直すことになったりしたが、先週頭に無事リニューアルリリースに漕ぎ着けた。 （段階的リリースまで完了）

ちなみに私独りの力ではなく、めちゃくちゃ優秀な同僚達がリードしてくれていたのが大きかった。

今後の振り返りのため、今回の仕事のアーキテクチャである Domain Driven Design with riverpod + freezed + state_notifier の実装例を、OpenSeaを題材にしてgithubに公開した。




![](./278FC6EDF211B2DCB03F899498025427.png)



テスト



