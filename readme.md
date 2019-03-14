# Flutter UI
![https://raw.githubusercontent.com/efoxTeam/flutter-ui/dev-ken/android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png](https://raw.githubusercontent.com/efoxTeam/flutter-ui/dev-ken/android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png)

> flutter ui 开发者社区 提供各种flutter相关开发教程

## 项目背景
* Google推出Flutter跨平台解决方案，渐渐地受到了开发者们的关注，结合dart使用，能够用一套代码实现开发iOS与Android两套应用，未来还将可以直接编译成桌面应用。
* Flutter拥有丰富的组件库，多样化的主题与UI风格，让开发者更简单的上手完成界面交互，从而提高了开发效率。
* 随着大厂纷纷着手研究与实践后，本团队利用工作之余，也迈进对Flutter了认知的旅程中，并对组件进行归类与逐步细化，着手于技术要点分析与总结。
* 此套组件库在几次没有硝烟的研讨中，命名为"Flutter UI"，使命为"知识千万点，学习第一条。代码快点敲，bug无数行"。没错，就是这么不押韵。
* 希与各位技术大大，有兴趣的小伙伴们一起交流，一起进步。

## 开发者如何参与完善控件
<img src="https://raw.githubusercontent.com/efoxTeam/flutter-ui/test/readme/qq-qrcode.png" width="200" />欢迎有兴趣的小伙伴参与进来，一同完善组件，同是也可以把相关问题通过issues方式与我们联系
[开发者如何参与完善控件](PR规范.md)
<p>QQ交流群</p>


## 环境
* 自行完成flutter环境配置
* 通过git clone本项目master分支代码，进入项目
* 切换flutter到master分支，步骤如下（若已切换可跳过）
1. flutter channel master // 选择master分支
2. flutter upgrade // 更新代码  
* 运行模拟器或真机
* flutter run运行程序

## app预览

![Alt 预览](readme/flutter_ui2.gif)
![Alt 预览](readme/flutter_ui3.gif)


## 目录
```
Flutter UI
  ├─assets      静态资源
  ├─docs      教程文件
  ├─locale      语言包
  ├─lib     dart执行代码
      ├─components
      ├─config  配置文件
      ├─controller
      ├─lang  多语言控制类
      ├─page  路由关联页面
      │  ├─component
      │  └─mine
      ├─router  路由
      ├─store 数据管理
      │  ├─models
      │  └─objects
      ├─utils 项目工具类
      └─widget  项目组件库
          ├─animate
          │  ├─animatedbuilder  【✔️ v1.0】
          │  ├─animatedcontainer
          │  ├─animatedcrossfade
          │  ├─animateddefaulttextstyle
          │  ├─animatedliststate
          │  ├─animatedmodalbarrier
          │  ├─animatedopacity
          │  ├─animatedphysicalmodel
          │  ├─animatedpositioned
          │  ├─animatedsize
          │  ├─animatedwidget
          │  ├─animatedwidgetbasestate
          │  ├─animationcontroller
          │  ├─decoratedboxtransition
          │  ├─fadetransition
          │  ├─hero
          │  ├─positionedtransition
          │  ├─rotationtransition
          │  ├─scaletransition
          │  ├─sizetransition
          │  └─slidetransition
          ├─bulletbox
          │  ├─alertdialog 【✔️ v1.0】
          │  ├─bottomsheet 【✔️ v1.0】
          │  ├─expansionPanel 【✔️ v1.0】
          │  ├─simpledialog 【✔️ v1.0】
          │  └─snackbar 【✔️ v1.0】
          ├─common
          │  ├─assetbundle
          │  ├─buttonbar
          │  ├─chip
          │  ├─container  【✔️ v1.0】
          │  ├─divider  【✔️ v1.0】
          │  ├─flatbutton 【✔️ v1.0】
          │  ├─icon
          │  ├─iconbutton
          │  ├─image
          │  ├─listtile
          │  ├─placeholder
          │  ├─raisedbutton
          │  ├─rawimage
          │  ├─stepper
          │  ├─text 【✔️ v1.0】
          │  └─tooltip
          ├─form
          │  ├─checkbox 【✔️ v1.0】
          │  ├─checkboxlisttile 【✔️ v1.0】
          │  ├─slider   【✔️ v1.0】
          │  ├─switch   【✔️ v1.0】
          │  ├─switchListTile   【✔️ v1.0】
          │  ├─daypicker  【✔️ v1.0】
          │  ├─radio    【✔️ v1.0】
          │  ├─radioListTile    【✔️ v1.0】
          │  ├─form
          │  ├─formfield
          │  ├─rawkeyboard
          │  ├─textfield    【✔️ v1.0】
          │  └─textinput
          ├─gestures
          │  ├─absorbpointer
          │  ├─dismissible
          │  ├─dragtarget
          │  ├─gesturedetector
          │  ├─ignorepointer
          │  └─longpressdraggable 【✔️ v1.0】
          ├─navigator
          │  ├─appbar
          │  ├─bottomnavigationbar
          │  ├─drawer
          │  ├─floatingactionbutton
          │  ├─materialapp
          │  ├─navigator
          │  ├─popupmenubutton
          │  ├─scaffold
          │  ├─tabbar
          │  ├─tabbarview
          │  └─widgetsapp
          ├─regular
          │  ├─align  【✔️ v1.0】
          │  ├─aspectratio  【✔️ v1.0】
          │  ├─center 【✔️ v1.0】
          │  ├─column 【✔️ v1.0】
          │  ├─constrainedbox 【✔️ v1.0】
          │  ├─container  【✔️ v1.0】
          │  ├─fittedbox  【✔️ v1.0】
          │  ├─flow 【✔️ v1.0】
          │  ├─layoutbuilder  【✔️ v1.0】
          │  ├─listbody 【✔️ v1.0】
          │  ├─listview 【✔️ v1.0】
          │  ├─padding  【✔️ v1.0】
          │  ├─row  【✔️ v1.0】
          │  ├─stack  【✔️ v1.0】
          │  ├─table  【✔️ v1.0】
          │  └─wrap 【✔️ v1.0】
          ├─scrollview
          │  ├─customscrollview 【✔️ v1.0】
          │  ├─gridview 【✔️ v1.0】
          │  ├─listview 【✔️ v1.0】
          │  ├─nestedscrollview 【✔️ v1.0】
          │  ├─scrollable 【✔️ v1.0】
          │  ├─scrollbar  【✔️ v1.0】
          │  ├─scrollcontroller 【✔️ v1.0】
          │  └─singlechildscrollview  【✔️ v1.0】
          └─vision
              ├─backdropfilter
              ├─clipoval
              ├─clippath
              ├─cliprect
              ├─custompaint
              ├─decoratedbox
              ├─fractionaltranslation
              ├─mediaquery
              ├─opacity
              ├─rotatedbox
              ├─theme
              └─transform
```

