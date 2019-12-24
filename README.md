# Number2Words

## 1、项目作用：
金额的数字转换为大写

## 2、输出结果对比： 
https://spanishnumbers.guide/numbers-in-spanish.html

## 3、输出结果示例：

```
0:cero
1:uno
2:dos
3:tres
4:cuatro
5:cinco
6:seis
7:siete
8:ocho
9:nueve
10:diez
11:once
12:doce
13:trece
14:catorce
15:quince
16:dieciséis
17:diecisiete
18:dieciocho
19:diecinueve
20:veinte
21:veintiuno
22:veintidós
23:veintitrés
24:veinticuatro
25:veinticinco
26:veintiséis
27:veintisiete
28:veintiocho
29:veintinueve
30:treinta
40:cuarenta
50:cincuenta
60:sesenta
70:setenta
80:ochenta
90:noventa
100:cien
101:ciento uno
182:ciento ochenta y dos
200:doscientos
300:trescientos
400:cuatrocientos
500:quinientos
600:seiscientos
700:setecientos
800:ochocientos
900:novecientos
1000:mil
1001:mil uno
1010:mil diez
1100:mil cien
10000:diez mil
100000:cien mil
200000:doscientos mil
1000000:un millón
2000000:dos millónes
```
## 4.代码修改位置

1. 原生的代码里，跟上面网站的结果不一致，1000以上的，多了一个un。

2. 修改 Spanish.POWER_NAMES ，将 un mil ->  mil 即可
