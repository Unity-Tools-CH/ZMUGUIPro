该课程是一款基于Unity UGUI拓展的插件ZMUGUIPro，主要目的是为一系列常用功能提供解决方案。

原 ZMUIFrameWork 配套插件库。

该插件在UGUI的基础上拓展了以下组件：

            Text-> Text Pro

            Image-> Image Pro

            Button-> Button Pro

            TextMeshPro GUI-> TextMesh Pro

功能介绍：

1.Text Pro 功能介绍：

            1.支持本地化多语言文本

            2.支持高性能描边

            3.支持文本顶点颜色渐变

            4.支持文本双色渐变

            5.支持文本三色渐变

            6.支持文本双色+描边

            7.支持文本投影

             8.支持文本投影顶点颜色渐变

 

2.Image Pro 功能介绍：

            1.支持高性能自定义图片遮罩(圆形、多边形、矩形、三角形、百分比图形)

            2.支持本地化静态多语言图片

            3.支持本地化Resources多语言图片

            4.支持本地化AssetBundle多语言图片

            5.支持自定义指定语言图片大小尺寸

3.Button Pro 功能介绍：

            1.支持按钮 双击事件 (可自定义双击间隔、触发事件)

            2.支持按钮 长按事件 (可自定义按下时长、触发事件)

            3.支持按钮 点击缩放 (可自定义缩放系数)

            4.支持按钮 点击音效 (可自定义按钮音效)

4.TextMesh Pro 功能介绍：

            1.支持本地化多语言文本

            2.更多功能正在拓展中...

 

无文本、Unity OutLine、TextPro、TextMeshPro 描边性能对比图：



性能对比总结：

前提：各个组件的Tris和Verts减去无文本的Tris和Verts。

小知识：Tris (Mesh中的三角面)  Verts(Mesh中的顶点数)

Unity Outline 一个文字占用Tris和Verts分别为：10,30

TextPro          一个文字占用Tris和Verts分别为：2,6

TextMeshPro 一个文字占用Tris和Verts分别为：4,8 

TextPro描边性能是Unity Outline描边性能的 5 倍

TextMeshPro描边性能是Unity Outline描边性能的 4 倍

总结：TextPro胜出，性能较好。
