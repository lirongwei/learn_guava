#尽量不要使用null
null 具有不明确的意义，我们很难从 return null 中看出 null 到底代表着是成功，失败，还是不可见。
null 容易引起 app 崩溃，对 null 不进行捕获通常会有严重的后果。尤其是在 app 开发的过程中。
null 做为 map 里头的 key 是不可接受的。谁能想到这个key 代表着什么含义。

#特殊情况

在列表或者 map 中当作 value 使用。但是为了代码的可读性，还是强烈建议把 null 替换成别的值，例如 success, fail, absent
