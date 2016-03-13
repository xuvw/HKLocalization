###有关App国际化：

##1 App名称国际化：
#生成InfoPlist.strings-->添加：‘"CFBundleDisplayName" = "中文名字";’
  ***只支持一种语言直接在Info.plist中添加:
  {
    <key>CFBundleDisplayName</key>
    <string>App名字</string>
  }

##2 App中文字内容国际化：
#生成：Localizable.strings-->添加对应内容，例如：
  "alertTitle" = "标题";

##3 其他内容国际化--后续补上

##4 系统控件本地化：
#target-->info-->添加key value对：
 ｛Localization native development region：china｝

  