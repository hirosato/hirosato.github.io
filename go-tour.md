# [A tour of Go](https://go-tour-jp.appspot.com/list0)

## Methods and interfaces
### [12 - Interface values with nil underlying values](https://go-tour-jp.appspot.com/methods/12)
なぜNPEが起きないか分かった。

### [13 - Nil interface values](https://go-tour-jp.appspot.com/methods/13)
短絡的だけど、NPE起きないって言われた後これ見ると、うーん、、、ってなるね。

### [17 - Stringers](https://go-tour-jp.appspot.com/methods/17)
toStringはこれだね。

## Concurrency
### [2 Channels](https://go-tour-jp.appspot.com/concurrency/2)
並列処理をするときに、ロックだとか待つだとか、そういうことを意識しなくてよい。メインのスレッドとのやり取りするときに同期したりもいらない。神。

### [Range and Close](https://go-tour-jp.appspot.com/concurrency/4)
rangeで終わるまで引き出せる。
