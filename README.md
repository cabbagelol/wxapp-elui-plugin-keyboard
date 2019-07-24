虚拟键盘插件,无法被第三方获取到输入信息, 可控制性的内容输入, 无法被通过用户触摸位置识别密码(如果被录屏无解 滑稽)，让用户觉得安全(重点)。

    Elui 0.0.6+
    Elui keyboard 0.0.1 
    依赖 Elui:el-colum

![](www/images/01.png)

**使用**

先导入Elui库（https://github.com/cabbagelol/wxapp-el-ui），将“_keyboard”文件夹放入Elui的“component”文件夹中。

    "el-keyboard": "./component/_keyboard/keyboard"
    
    <el-keyboard class='keyboard' title='安全键盘' bindkeyboard=''/>
    
**事件**

使用前在声明ready声明周期获取组件事件:

    this.keyboard = this.selectComponent(".keyboard");

    this.keyboard.show(); 显示，每次触发会重新排列键盘
    this.keyboard.hide(); 隐藏
    

**版本**

0.0.1: 
 初始化项目