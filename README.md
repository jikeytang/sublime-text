#[sublime text Download](http://www.sublimetext.com/dev)
<img src="http://images.cnitblog.com/blog/100150/201212/30105834-adb210004ed5468b9f67e5384225a46d.png" alt="">
		改版过的[Monokai](http://code.google.com/p/uigroupcode/downloads/detail?name=YaHei.Consolas.1.12.zip&can=2&q=#makechanges)代码着色。
## Info
大城小胖[视频介绍](http://v.youku.com/v_show/id_XMzU5NzQ5ODgw.html)

## Key
原则上是免费的，但是偶尔会提示你购买。
## Plugins
1.   [Emmet Git](https://github.com/emmetio/emmet)，[Document](http://docs.emmet.io/)原名为：`Zencoding, 快速生成html,css`，默认扩展快捷为`tab`，如果`tab`按钮损坏，`ctrl+e`替换。
	生成规则在：
		
		Preferences -> Browser packages -> Emment -> emment -> snippets.json				
	中修改。
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
		
## Settings
1. Font
推荐使用 [YaHei.Consolas.1.12.ttf](http://code.google.com/p/uigroupcode/downloads/detail?name=YaHei.Consolas.1.12.zip&can=2&q=#makechanges)，即为上图中所示字体。
2. Theme
	*   code style: 推荐使用这款[marktheme](http://code.google.com/p/uigroupcode/downloads/detail?name=Monokai.rar&can=2&q=#makechanges)
	*   [更换sidebar皮肤](https://gist.github.com/1854721)
3. 	Preferences -> Settings - User
	
		{
			"color_scheme"        : "Packages/Color Scheme - Default/Monokai.tmTheme",    // theme
			"draw_minimap_border" : true,                                                 // 右侧缩略图边框
			"font_face"           : "YaHei Consolas Hybrid",                              // 字体设置
			"font_size"           : 13,                                                   // 字体大小
			"highlight_line"      : true,                                                 // 当前行标亮
			"ignored_packages"    :	["Toggle Css Format"],                                // 开启vim模式
			"save_on_focus_lost"  : true                                                  // 失去焦点后保存
		}
		
4.  Keymap
	[豪情友情提供](http://www.cnblogs.com/jikey/archive/2012/11/26/2788921.html)
		
## Document
*	非官方文档：[Unofficial Document](https://sublime-text-unofficial-documentation.readthedocs.org/en/latest/)
*	sublime [配置详解](http://www.feelcss.com/sublime-text-2-settings.html)

## FAQ

*	如何删除安装的插件？

1.	ctr+shift+P,输入package
2.	查找remove package
3.	输入你要删除的package
4.	回车，OK
