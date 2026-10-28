# 陀思妥耶夫斯基人物原型测试

这是一个无需后端的静态网站。将整个文件夹发布到任意静态托管服务即可使用。

## 发布到 GitHub Pages（免费）

1. 登录 GitHub，点击右上角 **+** → **New repository**，创建一个公开仓库，例如 `dostoevsky-quiz`。
2. 将本文件夹内的 `index.html`、`styles.css` 和 `script.js` 上传到仓库根目录并提交。
3. 打开仓库的 **Settings** → **Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**；分支选 `main`，文件夹选 `/(root)`，点击 **Save**。
5. 等待约一分钟，GitHub 会在此页面显示公开网址，格式通常为：`https://你的用户名.github.io/dostoevsky-quiz/`。

## 本地预览

直接双击 `index.html` 即可打开。网站不依赖构建命令或服务器。

## 发布到 Netlify Drop（不使用 GitHub）

1. 打开 <https://app.netlify.com/drop>。
2. 将 `dostoevsky-quiz-upload.zip` **解压**，然后把解压出的 `dostoevsky-quiz` 文件夹拖到网页中。
3. 等待上传完成；页面会显示一个真正可分享的 `https://…netlify.app` 网址。

## 内容说明

- 16 题、每题 4 个选项；每次开始测试时选项顺序都会随机排列。
- 答案的原型映射仅保存在 `script.js`，答题界面不会显示。
- 结果包含八种原型的得分条、主／次原型，以及并列第一时的双重原型处理。
- 字体从 Google Fonts 加载；如网络无法访问，页面会自动使用系统宋体类字体。
