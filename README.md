# webuart

Online serial port tool usage guide
WebUART.com
1. Create a new terminal
1. Insert the USB to UART module into the PC
 
2. Open "Device Manager" and ensure that the COM port recognizes the device.
 
3. Open the WebUART.com homepage and click
4. Configure "Terminal Name", which is the name displayed in the interface tab bar, used to distinguish different terminal windows.
Configure the hardware properties of "Serial Port Rate", "Data Bits", "Stop Bits", "Verification Mode", and "Hardware Flow Control"
Configure the "screen cache" size, that is, the maximum number of characters displayed on the screen interface
Configure the "Save Log" switch, that is, whether to record communication content to the browser cache
Configure "Device Type". When connecting to a physical device, the device type should be selected as "Native Device"
 
5. Click "OK" and then authorize the browser to use the serial device
 
6. After authorization, you can use the serial device online
 
2. Sharing terminal
1. First connect the local serial device
 
2. Click to share the terminal console
 
3. Connect to terminals shared by others
method one:
1. Click to create a new terminal and select the remote device in the "Device Type" column.
 
2. Enter the "Device Number" and "Device Password" provided by the sharer, and click OK
 
 
Method two:
Open the "sharing link" given by the device sharer through the browser, and you can use it directly after opening it.
 
4. Stop sharing
1. Click to view device sharing status
 
2. Click "Stop" to confirm the stop.
 
 
5. Copy screen
Click to copy all content on the screen
 
6. Clear the screen
Click to clear all characters on the entire screen
7. HEX (hexadecimal) mode
1. Click to enter HEX (hexadecimal) mode
 
2. Click to exit HEX (hexadecimal) mode
8. Recording logs
1. Click to start recording logs to the browser cache.
 
2. Click to stop logging (note that the browser cache will be cleared after stopping, and the previously recorded content will no longer exist)
9. Save logs
Double-click the number behind the "Save Log: true" character at the bottom of the screen to download the log.
 
 
10. Automatic sending
1. Click to enter the automatic sending interface
 
2. "Sending method" can choose "text mode" and "script mode": "text mode" refers to sending ordinary characters, while "script mode" refers to controlling the sending behavior through JavaScript scripts.
3. "Text format" can choose "ASCII" and "HEX", "ASCII" corresponds to the string, and "HEX" corresponds to the HEX (hexadecimal) format of the string (note that in HEX mode, each Byte needs to be separated by a space "" Interval, in the form of "AA BB CC DD")
4. After the "Line by Line Send" switch is turned on, you can set the delay time after each line is sent, that is, the line interval time.
5. After the "Loop Send" switch is turned on, the content in the text box will continue to be sent; and the loop interval can be set.
6. After the "Turn on carriage return" and "Turn on line feed" switches are turned on, the corresponding characters will be added at the end each time a string is sent.
Text mode:
1. Fill in the characters you want to send in the text box
 
2. Turn on the "Line by Line Send Function", turn on "Add Carriage Return" and "Add Line Feed", and then confirm
 
 
Script mode:
1. Switch "Sending Method" to "Script Method" and click "Example" to view the reference code.
 
2. Modify the reference code and send Hello WebUART.com

# webuart
在线串口工具使用指导
WebUART.com
一、	新建终端
1、	将USB转UART模块插入PC
 
2、	打开“设备管理器”，确保COM端口识别到设备
 
3、	打开WebUART.com主页，点击 
4、	配置” 终端名称”，即界面标签栏显示的名字，用于区分不同的终端窗口
配置”串口速率”、 ”数据位”、 ”停止位”、 ”校验模式”、”硬件流控”硬件属性
配置“屏幕缓存”大小，即屏幕界面最多显示的字符个数
配置“保存日志”开关，即是否记录通信内容到浏览器缓存
配置“设备类型”，连接物理设备时候，设备类型应该选择为“本机设备”
 
5、	点击“确定”，然后授权浏览器使用串口设备
 
6、	授权后即可在线使用串口设备
 
二、	分享终端
1、	先连接本地串口设备
 
2、	点击 ，分享终端控制台
 
三、	连接他人分享的终端
方式一：
1、	点击 新建终端，“设备类型”一栏选择远程设备
 
2、	输入分享者提供的“设备编号”和“设备口令”，点击确定
 
 
方式二：
通过浏览器打开设备分享者给与的”分享链接”，打开后直接可以使用
 
四、	停止分享
1、	点击 ，查看设备分享情况
 
2、	点击“停止”，确定停止
 
 
五、	拷贝屏幕
点击 ，即可拷贝屏幕内所有内容
 
六、	清空屏幕
点击 ，将会清空整个屏幕所有字符
七、	HEX(16进制)模式
1、	点击 ，进入HEX(16进制)模式
 
2、	点击 ，退出HEX(16进制)模式
八、	记录日志
1、	点击 ，开始记录日志到浏览器缓存
 
2、	点击 ，停止记录日志（注意停止后将清空浏览器缓存、之前记录的内容不复存在）
九、	保存日志
双击屏幕下方“保存日志: true ”字符后面的数字，即可下载日志
 
 
十、	自动发送
1、	点击 ，进入自动发送界面
 
2、	“发送方式”可选“文本方式”和“脚本方式”：“文本方式”指的是发送普通字符，而“脚本方式”指的是通过JavaScript脚本控制发送行为
3、	“文本格式”可选”ASCII”和”HEX”， ”ASCII”对应字符串，“HEX”对应字符串的HEX(16进制)格式（注意HEX模式下每个Byte需要以空格” ”间隔，形如”AA BB CC DD”）
4、	“逐行发送”开关打开后，可以设置每行发送后的延迟时间 即行间隔时间
5、	“循环发送”开关打开后，会持续发送文本框里面的内容；并且可以设置循环间隔
6、	“打开回车”和“打开换行”开关打开后，会在每次发送字符串时在结尾添加对应字符
文本方式：
1、	在文本框内部填入想发送的字符
 
2、	打开“逐行发送功能”，打开“添加回车”和“添加换行”，然后确定
 
 
脚本方式：
1、	将“发送方式”切换为“脚本方式”，点击“示例”查看参考代码
 
2、	修改参考代码，发送Hello WebUART.com
 

