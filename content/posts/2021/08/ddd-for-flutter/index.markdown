
---
title: Domain Driven Design の実装例 (Flutter)
tags: [iOS,android,Flutter]
date: 2021-08-15
draft: false
---
  
今年の上半期は仕事として主に、既存のiOS/AndroidネイティブアプリをFlutterでリニューアルするというプロジェクトに集中して取り組んでいた。 途中まで bloc + freezed で実装していたものを、急遽、 riverpod + freezed + state_notifier に書き直すことになったりしたが、先週頭に無事リニューアルリリースに漕ぎ着けた。 （段階的リリースまで完了）


ちなみに私独りの力ではなく、めちゃくちゃ優秀な同僚達がリードしてくれていたのが大きかった。


今後の振り返りのため、今回の仕事のアーキテクチャである Domain Driven Design with riverpod + freezed + state_notifier の実装例を、OpenSeaを題材にしてgithubに公開した。


[link_preview](https://github.com/misyobun/opensea-app-flutter)


![20210815204007.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5fdb5920-39c3-4fcc-98d6-4b7f4a4b6a19/57c3973f-66f3-4268-bde3-be660c06f252/20210815204007.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20231208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20231208T132810Z&X-Amz-Expires=3600&X-Amz-Signature=b4b55756bb9ea332c2960d2a4fbb6194b03e06ce2aa28227ac1432abadb6a4cb&X-Amz-SignedHeaders=host&x-id=GetObject)

