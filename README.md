# rime_delete_char

(win)Rime强制删词脚本，引用自佛振提供的删词脚本，略有删改。

control+d可以强制过滤掉词汇。

如非win系统使用，需更改代码中的反斜杠 \\ \\：

```
--windows反斜杠 \\ 
local path=string.gsub(debug.getinfo(1).source,"^@(.+\\)[^\\]+$", "%1") 
```

```
--linux、安卓等系统目录
local path=string.gsub(debug.getinfo(1).source,"^@(.+/)[^/]+$", "%1") 
```
