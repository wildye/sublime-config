User Config
=

## 1. 自定义配置 Preferences


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

## 2. 快捷键 keymap

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

Package
=

## 1. 功能扩展

- **ChineseLocalizations**<br>
语言支持 简体中文、繁体中文、日语、英语

- **SideBarEnhancements**<br>
侧边栏增强

- **Less2Css**<br>
less编译生成css

## 2. 代码补全

- **Emmet**<br>
html标签代码补全，多标签缩写<br>
API： https://www.w3cplus.com/tools/emmet-cheat-sheet.html

- **AutoFileName**<br>
    功能简介：快捷输入文件名

- **AutoPrefixer**<br>
CSS3 私有前缀自动补全<br>
`Ctrl + Alt + P`

- **Better Completion**<br>
代码补全

- **DocBlock**<br>
注释代码块<br>
`/** + Enter`

## 3. 代码格式化

- **Alignment**<br>
代码对齐<br>
`Ctrl + Alt + A`

- **ConvertToUTF8**<br>
编码转换为UTF8

- **CSScomb**<br>
CSS格式化及自定义排序<br>
`Ctrl + Shift + C`、`右键 -> Run CSScomb`

- **Js Format**<br>
JS格式化<br>
`Ctrl + Shift + C`

## 4. 视觉

- **A File Icon**<br>
文件图标标识

- **Color Highlighter**<br>
颜色高亮

- **LESS**<br>
LESS语法高亮

- **Bootstrap**<br>
Bootstrap语法高亮
