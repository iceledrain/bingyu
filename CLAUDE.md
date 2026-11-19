# bingyu

小手机「冰雨机」，全在 `index.html` 一个文件里，没有构建。

- 改了 `index.html` 就把开头 `BYJ_VER` 末位加 1。
- 存档在浏览器 IndexedDB（`ledphone`），删改字段要在读档那段兼容旧数据。
- 画出来的图单独存在 IndexedDB 的 `img:<id>`，存档里只留 `idb:<id>`，备份不带图。
- 改完验证过直接推 `main`，不开 PR、不问、不强推。
- 话少：回复和界面里都不写说明解释。
