#[sublime text Download](http://www.sublimetext.com/dev)
<img src="http://images.cnitblog.com/blog/100150/201212/30105834-adb210004ed5468b9f67e5384225a46d.png" alt="">
		改版过的[Monokai](http://pan.baidu.com/s/1qWr9v56) 密码: siem 代码着色，及相关资源。
## Video

- 大城小胖 [视频介绍](http://v.youku.com/v_show/id_XMzU5NzQ5ODgw.html)
- happypeter [快乐的sublime编辑器](http://www.imooc.com/learn/333)
- GreenBoots [前端开发工具技巧介绍—Sublime篇](http://www.imooc.com/learn/40)

## QQ Group
*	193076432 专注sublime-text
*	327388215 专注前端开发(css,javascript,jquery)

## License
原则上是免费的，但是偶尔会提示你购买。
## Plugins
1.   [Emmet Git](https://github.com/emmetio/emmet)，[Document](http://docs.emmet.io/)原名为：`Zencoding, 快速生成html,css`，默认扩展快捷为`tab`，如果`tab`按钮损坏，`ctrl+e`替换。
	生成规则在：
		
		Preferences -> Browser packages -> Emment -> emment -> snippets.json				
	中修改。

	[@ Emmet 中文版文档](http://www.iteye.com/news/27580)
2. 	[Side Bar](https://github.com/titoBouzout/SideBarEnhancements)`增强的侧边栏`
3. 	[Docblockr](https://github.com/spadgos/sublime-jsdocs)`增强js注释`
4.  [Alignment](https://github.com/wbond/sublime_alignment)`等号对齐`
在`Preferences -> package settings -> Alignment -> Settings User`添加冒号对齐。

		{
		 "align_indent": false,
		 "alignment_chars": ["=", ":"],
		 "alignment_space_chars": ["=", ":"]
		}
		
5. 	[AutoFileName](https://github.com/BoundInCode/AutoFileName): `文件路径自动提示`
6.  [gbk支持 GBK Encoding Support](https://github.com/akira-cn/sublime-gbk)
7.  [检测快捷键冲突](http://www.welefen.com/keymapmanager-add-check-plugins-keymap-conflict-feature.html)
8.  [markdown](https://github.com/revolunet/sublimetext-markdown-preview)
[markdown 转为 pdf](http://www.tcreator.info/social/experience/markdown-to-pdf.html)
9. [LineEndings 设置换行符](https://github.com/SublimeText/LineEndings)
10. [SublimeText插件列表](https://sublime.wbond.net/)
11. [html美化插件](https://github.com/rehorn/sublime-htmlbeautify)
12. [Sublime Text 新建文件的模版插件: SublimeTmpl](http://www.fantxi.com/blog/archives/sublime-template-engine-sublimetmpl/)
13. [前端自动化神器LiveReload配合浏览器和less/sass使用方法](http://www.cnblogs.com/liu-l/p/3902100.html)
14. [使用 Sublime Text 2 开发 Unity3D 项目](http://www.cnblogs.com/yili16438/p/3721896.html)
15. [全栈开发必备的10款 Sublime Text 插件](http://www.cnblogs.com/lhb25/p/10-essential-sublime-text-plugins.html)
		
## Settings
1. Font
推荐使用 [YaHei.Consolas.1.12.ttf](http://code.google.com/p/uigroupcode/downloads/detail?name=YaHei.Consolas.1.12.zip&can=2&q=#makechanges)，即为上图中所示字体。
2. Theme
	*   code style: 推荐使用这款[marktheme](http://code.google.com/p/uigroupcode/downloads/detail?name=Monokai.rar&can=2&q=#makechanges)
	*   [更换sidebar皮肤](https://gist.github.com/1854721)
	*   [分享一个sublime 主题 ](http://jamiewilson.io/predawn/)
	*   [颜色配色](http://colorsublime.com/)
	*   [针对 ST3 的皮肤](https://github.com/ctf0/Seti_ST3)
3. Preferences
    - 用户设置  Preferences -> Settings - User
	
	    ```javascript
		{
			"color_scheme"        : "Packages/Color Scheme - Default/Monokai.tmTheme",    // theme
			"draw_minimap_border" : true,                                                 // 右侧缩略图边框
			"font_face"           : "YaHei Consolas Hybrid",                              // 字体设置
			"font_size"           : 13,                                                   // 字体大小
			"highlight_line"      : true,                                                 // 当前行标亮
			"ignored_packages"    :	["Toggle Css Format"],                                // 开启vim模式
			"save_on_focus_lost"  : true                                                  // 失去焦点后保存
		}
		```
	
	- 全屏设置 Preferences -> Settings - More -> Distraction Free - User
	
	    ```javascript
	    {
            "line_numbers": true,      //是否显示行号
            "gutter": true,            //是否显示边列
            "draw_centered": true,      //是否居中显示
            "wrap_width": 80,           //换行宽度(单位：字符)
            "word_wrap": false,          //是否自动换行
            "scroll_past_end": true     //滚动能否超过结尾
        }
	    ```
	- Emmet css冒号后面的空格，在emmet-settings-default
	
	    ```javascript 
        "preferences": {
            "css.valueSeparator": ":",
            "css.propertyEnd": ";"
        }
        ```
		
4. [定制缩进](http://baelabs.duapp.com/Sublime/indentation.html)
5. [拼写检查](http://baelabs.duapp.com/Sublime/spell_checking.html)
6. [全屏模式，自由模式的定制](http://baelabs.duapp.com/Sublime/distraction_free.html)
7. [在sublime-text中设置浏览器预览](http://www.cnblogs.com/jikey/archive/2013/03/12/2955230.html)
8. [其它配置](http://baelabs.duapp.com/Sublime/settings.html)
9. [配置sublime右键打开](http://www.pixelstech.net/article/1445261721-Add-Sublime-Text-to-your-context-menu-on-right-click)

    ```shell
    @echo off
    SET sublimeTextPath=C:\Program Files\Sublime Text 3\sublime_text.exe
     
    REM ADD REGISTRY KEYS
    @reg add "HKEY_CLASSES_ROOT\*\shell\Open with Sublime Text 3"         /t REG_SZ /v "" /d "Open with Sublime Text 3"   /f
    @reg add "HKEY_CLASSES_ROOT\*\shell\Open with Sublime Text 3"         /t REG_EXPAND_SZ /v "Icon" /d "%sublimeTextPath%,0" /f
    @reg add "HKEY_CLASSES_ROOT\*\shell\Open with Sublime Text 3\command" /t REG_SZ /v "" /d "%sublimeTextPath% \"%%1\"" /f
     
    pause
    ```

## Skill
1. 按住 `ctrl` 键，鼠标单击就是多重选择。
2. [键盘多重选择](http://baelabs.duapp.com/Sublime/multiple_selection_with_the_keyboard.html)
3. 根据选择文本自动添加 ', "",(),[] 匹配。	
4. 搜索按钮的功能说明 ([冷风贡献](http://hi.baidu.com/chaoxinggsc/item/904a471aa937bc35f6625c42))：   
    <img src="http://e.hiphotos.baidu.com/album/pic/item/77094b36acaf2edd9ffd46a08c1001e93901936e.jpg" />	


## Default Keymap

    1. Ctrl+L             选择整行（按住-继续选择下行） 
	2. Ctrl+Shift+K(shhift+del)     删除整行，  ctrl + KK 从光标处删之行尾，Ctrl+K Backspace 从光标处删除至行首
	3. Ctrl+Shift+D       复制光标所在整行，插入在该行之前  
	4. Ctrl+D             选词 （按住-继续选择下个相同的字符串，再按，可跳到相应的方法定义处
    5. Ctrl+Shift+M       选择括号内的内容（按住-继续选择父括号） 
    6. Ctrl+/             注释整行（如已选择内容，同“Ctrl+Shift+/”效果）
    7. Ctrl + alt + /     取消注释 
    8. Ctrl+Shift+UP      与上行互换  ctrl + shift + up: 列模式编辑  
    9. Ctrl + R           跳转当前页的目标方法
    10. Ctrl+K + U        大写
    11. Ctrl+K + L        小写
    12. 鼠标中间           列模式编辑
    13. Ctrl+Shift+[]     代码折叠
    14. ctrl+k ctrl+1:    折叠所有代码 
    15. Ctrl + K,B        打开侧边栏
    16. ctrl + 回车：　　   光标后插入行，　Ctrl+Shift+Enter 光标前插入行
    17. ctrl + m:         匹配括号
    18. vim mode下        查找上一个下一个的快捷键是 是* #
    19. ctrl +z, y:       撤销，恢复撤销
    20. alt + .:          闭合当前标签
    21. Ctrl+F2:          设置书签
    22. F2:               下一个书签
    23. Shift+F2:         上一个书签
    24. ctrl + p:         即时的文件切换
    25. ctrl + shift + a: 选择标签内的内容 
    26. ctrl + 单击：      多行随意位置添加光标
    27. alt + F3( mac: ctrl + command + g): 选择页面中所有相同的词
    28. ctrl + F3:        跳转到下一个选中的词	
    29. Ctrl+Shift+P Set Syntax:html : 设置文件类型
    30. Shift + 右键:     连续多行光标选中 (by Gary Gauh)

## Emmet(zencoding) Keymap    


    1. match_pair_outward: ctrl+,向外匹配
    2. match_pair_inward: ctrl+alt+,向内匹配
    3. matching_pair: ctrl+alt+j，快速匹配html标签(phpstorm: ctrl + [])
    4. split_join_tag: shift+ctrl+`，快速成对修改html标签
    5. remove_tag: shift+ctrl+;删除包裹的html标签(phpstorm: ctrl + shift + del)
    6. increment_number_by_1: ctrl+up,数字快速增长,步长为1
    7. decrement_number_by_1: ctrl+down,数字快速递减,步长为1
    8. increment_number_by_01: alt+up,数字快速增长,步长为0.1
    9. decrement_number_by_01: alt+down,数字快速递减,步长为0.1
    10. increment_number_by_10:shift+alt+up,数字快速增长,步长为10
    11. decrement_number_by_10: shift+alt+down,数字快速递减,步长为10
    12. select_next_item:shift+ctrl+. 选择下一个属性
    13. select_previous_item: shift+ctrl+,, 选择上一个属性 
    14. wrap_as_you_type: shift+ctrl+g,包裹内容

## VIM Keymap

sublime 支持 VIM 80% 左右的快捷键，以实际为准。

    一. 移动：
        h,j,k,l: 左，下，上，右。
        w: 下一个词的词首。W:下一个单词(不含标点)。
        e:下一个词的词尾。E:不含标点。
        b:上一个词的词首。B:不含标点。
        <>: v 模式选中后进行缩进。
        >><<:向前向后缩进。 
    二. 跳转：
        %: 可以匹配{},"",(),[]之间跳转。
        H、M、L：直接跳转到当前屏幕的顶部、中部、底部。
        #H：跳转到当前屏的第#行。
        #L：跳转到当前屏的倒数第#行。
        zt: 当前编辑行置为屏顶。
        zz: 当前编辑行置为屏中。
        zb: 当前编辑行置为屏底。
        G：直接跳转到文件的底部。
        gg: 跳转到文件首。
        gd: 跳转到光标所在函数和变量的定义。
        ():跳转到当前的行首、行尾。
        {}：向上、向下跳转到最近的空行。
        [{：跳转到目前区块开头。
        ]}：跳转到目前区块结尾。
        0: 跳转到行首。
        $: 跳转到行尾。
        2$: 跳转到下一行的行尾。
        #：跳转到该行的第#个位置。
        #G: 15G,跳转到15行。
        :#：跳转到#行。
        f'n'：跳转到下一个"n"字母后。
        ctrl+b: 向后翻一页。
        ctrl+f：向前翻一页。
        ctrl+u: 向后翻半页。
        ctrl+d: 向前翻半页。
        ctry+e: 下滚一行。
    三. 选择：
        1.v: 开启可视模式。 V: 开启逐行可视模式。
        2.^V: 矩形选择。
        3.v3w: 选择三个字符。  
        4.ab：包括括号和()内的区域。
        5.aB：包括括号和{}内的区域。
        6.ib：括号()内的区域。
        7.iB：括号{}内的区域。
        8.aw：标记一个单词。
    四. 编辑：
        1. 新增：
            i: 光标前插入。
            I: 在当前行首插入。
            a: 光标后插入。
            A: 当前行尾插入。
            O: 在当前行之前插入新行。
            o: 在当前行之后插入新行。
        2. 修改 c(change) 为主：
            r: 替换光标所在处的字符。
            R：替换光标所到之处的字符。
            cw: 更改光标所在处的字到字尾处。
            c#w: c3w 修改3个字符。
            C：修改到行尾。
            ci'：修改配对标点符号中的文本内容。
            di'：删除配对标点符号中的文本内容。
            yi'：复制配对标点符号中的文本内容。
            vi'：选中配对标点符号中的文本内容。
            s：替换当前一个光标所处字符。
            #S：删除 # 行，并以新文本代替。
        3. 删除 d(delete) 为主：
            D：删除到行尾。
            X: 每按一次，删除光标所在位置的前面一个字符。
            x: 每按一次，删除光标所在位置的后面一个字符。
            #x: 删除光标所在位置后面6个字符。
            d^: 删至行首。
            d$: 删至行尾。
            dd:(剪切)删除光标所在行。        
            dw: 删除一个单词/光标之后的单词剩余部分。
            d4w: 删除4个word。
            #dd: 从光标所在行开始删除#行。
            daB: 删除{}及其内的内容。
            diB: 删除{}中的内容。
            n1,n2 d：将n1,n2行之间的内容删除。
        4. 查找：
            /： 输入关键字，发现不是要找的，直接在按n，向后查找直到找到为止。
            ?： 输入关键字，发现不是要找的，直接在按n，向前查找直到找到为止。
            *: 在当前页向后查找同一字。
            #: 在当前页向前查找同一字。
        5. 复制 y(yank)为主：
            yw: 将光标所在之处到字尾的字符复制到缓冲区中。
            #yw: 复制#个字到缓冲区。
            Y：相当于yy, 复制整行。
            #yy:表示复制从光标所在的该行往下数#行文字。
            p: 粘贴。所有与y相关的操作必用p来结合粘贴。
            ]p：粘贴到合适的缩进处。
            n1,n2 co n3：复制第n1行到第n2行之间的内容到第n3行后面。
        6. 大小写转换：
            gUU: 将当前行的字母改为大写。
            guu: 将当前行的字母改为小写。
            gUw: 将当前光标下的单词改为大写。
            guw: 将当前光标下的单词改为小写。
            a. 整篇大写:
            ggguG
            gg: 光标到文件第一个字符。
            gu: 把选择范围全部小写。
            G: 到文件结束。
            b. 整篇小写：gggUG
        7.  其它：
            J：当前行和下一行合并成一行。
        8.  移动：
            n1,n2 m n3：将n1行到n2行之间的内容移至n3行下。
    五.退出：
         1. w filename: 保存正在编辑的文件filename
         2. wq filename: 保存后退出正在编辑的文件filename
         3. q：退出不保存。
    六.窗口操作：
         1. ctrl+w p: 在两个分割窗口之间来回切换。
         2. ctrl+w j: 跳到下面的分割窗
         3. ctrl+w h: 跳到左边的分割窗。
         4. ctrl+w k: 跳到上面的分割窗。
         5. ctrl+w l: 跳到右边的分割窗。
    七.折叠：
        zo 將游標所在處的折疊打開。open。
        zc 將游標所在處已打開的內容再度折疊起來。close。
        zr 將全文的所有折疊依層次通通打開。reduce。
        zm 將全文已打開的折疊依層次通通再折疊起來。more。
        zR 作用和 zr 同，但會打開含巢狀折疊（折疊中又還有折疊）的所有折疊。
        zM 作用和 zm 同，但對於巢狀折疊亦有作用。
        zi 這是個切換，是折疊與不折疊指令間的切換。
        zn 打開全文的所有折疊。fold none。
        zN 這是 zn 的相對指令，回復所有的折疊。
    
		
## Document
*	非官方文档：[Unofficial Document英文版](https://sublime-text-unofficial-documentation.readthedocs.org/en/latest/)
[Unofficial Document中文版](http://baelabs.duapp.com/Sublime_unofficial/)
*	sublime [配置详解](http://www.feelcss.com/sublime-text-2-settings.html)
*	sublime [其它文档](http://baelabs.duapp.com/Sublime/)

## FAQ

-	如何删除安装的插件？

    1.	ctr+shift+P,输入package
    2.	查找remove package
    3.	输入你要删除的package
    4.	回车，OK

-	百度输入造成sublime闪退(感谢[leohxj](https://github.com/leohxj)提供)
	如果同时安装这两个软件，会造成sublime闪退，原因不详。但是测试过，是百度输入法的原因。希望能把这条信息加入到Wiki中，让更多人知道。
	
- Emmet tab失效问题

    - [Sublime报please wait a bit while pyV8 binary](http://jingyan.baidu.com/article/aa6a2c14d5177f0d4d19c45f.html)
    - [Sublime Text 3 解决Emmet失效的问题](http://www.jianshu.com/p/0862e754cf15)
    - [关于Sublime text 2中Emmet的安装 _html:xt无效](http://www.csdn123.com/html/itweb/20130915/119877_119876_119883.htm)

## Guide

*   [sublime text zhihu专题](http://www.zhihu.com/topic/19668076)
*   [xdebug调试](https://github.com/martomo/SublimeTextXdebug)
*	[sublimetext 3.0文档](http://baelabs.duapp.com/Sublime%20text3)
*	[Sublime Text 3 绝对神器](http://www.cnblogs.com/bananaplan/p/Sublime-Text-3-Powerful.html)
*	[SublimeText手册-tw](http://docs.sublimetext.tw/)
*	[怎样从直接Github的repository安装Sublime Text插件](http://code-tech.diandian.com/post/2012-11-10/40041273125)
*	[Sublime text2的ThinkPHP插件](http://code-tech.diandian.com/post/2012-11-14/40041132753)
*	[Ubuntu 下Sublime Text 2 输入中文解决方法](http://code-tech.diandian.com/post/2012-11-14/40042622351)
*	[如何开发Sublime Text2插件_衍生篇](http://code-tech.diandian.com/post/2012-11-16/40042306130)
*	[用sublime构建phonegap项目](http://code-tech.diandian.com/post/2012-11-16/40042845471)
*	[超级牛B编码王（二）：Sublime2之Zencoding快速上手](http://code-tech.diandian.com/post/2012-11-16/40041334087)
*	[sublime text 左侧菜单美化1](http://code-tech.diandian.com/post/2012-11-21/40042403501)
*	[在 Ubuntu 12 下安装 Sublime Text 2](http://code-tech.diandian.com/post/2012-11-29/40043724758)
*	[Sublime Text 全程指南](http://zh.lucida.me/blog/sublime-text-complete-guide/)
*	[Sublime Text 全程指引 by Lucida](http://www.cnblogs.com/figure9/p/sublime-text-complete-guide.html)
*	[sublime 有哪些使用技巧](http://www.zhihu.com/question/24896283)
*	[前端工程师手中的Sublime Text](http://www.html-js.com/article/The-frontend-tool-Megamix)
*	[Sublime 进阶使用](http://blog.saymagic.cn/2015/06/20/write-blog-by-sublime.html)
*	[JavaScript 开发者必备的10款 Sublime Text 插件](http://info.9iphp.com/essential-sublime-text-javascript-plugins/)
*	[ Sublime Text 学习日志](https://github.com/HereChen/LogList/blob/master/sublimeLog.md)
*	[Sublime Text 之运行 ES6 (基于babel)](http://www.52cik.com/2015/10/21/sublime-text-run-es6.html)
*	[sublime 英文教程](http://code.tutsplus.com/)
*	[Sublime-Tutorial](https://github.com/liveNo/Sublime-Tutorial)

## SublimeText3

- [推荐给 Web Developer 的 Sublime Text 3 插件](http://vinta.ws/code/must-have-sublime-text-packages.html)
- [Bootstrap 3 Snippets Plugin for Sublime Text 2/3](https://github.com/JasonMortonNZ/bs3-sublime-plugin)
- [自定义Emmet语法规则以快速输出bootstrap组件](http://frontenddev.org/article/sublime-does-text-3-plug-in-custom-emmet-grammatical-rules-in-order-to-quickly-bootstrap-output-component.html)
- [Sublime text 3 中文文件名显示方框怎么解决？](http://www.zhihu.com/question/24029280/answer/30256243)

## Add
*	`jikeytang#gmail.com`
