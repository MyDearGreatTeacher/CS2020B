# 網站伺服器XAMPP
```
C:\xampp2\htdocs\TF


http://127.0.0.1/tf/Ch14_5_4a.html

notepad++
```
```
https://github.com/MyDearGreatTeacher/CS4high/tree/master/web
```
# 參考書
```
跨裝置網頁設計 -- HTML5、CSS3、JavaScript、jQuery、Bootstrap, 4/e
陳惠貞
碁峰資訊
2018-11-26
ISBN:9864769502
ISBN-13:9789864769506
```
```
PHP 7 & MySQL 網站開發 -- 超威範例集, 3/e
陳惠貞/陳俊榮
碁峰資訊
ISBN:9865024187
ISBN-13:978986502418
```
```
最潮 HTML5 + CSS3 網頁版型設計 Standard Layout‧Grid Layout‧Single Page Layout
吉田真麻 著、李保宜、楊瑩瑩譯
旗標科技
ISBN:9863123730
ISBN-13:9789863123736
```
## tf_js_1.html 原始程式
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"/>
<title>Ch14_4_1.html</title>
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@latest"></script>
</head>
<body>
<script>
const x = tf.scalar(10.5);
document.write("張量x值: " + x + "<br/>");
document.write("等級: " + x.rank + "<br/>");
document.write("形狀: [" + x.shape + "]<br/>");
document.write("型態: " + x.dtype + "<br/>");
document.write("----------------------------------------<br/>");
const y = tf.scalar(10, "int32");
document.write("張量y值: " + y + "<br/>");
document.write("型態: " + y.dtype + "<br/>");
</script>
</body>
</html>
```
## 程式架構
```
<!DOCTYPE html>

<html>

<head>
<meta charset="utf-8"/>
<title>Ch14_4_1.html</title>
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@latest"></script>
</head>


<body>


<script>
把程式放在這裡......
</script>

</body>
</html>
```
```
const x = tf.scalar(10.5);
document.write("張量x值: " + x + "<br/>");
document.write("等級: " + x.rank + "<br/>");
document.write("形狀: [" + x.shape + "]<br/>");
document.write("型態: " + x.dtype + "<br/>");
document.write("----------------------------------------<br/>");
const y = tf.scalar(10, "int32");
document.write("張量y值: " + y + "<br/>");
document.write("型態: " + y.dtype + "<br/>");
```
