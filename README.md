# PL
ChatGPT 學習/使用歷程

姓名:Jerry Wu


# Markdown 撰寫教學

> Author: Chris  
> Date: 2017-02-17  

> 表格生成器：[Markdown Tables Generator](http://www.tablesgenerator.com/markdown_tables)  

> 線上MarkDown編輯器
>> [Dillinger](http://dillinger.io/)  
>> [StackEdit](kedit.io)  
>> [Markdown Editor](https://jbt.github.io/markdown-editor/)

## 一、常用功能

### Markdown語法：
```
斜體：在兩邊加上 *星號* 或是 _底線_

粗體：在兩邊加上 **兩個星號** 或是 __兩個底線__

也可以用 **星號 與 _底線_**

刪除線：在兩邊加上 ~~兩個波浪~~

引言(註解)：

> 換行：需在最後面+`兩個空白鍵`··  
> 先以··表示空白
```
### 顯示結果：

斜體：在兩邊加上 *星號* 或是 _底線_

粗體：在兩邊加上 **兩個星號** 或是 __兩個底線__

也可以用 **星號 與 _底線_**

刪除線：在兩邊加上 ~~兩個波浪~~

引用文字(註解)：

> 換行：需在最後面+`兩個空白鍵`··  
> 先以··表示空白

## 二、標題

### Markdown語法：
```
Markdown 提供了六種規格的，分別對應 Html 標籤中的`<h1> ~ <h6>`

# H1
## H2
### H3
#### H4
##### H5
###### H6
```
### 顯示結果：

# H1
## H2
### H3
#### H4
##### H5
###### H6

## 三、列表

### Markdown語法：
```
有序列表直接打 `數字`+ `.` + `空白鍵`就可以了

1. 有序列表1 
2. 有序列表2
	1. 子有序列表1
	2. 子有序列表2

* 無序列表
	* 子無序列表
	* 子無序列表
	
		要在列表項目下加入段落，只要`+Tab`就好了。 
		> * 無序列表可以使用星號
		> - 或減號
		> + 或加號
```
### 顯示結果：

有序列表直接打 `數字`+ `.` + `空白鍵`就可以了

1. 有序列表1 
2. 有序列表2
	1. 子有序列表1
	2. 子有序列表2

* 無序列表
	* 子無序列表
	* 子無序列表
	
		要在列表項目下加入段落，只要`+Tab`就好了。 
		> * 無序列表可以使用星號
		> - 或減號
		> + 或加號

## 四、連結

### Markdown語法：
```
* 連結兩邊加上`<` `>`就會產生超連結

	<http://dillinger.io/>  
	
* 名稱兩邊加上`[` `]`然後再連結兩邊加上`(` `)`就可以將連結替換成文字連結

	[Dillinger](http://dillinger.io/ "link")
	
* 將`[` `]`前+`!`，則可以產生圖片 (把滑鼠指向圖片可以看到註解）

	![圖片參考名稱](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png "Logo")
```
### 顯示結果：

* 連結兩邊加上`<` `>`就會產生超連結

	<http://dillinger.io/>  
	
* 名稱兩邊加上`[` `]`然後再連結兩邊加上`(` `)`就可以將連結替換成文字連結

	[Dillinger](http://dillinger.io/ "link")
	
* 將`[` `]`前+`!`，則可以產生圖片 (把滑鼠指向圖片可以看到註解）

	![圖片參考名稱](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png "Logo")

## 五、程式碼與語法高亮


```
行內的 `程式碼` 用 `反引號` 包起來
區塊的 `程式碼` 用 ```三個反引號```包起來
記得要加上語言名稱
```

### Markdown語法：

	```javascript
	var s = "JavaScript 語法高亮";
	alert(s);
	```
 
	```php
	$s = "PHP 語法高亮";
	echo $s;
	```

### 顯示結果：

```javascript
var s = "JavaScript 語法高亮";
alert(s);
```

```php
$s = "PHP 語法高亮";
echo $s;
```

## 六、表格

### Markdown語法：
```
每個標頭元件都要用至少三個`破折號`+`直線`分隔開來，預設為置左。  
`冒號`可以用來標示欄位的對齊方式。

| 表頭1 | 表頭2 | 表頭3 |
|-------|:-----:|------:|
| 左1   |  中1  |   右1 |
| 左2   |  中2  |   右2 |
| 左3   |  中3  |   右3 |

當然，也可以在表格內加入樣式

|  功能  |    效果    | Markdown語法 |
|:------:|:----------:|:------------:|
|  粗體  |  **粗體**  |  `**粗體**`  |
|  斜體  |   *斜體*   |   `*斜體*`   |
| 刪除線 | ~~刪除線~~ | `~~刪除線~~` |

```
### 顯示結果：

每個標頭元件都要用至少三個`破折號`+`直線`分隔開來，預設為置左。  
`冒號`可以用來標示欄位的對齊方式。

| 表頭1 | 表頭2 | 表頭3 |
|-------|:-----:|------:|
| 左1   |  中1  |   右1 |
| 左2   |  中2  |   右2 |
| 左3   |  中3  |   右3 |

當然，也可以在表格內加入樣式

|  功能  |    效果    | Markdown語法 |
|:------:|:----------:|:------------:|
|  粗體  |  **粗體**  |  `**粗體**`  |
|  斜體  |   *斜體*   |   `*斜體*`   |
| 刪除線 | ~~刪除線~~ | `~~刪除線~~` |
