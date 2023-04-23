# rime_delete_char

(win系统使用)

rime强制删词脚本，引用自佛振提供的删词脚本，略有删改。

control+d可以强制过滤掉词汇。

如非win系统使用，需把代码中的：

```
local path=string.gsub(debug.getinfo(1).source,"^@(.+\\)[^\\]+$", "%1")
```
反斜杠 \\ 改为 /
