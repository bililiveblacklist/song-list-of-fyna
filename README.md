# Fyna的歌单

修改自项目alan314m/song-list-of-nanakaie

<br />

## 运行项目前端

此项目使用Next.JS(一个基于React.JS的前端框架)撰写。如果运行环境没有Node.JS，请先下载[Node.JS](https://nodejs.org)

<br />

### 启动开发环境

启动开发服务器请使用如下指令：

```bash
npm install

npm run dev
# or
yarn dev
```
默认3000端口

<br />

## 导出静态网站

目前next.config.js参考的腾讯云文档。其他部署环境可能需要更改

```bash
npm run build
npm run export

# or

npm run buildssg
```

Next.JS自动生成的"out"文件夹可直接用于部署静态网页

<br />

## Excel歌单转Json

转Excel到Json需要[Python3](https://www.python.org/), pandas和openpyxl

目前歌曲信息储存于"./public/music_list_7.json"

金山文档输出Excel覆盖"./music_list_7.xlsx"并运行"./music_list_to_json.py"自动输出json文件覆盖"./public/music_list_7.json"

<br />
<br />
<br />
