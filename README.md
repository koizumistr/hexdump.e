# hex_dump.e

ファイルの内容を16進数で表示するプログラムです。標準コマンドにhdとかhexdumpというがあるかと思いますけど、それとほぼ同じことをします。
はい、恒例の車輪の再発明です。新しいのはEiffelで書いていることくらいでしょうか。Liberty Eiffelで（Eiffelとして警告なく）コンパイルできることを確認しています。（残念ながらCとしては警告が出ています。）

ChangeLogにも書いてあるように、最初にコミットされているものはかなり以前に作成したものです。当時はSmartEiffelでコンパイルできることを確認していた、、、はずです。
今となっては意味のないものではありますが、今のものとの差分が見えるとちょっと面白いかなと思ってコミットしました。prettyの適用の有無が異なりますので、興味のある方は空白の違いを無視するようにしてdiffを取ってみてください。
