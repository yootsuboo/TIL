# make links

### ハードリンク

- 一つのファイルの実態に複数の名前をつける

- 元のファイルを削除しても消えない

- すべてのハードリンクがなくたったと気に削除される

- 異なるディレクトリをまたいでの作成が**できない**

- ディレクトリに対して使うことができない

### シンボリックリンク

- リンク先のパス名が書かれた特殊ファイルで、リンク先のみが実在

- シンボリックリンクを残したままファイルを削除したり、ファイルを移動するとファイルを参照できなくなる(PATHを参照しているため)

