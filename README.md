## YIT-FAST-COMMENT-FOR-STU

ps:本篇教程参考[INFP-MoZhu/SDU-Quick-Comment: 给懒得点教学评估的uu一个快速水的方式](https://github.com/INFP-MoZhu/SDU-Quick-Comment)

感谢伟大的墨竹老师提供的思路

**教程**

1. 打开教学评价界面

2. 打开开发者模式f12

3. click控制台

4. 输入代码,回车

5. 手动将其中一条优秀改为良好

   > 本校系统不允许所有选项填同一选项orz

代码如下:

```
document.querySelector('input[name="pj0601id_1"][value="90F96EE04BDC49FDBEDF7B07AA1293B8"]').checked = true;  // 言行为人师表
document.querySelector('input[name="pj0601id_4"][value="B38D84D9E8B34064A211F1F61C53254B"]').checked = true;  // 遵守教学纪律
document.querySelector('input[name="pj0601id_3"][value="D3607377D52344228C0802CF29546423"]').checked = true;  // 有效管理课堂
document.querySelector('input[name="pj0601id_2"][value="E791CB20F5B34730AD4740ED71236505"]').checked = true;  // 教学内容熟练
document.querySelector('input[name="pj0601id_8"][value="B14321930F3A43E78CB21368F9821C97"]').checked = true;  // 理论联系实际
document.querySelector('input[name="pj0601id_5"][value="D24B90A631D54E0AB99CD18E675D9BA2"]').checked = true;  // 教学方法创新
document.querySelector('input[name="pj0601id_6"][value="1B70DB1D25A1451BBBCBD83618517A7C"]').checked = true;  // 注重师生互动
document.querySelector('input[name="pj0601id_7"][value="CB592DF600A640C295DC5A1D0EAAB8D2"]').checked = true;  // 教学作风严谨

```

![img](file:///D:\QQ_Tencent\Tencent Files\2450687812\nt_qq\nt_data\Pic\2025-01\Ori\ed67c8c18618c01a6a336e1312868e31.png)

**注意的问题**

js的代码主要根据name值和value值确定操作の地,如果你执行我给出的代码有问题,很可能是那么值和value值与你打开的页面无法匹配

**解决方法**

1. 同样打开评价页面
2. 点击元素
3. 选择对应的元素
4. 复制,并把它喂给gpt让gpt帮你替换

**如果你遇到了问题且并没有相关的知识去执行相应步骤,欢迎添加作者联系方式**

qq:2450687812

邮箱:2450687812@qq.com

网站:zheyuan.zhuzimiko.com(还在建设中)
