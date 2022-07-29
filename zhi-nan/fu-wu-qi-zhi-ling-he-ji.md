---
description: 一些常用指令
---

# ☮ 服务器指令合集

### **常用指令**

{% hint style="success" %}
/warp dp  前往地皮世界

/warp zy  前往资源世界

/warp sg1 前往刷怪点

/spawn     回到主城



/sethome 设置家

/delhome 删除家



/tpa \<ID> 传送到\<ID>玩家处



/tpaccept 同意被传送

/tpacancle拒绝被传送



/tpr            随机传送

/cd             打开服务器菜单
{% endhint %}

### 地皮专用指令

{% hint style="success" %}
/plot trust <mark style="color:green;">\<ID></mark>       给某人<mark style="color:red;">永久全部权限</mark>

/plot add <mark style="color:green;">\<ID></mark>         给某人<mark style="color:green;">临时的全部权限</mark>----<mark style="color:green;">地皮主人下线后，权限直接消失</mark>

/plot remove <mark style="color:green;">\<ID></mark>   移除<mark style="color:green;">某人单次建筑权限</mark>

/plot visit <mark style="color:green;">\<ID></mark>         去某人<mark style="color:green;">地皮参观</mark>，<mark style="color:green;">无法传送到禁足的地皮</mark>



/plot auto                 <mark style="color:purple;">随机认领一个地皮</mark>

/plot claim                 <mark style="color:purple;">认领脚下的地皮</mark>



/plot deny <mark style="color:green;">\<ID></mark>       <mark style="color:red;">拉黑\<ID>从你地皮，填写 “/plot deny \* ” 则拉黑所有人</mark>

/plot undeny <mark style="color:green;">\<ID></mark>   <mark style="color:red;">解除拉黑\<ID>，填写 “/plot undeny \* ” 则解除拉黑所有人</mark>

/plot h                        <mark style="color:green;">返回地皮，也可使用 "/p h" 快捷指令</mark>
{% endhint %}

### 领地专用指令

{% hint style="success" %}
先用一块木头锄头左键 "对角" 敲击一方块设置点A，右键敲击一方块设置点B

/res select size               <mark style="color:blue;">查看所选区域的大小</mark>

/res create <mark style="color:green;"><领地名></mark>      创建一个领地<mark style="color:green;">(领地名字必须英文)</mark>

/res remove <mark style="color:green;"><领地名></mark>    <mark style="color:red;">移除领地(不会返还金钱,慎重)</mark>

/res set <mark style="color:green;"><领地名></mark>            设置领地权限<mark style="color:red;">(无特殊要求的情况下，无需设置)</mark>



以下是给予玩家领地全部权限指令:&#x20;

/res pset <mark style="color:green;"><领地名> <玩家名称></mark> trusted true ---- 表示<mark style="color:green;">添加</mark>一个玩家拥有领地的全部权限

/res pset <mark style="color:green;"><领地名> <玩家名称></mark> trusted false ---- 表示<mark style="color:red;">撤销</mark>一个玩家拥有领地的全部权限
{% endhint %}

### 设置领地进出提示

{% hint style="success" %}
/res message <领地名> enter <mark style="color:green;"><提示内容></mark>     ----  设置进入领地时所提示的文字

/res message <领地名> leave <mark style="color:green;"><提示内容></mark>     ----  设置离开领地时所提示的文字

<领地名>处不填，则默认为当前所处领地;



<mark style="color:purple;">特殊设置, 在提示信息中可以添加以下文字可产生特殊效果：</mark>

<mark style="color:purple;">%player - 在提示信息中显示进出领地的玩家名</mark>

<mark style="color:purple;">%owner - 在提示信息中显示领地主人</mark>

<mark style="color:purple;">%residence - 在提示信息中显示该领地名称</mark>
{% endhint %}
