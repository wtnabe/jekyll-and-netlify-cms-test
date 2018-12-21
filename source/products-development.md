---
title: システム開発
category: shopping
date: 2018-12-21T09:58:43.144Z
---
システム開発

なるほど、editorial_workflow にしたら Publish 以外に Save メニューが増えて、Save したものについて可能なアクションが増える。

default では Delete と Publish しかないが、Delete が Entry ではなく unpublished changed になる。

また Status が増えて、これを

 * draft
 * in review
 * ready

に設定できるようになる。

Save すると変更したファイル名を冠した `cms/:page` branch が作成される。
