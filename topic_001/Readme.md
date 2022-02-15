# aiter()

Return an asynchronous iterator for an asynchronous iterable. Equivalent to calling x.__aiter__().
aiter(x) itself has an __aiter__() method that returns x, so aiter(aiter(x)) is the same as aiter(x).
Note: Unlike iter(), aiter() has no 2-argument variant.

非同期イテレートのための非同期イテレータを返します。x.__aiter__()を呼び出すのと同じです。
aiter(x)自体がxを返す__aiter__()メソッドを持っているので、aiter(aiter(x))はaiter(x)と同じになります。
注： iter()と異なり、aiter()には2引数のバリアントがありません。

バージョン 3.10 で追加.

url https://docs.python.org/ja/3/library/functions.html#aiter



