#User Config

- 自定义配置 Preferences

``` javascript
{
    // 主题路径
    "color_scheme": "Packages/Color Scheme - Default/Monokai.tmTheme",

    // 主题
    "theme": "Boxy Monokai.sublime-theme",

    // 自动保存
    "ensure_newline_at_eof_on_save": true,

    // 字体大小
    "font_size": 12,

    // 高亮光标所在行
    "highlight_line": true,

    // 高亮未保存文件
    "highlight_modified_tabs": true,

    // 显示文件编码
    "show_encoding": true,

    // 缩进
    "tab_size": 4,

    // 设置使用空格缩进
    "translate_tabs_to_spaces": true,

    // 设置保存时自动转换
    "expand_tabs_on_save": true,

    // 清除行尾多余空格
    "trim_trailing_white_space_on_save": true,

    // 自动更新
    "update_check": false
}

```

- 快捷键 keymap

``` javascript
[
    // 代码对齐
    {
        "keys": ["ctrl+shift+a"], "command": "alignment"
    },

    // CSS 前缀补全
    {
        "keys": ["ctrl+alt+p"], "command": "autoprefixer"
    },

    // CSS 格式化
    {
        "keys": ["ctrl+shift+c"], "command": "css_comb"
    },

    // JS 格式化
    {
        "keys": ["ctrl+shift+c"], "command": "js_format",
        "context": [{"key": "selector", "operator": "equal", "operand": "source.js,source.json"}]
    }
]
```

#Package
##功能扩展

1. **ChineseLocalizations**
语言支持 简体中文、繁体中文、日语、英语

2. **SideBarEnhancements**
侧边栏增强

3. **Less2Css**
less编译生成css

##代码补全

1. **Emmet**
html标签代码补全，多标签缩写
API： https://www.w3cplus.com/tools/emmet-cheat-sheet.html

2. **AutoFileName**
    功能简介：快捷输入文件名

3. **AutoPrefixer**
CSS3 私有前缀自动补全
`Ctrl + Alt + P`

4. **Better Completion**
代码补全

5. **DocBlock**
注释代码块
`/** + Enter`

##代码格式化

1. **Alignment**
代码对齐
`Ctrl + Alt + A`

2. **ConvertToUTF8**
编码转换为UTF8

3. **CSScomb**
CSS格式化及自定义排序
`Ctrl + Shift + C`、`右键 -> Run CSScomb`

4. **Js Format**
JS格式化
`Ctrl + Shift + C`

##视觉

1. **A File Icon**
文件图标标识

2. **Color Highlighter**
颜色高亮

3. **LESS**
LESS语法高亮

4. **Bootstrap**
Bootstrap语法高亮
