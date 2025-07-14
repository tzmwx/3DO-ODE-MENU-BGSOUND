# 3DO-ODE-MENU-BGSOUND

此套软件可修改3DO ODE光驱板软件的开机画面LOGOpic，游戏菜单背景图片MENUpic，背景音乐BGSOUND。

注意，可能有杀毒软件报警，请放心使用，没有病毒和木马！没有病毒和木马！没有病毒和木马！

3DOLOGOpic.EXE的功能是修改背景音乐

3DOMENUpic.EXE的功能是更改游戏菜单背景图片

3DOBGSOUND.EXE的功能是更改3DO ODE菜单软件BOOT.ISO内置背景音乐


文件需求：

1.在BGSOUND文件夹内已提供3DOBGSOUND.EXE，3DOMENUpic.EXE和3DOLOGOpic.EXE，还需要2个文件，一个是BOOT.ISO,一个是FFMPEG.EXE；

2.在3DO ODE的U盘或SD卡找到BOOT.ISO，建议使用最新的R5版本；

3.FFMPEG.EXE文件可在  https://www.gyan.dev/ffmpeg/builds/  下载，此站点有essentials和full版本，
均可以使用，解压缩后在BIN文件夹内。

（注：FFMPEG 7.0后，full版本不再支持Windows7和8，请下载essentials版本。）

4.运行前确保目录结构如下有5个文件
：
        3DOMLOGOpic.EXE
        
        3DOMENUpic.EXE

        3DOBGSOUND.EXE
        
        BOOT.ISO
        
        FFMPEG.EXE
        
        

5.音频文件基本兼容所有格式，不管源文件是什么格式或品质，均以16Bit 44.1Khz Stereo注入BOOT.ISO

6.图片文件基本兼容所有格式。需要注意游戏菜单背景图片最好使用亮度偏暗一点的图片，否则可能会看不清游戏列表字符，此软件已自动降低亮度20%，如需再次降低亮度，请自行提前处理，然后在再让软件注入BOOT.ISO

3个修改软件使用方法基本相同，以背景音乐3DOBGSOUND.EXE举例说明如何使用：

方法1：

1.打开2个文件夹窗口，一个是此5个文件的文件夹，一个音频文件夹；

2.鼠标左键持续按住音频文件不松手，然后拖到3DOBGSOUND.EXE上方松开鼠标左键；

3.屏幕可见黑白字符滚动的窗口，稍后提示“请按任意键继续”，此时你可以关闭窗口；

4.此时BOOT.ISO已被修改，把它拷贝到3DO的U盘或SD；

5.插入3DO ODE运行。




方法2：

1.用鼠标右击音频文件，选择“复制”

2.用鼠标右击3DOBGSOUND.EXE，选择“粘贴”

3.屏幕可见黑白字符滚动的窗口，稍后提示“请按任意键继续”，此时你可以关闭窗口；

4.此时BOOT.ISO已被修改，把它拷贝到3DO的U盘或SD；

5.插入3DO ODE运行。




By tzmwx

2025/07/12



感谢以下软件及作者：

1.3DO homebrew encryption   v0.6a        By Charles Doty

2.OperaTool     0.01a - By Cristina Ramos

3.3DO R.E.A.L. Multiplayer ISO tool. v0.1 By nikk 

4.BOOT.ISO    R5    By Fixel

5.FFMPEG
