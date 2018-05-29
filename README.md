# sublime-config
##1、功能扩展

    插件名称：ChineseLocalizations
    功能简介：语言支持 简体中文、繁体中文、日语、英语

    插件名称：SideBarEnhancements
    功能简介：侧边栏增强

    插件名称：Less2Css
    功能简介：less编译生成css

##2、代码补全

    插件名称：Emmet
    功能简介：html标签代码补全，多标签缩写
    语法：
    后代	兄弟	上级	分组	乘法	自增	ID和类	自定义属性
    >	+	^	()	*	$	#id.class	p[nck='1']
    更多： https://www.w3cplus.com/tools/emmet-cheat-sheet.html

    插件名称：AutoFileName
    功能简介：快捷输入文件名

    插件名称：AutoPrefixer
    功能简介：CSS3 私有前缀自动补全
    快捷键：Ctrl + Alt + P

    插件名称：Better Completion
    功能简介：代码补全

    插件名称：DocBlock
    功能简介：注释代码块
    快捷键：/** + Enter

##3、代码格式化

    插件名称：Alignment
    功能简介：代码对齐
    快捷键：Ctrl + Alt + A

    插件名称：ConvertToUTF8
    功能简介：编码转换为UTF8

    插件名称：CSScomb
    功能简介：CSS格式化及自定义排序
    快捷键：Ctrl + Shift + C   右键 -> Run CSScomb

    插件名称：Js Format
    功能简介：JS格式化
    快捷键：Ctrl + Shift + C

##4、视觉

    插件名称：A File Icon
    功能简介：文件图标标识

    插件名称：Color Highlighter
    功能简介：颜色高亮

    插件名称：LESS
    功能简介：LESS语法高亮

    插件名称：Bootstrap
    功能简介：Bootstrap语法高亮

    插件名称：Color Highlighter
    功能简介：颜色高亮

#User Config

##Preferences
- 自定义配置
``` json
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

##keymap
- 快捷键
``` json
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

