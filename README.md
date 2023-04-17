# DoReMi_nako3
[日本語プログラミング言語「なでしこ３」](https://nadesi.com/doc3/)でWeb Audio APIを使って、MMLや[テキスト音楽「サクラ」](https://sakuramml.com/)の[ストトン表記](https://sakuramml.com/wiki/index.php?%E3%82%B9%E3%83%88%E3%83%88%E3%83%B3%E8%A1%A8%E8%A8%98)風味なドレミのテキストを演奏したりなんだりしたいというNAKO3プラグインです。

なでしこｖ１の「MML演奏」のようにMIDIに変換するのではなく直接鳴らすやつです。

歌詞のカラオケ表示、演奏と連携した鍵盤の表示、時間領域(TimeDomain)の波形と周波数領域(Frequency)の波形を表示する機能があります。


## テスト
### 演奏
- [とりあえず演奏](https://snowdrops89.github.io/DoReMi_nako3/test/test0.html)
※画面をクリックすると演奏します。
```
「ドレミファソラシ`ドー」をドレミ演奏。
```
- [再生・停止・一時停止・再開](https://snowdrops89.github.io/DoReMi_nako3/test/test1.html)
### 字幕
- [字幕表示（カラオケ表示）](https://snowdrops89.github.io/DoReMi_nako3/test/test2.html)
- [ダミートラックでカラオケ表示](https://snowdrops89.github.io/DoReMi_nako3/test/test3.html)

> 漢字や拗音など主旋律の音符と歌詞の文字数が合わない時もカラオケ表示させる。

### 波形描画
- [波形描画](https://snowdrops89.github.io/DoReMi_nako3/test/test4.html)

> 時間領域(TimeDomain)の波形と周波数領域(Frequency)の波形を表示。

### 鍵盤描画
- [鍵盤の連携表示](https://snowdrops89.github.io/DoReMi_nako3/test/test5.html)

> 鍵盤を描画して連動させる。
