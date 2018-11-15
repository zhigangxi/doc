# fariygui环境配置
1. 下载 [farigui-cocos2dx](https://github.com/fairygui/FairyGUI-cocos2dx)
2. 下载[ui编辑器](http://www.fairygui.com/)
3. 把 【*libfairygui*】 放入 cocos2d\external 目录中
4. 修改 【*libfairygui.vcxproj*】 文件，修改内容为  
`<Import Project="..\..\..\..\cocos2d\cocos\2d\cocos2dx.props" />
    <Import Project="..\..\..\..\cocos2d\cocos\2d\cocos2d_headers.props" />`
5. 修改【*cclabel.h*】文件   
`virtual void updateBMFontScale();`
