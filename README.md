# actions_build_ErfanGSIs  
原作者：Github@together08

奶牛快传脚本上传部分：GitHub@Mikubill

整合（其实就是复制黏贴）：Github@bluboy-official


## 一个基于Github Actions制作的自动跑ErfanGSI的脚本。 
### 步骤如下： 
- 首先，fork这个仓库。 
- 接着，编辑build_ErfanGSIs.yml文件，把其中的ROM_URL改成你要做gsi的底包（注意直链）；还有ROM_NAME改成你的ROM名称。 
- 然后，按Star小星星就可以开始了！ 
- 最后，在Upload GSI里展开，看Download Link链接，访问即可下载。 

### 注意：由于上传artifacts的时候测试会卡BUG，于是决定改成上传到日本的BitSend（bitsend.jp）需要Fq。

bluboy：事实上好像bitsend时不时抽风，fq也未必有用，所以我改用了Mikubill佬的奶牛快传脚本来替换这一步，目测可行

## 附：ErfanGSI支持的ROM ##
> ROM_NAME里填一摸一样的，下的ROM也要一样；Generic是（类）原生的意思
### 9 Pie： ### 
> ColorOS	
Flyme
Generic
MIUI	
Moto	
Nubia	
OneUI	
OxygenOS	
Pixel	
Xperia	
ZUI	
ZenUI
### 10 Q： ###
> Generic
MIUI	
OxygenOS
Pixel
### 11 R： ##
> Generic	
Pixel
