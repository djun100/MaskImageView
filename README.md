# MaskImageView
ImageView applying alpha mask (supplied as drawable) when render image

今更という感じもしますが、割り当てたマスク用のDrawableを適用して切り抜いた画像を表示するだけのImageView/ImageButtonです。
丸でも星でも好きな形にくりぬいて表示できるようになります。

マスク用のDrawableは丸でも星でもVectorDrawableでもShapeでもナインパッチでもアルファ値を取得できれば何でもOK.
そもそもマスク用のDrawableはアルファ値のみ使っているので色自体も関係ありません。
