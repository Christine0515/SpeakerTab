# SpeakerTab

A website with one tab for each ESSEC guest speaker session in 2026. Each tab shows the session's key takeaways and an interactive game: a quiz, matching pairs, flashcards or a sorting game.

Live site: https://christine0515.github.io/SpeakerTab/

## 添加一场新讲座（无需写代码）

1. 打开编辑模式：https://christine0515.github.io/SpeakerTab/?edit
2. 点 **+ Add session**，填写讲者、日期、主题、要点，选择游戏类型并粘贴内容（右侧有实时预览）。可以一次加好几场。
3. 页面顶部会出现黄色提示框：
   - 点 **1. Copy data** 复制全部内容
   - 点 **2. Open data.json on GitHub**，在打开的编辑页里全选（Ctrl/Cmd + A），粘贴，点 **Commit changes**
4. 等 1–2 分钟，网站就更新了。

普通访问者打开不带 `?edit` 的网址，只会看到游戏，不会看到编辑按钮。

## 文件说明

- `index.html`：网站本身（样式和游戏逻辑），平时不用改
- `data.json`：所有讲座内容，添加或修改讲座只改这个文件
