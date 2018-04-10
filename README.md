# 国产手机运行时权限适配 借用别人的项目
<h2 id="pro">混淆</h2>
1.如果你是使用 listener 可以不必混淆

2.如果你是使用 annotation ，如下：
>
	-dontwarn com.joker.api.**
	-keep class com.joker.api.** {*;}
	-keep interface com.joker.api.** { *; }
	-keep class **$$PermissionsProxy { *; }

<h2 id="help">help me</h2>