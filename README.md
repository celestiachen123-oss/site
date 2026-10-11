# 个人网站 — 文档原文版

本次内容以《个人网站.docx》为准，按原文保留六部分与顺序：
Home → Fieldwork → Internships & Volunteering → Beyond School → Stage → Contacts。
正文、成绩、职务名称与联系方式按用户文档保留，未擅自润色或与旧活动列表合并。
当前版本仅用于本地预览，不发布。

## 预览

安装依赖后运行 `npm run build`，然后 `npm run preview -- --port 5173`。
日常开发可使用 `npm run dev`。当前环境使用已构建版本提供本地预览。

## 替换图片与视频

1. 把图片、视频放入 `public/media/`，例如 `public/media/wang-yanan.jpg`。
2. 在 `src/media.json` 找到对应的区域，例如 `wang-yanan`。
3. 填写 `src` 为 `/media/wang-yanan.jpg`，并填写 `alt` 图片说明。
4. 视频区域可填写 `poster` 为封面图片路径；播放器已带播放、暂停、音量和全屏控件。
5. 重新构建并刷新本地预览。

空白区域是明确标注的图片/视频预留位，不是上传按钮。此版本没有上传或存储服务。
首页现有临时帷幕视频位于 `public/curtain-loop.mp4`，封面为 `public/curtain-loop.jpg`，可以替换同名文件。
临时素材来源：Kaboompics / Pexels — https://www.pexels.com/video/moving-red-curtain-4863244/ 。这不是学生个人作品。

文档原文保存在 `src/document-text.json`，页面结构在 `src/main.jsx`，排版在 `src/style.css`。
保留 1700px 最大版心及移动端适配。首页为全屏视频，Contacts 为整屏收尾。
