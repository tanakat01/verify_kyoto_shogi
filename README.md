# verify_kyoto_shogi
京都将棋の弱解析結果を検証する

注) Notebook形式で作成してみましたが，Google Colab上ではメモリ不足で動きませんでした．64GB搭載の MacBook Pro上では動きます．

この Notebookは[第26回ゲームプログラミングワークショップ GPW-2021](https://www.gi-ipsj.org/gpw/2021/) で [ベストポスター賞](https://www.gi-ipsj.org/gpw/2021/to_award.html)を受賞した電気通信大学の塩田 雅弘さん，伊藤 毅志さんによる[京都将棋の弱解決](https://ipsj.ixsq.nii.ac.jp/ej/?action=pages_view_main&active_action=repository_view_main_item_detail&item_id=213428&item_no=1&page_id=13&block_id=8)の発表の結果を検証するために作成しました．

Notebookではなくてpythonファイル形式でダウンロードして pypy で動かすと1時間ほどで検証が終わると思います．ただし，この場合もメモリは32GB以上は必要と思われます．

