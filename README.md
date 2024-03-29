## 安装gitbook

## 写配置文件book.json
````json
{
  "title": "前端学习笔记",
  "author": "lixiaojian",
  "description": "日常学习笔记整理",
  "language": "zh-hans",
  "gitbook": "3.2.3",
  "styles": {
    "website": "./styles/website.css"
  },
  "structure": {
    "readme": "index.md"
  },
  "plugins": [
    "-sharing",
    "-livereload",
    "-lunr",
    "-search",
    "-fontsettings",
    "-livereload",
    "prism",
    "-highlight",
    "expandable-chapters",
    "search-pro",
    "code",
    "theme-lixj"
  ],
  "variables": {
    "themelixj":{
      "logo": "/resource/logo.png",
      "nav":[
        {
          "href":"https://www.lixj.vip",
          "target":"_blank",
          "text": "我的简介"
        },
        {
          "url":"https://www.lixj.vip/#resume",
          "target":"_blank",
          "text": "我的简历"
        }
      ]
    },
    "prism": {
      "css": [
        "prismjs/themes/prism-solarizedlight.css"
      ]
    }
  },
  "pluginsConfig": {
    "theme-lixj":{
      "search-placeholder":"输入关键字搜索"
    }
  }
}
````

### 安装依赖
````text
gitbook install
````

### 启动服务

`````text
gitbook serve 
`````

### 打包
`````text
gitbook build
`````