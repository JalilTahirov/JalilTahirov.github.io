## HTML 
#### Tesvir
> Hipertext webde sehifelerin bir biri ile elagesini gosterir

> HTML ile siz yalniz sehifenin formasini teyin edirsiz.
 

#### NUMUNE
 * Create Index HTML document and add following content: 
```
<!DOCTYPE html>
<html>

   <head>
      <title>This is document title</title>
   </head>
	
   <body>
      <h1>This is a heading</h1>
      <p>Document content goes here.....</p>
   </body>
	
</html>

```
-----------------------------------
* Yaratdiginiz fayli prauzerde achin
 
## HTML Tags

#### Tesvir
>HTMLde taglardan istifade olunur ki senedin formatin teyin etsin

* Documentin tipini və html versiyasin təyin edir. 
``` <!DOCTYPE...> ``` 


* This tag encloses the complete HTML document and mainly comprises of document header which is represented by ```<head>...</head>``` and document body which is represented by ```<body>...</body>``` tags.
```<html>```


* The ```<head>``` tag represents the document's header which can keep other HTML tags like ```<title>```, ```<link>``` etc.

* 	```<title>```
* The``` <title>``` tag is used inside the <head> tag to mention the document title.

* The ```<body>``` tag represents the document's body which keeps other HTML tags like ```<h1>```, ```<div>```, ```<p>``` etc.	

* the	```<h1>```  tag represents the heading.

* the 	```<p>``` tag represents a paragraph.



#### Heading Tags



```

<!DOCTYPE html>
<html>

   <head>
      <title>Heading Example</title>
   </head>
	
   <body>
      <h1>This is heading 1</h1>
      <h2>This is heading 2</h2>
      <h3>This is heading 3</h3>
      <h4>This is heading 4</h4>
      <h5>This is heading 5</h5>
      <h6>This is heading 6</h6>
   </body>
	
</html>

```
#### Paragraph Tag

The ```<p>``` tag offers a way to structure your text into different paragraphs. Each paragraph of text should go in between an opening ```<p>``` and a closing ```</p>``` tag as shown below in the example

```

<!DOCTYPE html>
<html>

   <head>
      <title>Paragraph Example</title>
   </head>
	
   <body>
      <p>Here is a first paragraph of text.</p>
      <p>Here is a second paragraph of text.</p>
      <p>Here is a third paragraph of text.</p>
   </body>
	
</html>

```

#### Line Break Tag

```

<!DOCTYPE html>
<html>

   <head>
      <title>Line Break  Example</title>
   </head>
	
   <body>
      <p>Hello<br />
         You delivered your assignment ontime.<br />
         Thanks<br />
         Jalil</p>
   </body>
	
</html>

```

#### Horizontal Lines

```
<!DOCTYPE html>
<html>

   <head>
      <title>Horizontal Line Example</title>
   </head>
	
   <body>
      <p>This is paragraph one and should be on top</p>
      <hr />
      <p>This is paragraph two and should be at bottom</p>
   </body>
	
</html>

```

#### HTML Tables

>The HTML tables are created using the ```<table>``` tag in which the ```<tr>``` tag is used >to create table rows and ```<td>``` tag is used to create data cells. The elements >under <td> are regular and left aligned by default


```
<!DOCTYPE html>
<html>

   <head>
      <title>HTML Tables</title>
   </head>
	
   <body>
      <table border = "1">
         <tr>
            <td>Row 1, Column 1</td>
            <td>Row 1, Column 2</td>
         </tr>
         
         <tr>
            <td>Row 2, Column 1</td>
            <td>Row 2, Column 2</td>
         </tr>
      </table>
      
   </body>
</html>

```

# CSS

#### Tesvir
> Cascading Style Sheets is a simple design language intended to simplify the process of making web pages presentable.  

> CSS handles the look and feel part of a web page. Using CSS, you can control the color of the text, the style of fonts, the spacing between paragraphs, how columns are sized and laid out, what background images or colors are used, layout designs,variations in display for different devices and screen sizes as well as a variety of other effects.



```
h1 {
   color: #36CFFF; 
}
```


#### Class Selector

```

.black {
   color: #000000; 
}

```
#### Grouping Selectors
```
h1, h2, h3 {
   color: #36C;
   font-weight: normal;
   letter-spacing: .4em;
   margin-bottom: 1em;
   text-transform: lowercase;
}

```

#### Embeded CSS

```

<!DOCTYPE html>
<html>
   <head>
      <style type = "text/css" media = "all">
         body {
            background-color: linen;
         }
         h1 {
            color: maroon;
            margin-left: 40px;
         }
      </style>
   </head>   
   <body>
      <h1>This is a heading</h1>
      <p>This is a paragraph.</p>
   </body>
</html>

```



























