# markdown note  
## line breaks
two spaces and return
## strong and emphasizes粗体和斜体
两个＊是粗体，一个＊是斜体  
**strong**:`**strong** or _strong_`
*emphasize*:`*emphasize* or _emphasize_`
## headers标题
  	# header1  
  	...  
  	###### header6  
## lists
* lists must be preceded by a blank line or block element  
* 无序list用* or - 开始
* 有序list用数字加.加空格开始`1. `,并且他的顺序和数字本身的大小没关系  
* 使用缩进indent可以嵌套list  
## links and emails
`inline的写法：link或者email和url写在同一行`
<ll917@uowmail.edu.au>:`<emails>`  
<https://www.github.com/unclepis>:`<url>`  
[unclepis](htttps://www.github.com/unclepis "pis_github"):`link text`  
  
`reference style的写法：使用id把email或者url引用进来，写在文件别的地方`  
`用id代替行内冗长的url，然后在文档其他位置统一声明urls`
`[a link][arbitrary_id]`  
`[arbitrary_id]:urls`  
[a link][github]  
[github]:https://www.githhub.com/unclepis "pis_github"
    
`不想单独定义id,想要使用link text本身作为arbitrary_id` 
`[click][]`  
`[click]:https://www.github.com/unclepis "pis_github"`  
[click][]  
[click]:https://www.github.com/unclepis "pis_github"

`通常的用法就是在inline中使用id代替url，在末位统一定义url`  
## images
`inline的写法：![图片替换文本](path/url)`
`![alt image text](path/or/url/to.type "title")`  
![logo](web/project_demo/images/uncle_pis.ico "logo")  
 
`reference style的写法：和url一样，图片也可以把path或者url单独定义`  
`![图片替换文本][arbitrary_id]`  
`[arbitrary_id]:path/url "title"`  
![uncle_pis][logo]  
[logo]:web/project_demo/images/uncle_pis.ico "logo"  

 
## block quote引用  
在我们写作的时候，经常需要引用别人的文字，这个时候引用这种格式就很有必要。你只需要在引用蚊子前面加>
`angle brackets尖括号are used for block quotes`
`并不是每一行都需要>开始，只要段落中没有空的行`  
> block quotes  
>> blok quotes can be nested  
>>> such multiple levels in block quotes  
>
> most markdown syntaxes work inside block quotes
> 
> * list  
> * [Lee](https:www.github.com/unclepis)  
> * ![image](web/project_demo/images/uncle_pis.ico)  
> * Etc.  
 
## inline code代码引用
需要引用代码时，如果引用的语句只有一段，不分行，可以用`将语句包起来.  
如果需要引用的代码时多行，可以将```置于代码的首行和末行.  
`backticks and double backticks`  
`inline code`  
``如果inline code里面本身就有backtick`那么就需要使用double backticks``  
`` `inline block` ``

##block code块级代码
`if you indent at least four spaces or one tab,it'll display a code block.`  

	tab key
    at least four spaces
##horizontal rules水平分割线
`if you type three arterisks or three dashes on a line,it will display a horizental rule`  
***
---
## table
`冒号在哪边就是对齐方式`  

First Header | Second Header | Third Header
:------------| :------------:|-----------:
content cell | content cell  |content cell
content cell | content cell  |content cell
content cell | content cell  |content cell






	
	
	

 
