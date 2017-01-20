## how to solve the problem 'no CPU/ABI system image for target'
### 1.点击桌面上的【计算机】，然后点击弹出界面上方的【系统属性】，接着在【系统】面板中左键点选右下方的【更改设置】
### 2.在弹出的【系统属性】面板，在该面板中点击上方的【高级】，然后点击该界面下方的【环境变量】
### 3.在【XX用户变量】下方添加环境变量【ANDROID_SDK_HOME】,然后将变量值Android sdk的路径填好就可以了。
### 4.然后打开Android SDK Manager，点击创建安卓模拟器，看看是否成功
***如果没有成功，可以试试下面的方法***
### 5.打开Android SDK Manager，下载ARM EABI v7a System Image、Intel X86 Atom System Image 和 MIPS System Image 这三个文件（下载上述三个
文件时要先点击界面上方的【Tools】，然后选择【Option】，在Option中设置连接外网才能进行下载），然后点击创建安卓模拟器，看看是否成功。over~
