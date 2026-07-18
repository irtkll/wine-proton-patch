# wine-proton-patch
wine-proton的补丁

## 修复Windows Steam 无法显示登录UI以及后续UI的问题
Windows Steam 的steamwebhelper.exe会因为在加载字体时崩溃，而无法渲染窗口
### 注：要让WINDOWS版steam运行起来，需在在境变量中添加 PROTON_DISABLE_LSTEAMCLIENT=1,否则依旧无法运行
