###  heading of all levels 
```
<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
<h3>Heading level 3</h3>
<h4>Heading level 4</h4>
<h5>Heading level 5</h5>
<h6>Heading level 6</h6>
```
####
<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
<h3>Heading level 3</h3>
<h4>Heading level 4</h4>
<h5>Heading level 5</h5>
<h6>Heading level 6</h6>
---
---

###  line break
```<br>```

---
---

### horizontal line tag  

```<hr size="3" noshade>```

 atributes :size and noshade  --> <br>
 size:Sets the height, in pixels, of the rule. --> <br>
 noshade :Sets the rule to have no shading. --> <br>

####

<hr size="3" noshade>
---
---

### html boilerplate 

```
<!DOCTYPE html>
<!-- html5 -->
<html lang="en" dir="ltr">

<head>
  <!--    contents and links  -->
  <meta charset="utf-8">
  <!--  meta tags are used for discrible content of the page ,authrer ,charset so on    -->
  <!--   charsert defines the set of char used in the web page 
  utf8 has  all the char even mojs and sopports all languages and symboles 
-->
  <title>hello</title>
  <!--     title of the page -->
</head>

<body>
  <!--     body contents the all the thing that we see on the website  -->
  <h1>Hello world !</h1>
</body>

</html>

<br>
<hr size="3" noshade>

```
---
---
### blod tag
```
<b>blod</b>
```
---
---
### strong tag
```
<strong>strong</strong>
```
####
<strong>strong</strong>


```
 <b> vs. <strong>
It is often confusing to new developers why there are so many ways to express the same 
thing on a rendered website. <b> and <strong> are perhaps one of the most common sources
of confusion, causing developers to ask "Should I use <b> or <strong>? Don't they both do the same thing?"

Not exactly. The <strong> element is for content that is of greater importance, while the <b> 
element is used to draw attention to text without indicating that it's more important.

It may help to realize that both are valid and semantic elements in HTML and that
it's a coincidence that they both have the same default styling (boldface) in most
browsers (although some older browsers actually underline <strong>). Each element 
is meant to be used in certain types of scenarios, and if you want to bold text for
decoration, you should instead actually use the CSS font-weight property.

The intended meaning or purpose of the enclosed text should be what determines which element you use. 
Communicating meaning is what semantics are all about. 
```

---
---
### italics tag
```
<i>italics</i>
```
 #### 
 <i>italics</i>

<!-- _____________________________________________________________________________ -->

<em>Emphasis</em>

```
 <i> vs. <em>
Some developers may be confused by how multiple elements seemingly produce similar
visual results. <em> and <i> are a common example, since they both italicize
text. What's the difference? Which should you use?
```
```
By default, the visual result is the same. However, the semantic meaning is different.
The <em> element represents stress emphasis of its contents, while the <i> element represents 
text that is set off from the normal prose, such a foreign word, fictional character thoughts,
or when the text refers to the definition of a word instead of representing its semantic meaning. 
(The title of a work, such as the name of a book or movie, should use <cite>.) -->
```
---
---
 ``` <em> vs. <strong> 
Adding to the confusion is the fact that while HTML 4 defined <strong> as indicating
a stronger emphasis, HTML 5 defines <strong> as representing "strong 
importance for its contents." This is an important distinction to make.

While <em> is used to change the meaning of a sentence as spoken emphasis does
("I love carrots" vs. "I love carrots"), <strong> is used to give portions of 
a sentence added importance (e.g., "Warning! This is very dangerous.") 
Both <strong> and <em> can be nested to increase the relative degree of importance 
or stress emphasis, respectively. 
```
---
---

### html lits 
#### un ordered list 
```
<h2>programing languages that I know :</h2>
<ul>
  <!-- un-ordered list -->
  <li>c++</li>
  <li>c programing</li>
  <li>java</li>
</ul>
```
#####
<ul>
  <!-- un-ordered list -->
  <li>c++</li>
  <li>c programing</li>
  <li>java</li>
</ul>

#### order lists
```
<h2> lang</h2>
<ol>
  <!-- ordered list -->
  <li>English</li>
  <li>kannada</li>
  <li>Hindi</li>
</ol>

```
#####

<h2> lang</h2>
<ol>
  <!-- ordered list -->
  <li>English</li>
  <li>kannada</li>
  <li>Hindi</li>
</ol>


---
---


### image tag
```
<img src="https://media-exp1.licdn.com/dms/image/C5603AQFYd4O7S6WLfQ/profile-displayphoto-shrink_400_400/0/1629387644470?e=1672272000&v=beta&t=8gpivCoBbEa4m2m3P5TzNZ0wLdOlvY-VpelolPQPNCY" width="200" alt="my linkdin profie">

```
<img src="https://media-exp1.licdn.com/dms/image/C5603AQFYd4O7S6WLfQ/profile-displayphoto-shrink_400_400/0/1629387644470?e=1672272000&v=beta&t=8gpivCoBbEa4m2m3P5TzNZ0wLdOlvY-VpelolPQPNCY" width="200" alt="my linkdin profie">


---
---

###  hiper links -->

```
<em>
  <br>
  <strong><a href="https://nie.ac.in/blog/department/cse-department/">Computer science </a></strong> <br>
  <a href="https://nie.ac.in/"> Nation intiute of engneering Mysore</a>
</em>
```
<!-- _____________________________________________________________________________ -->
<em>
  <br>
  <strong><a href="https://nie.ac.in/blog/department/cse-department/">Computer science </a></strong> <br>
  <a href="https://nie.ac.in/"> Nation intiute of engneering Mysore</a>
</em>

<!-- _____________________________________________________________________________ -->
### table example
```
<h1>My Education</h1>
   <table>
     <thead>
       <tr>
         <th> years</th>
         <th> School/collage</th>
         <tr>
     </thead>
     <tr>
       <td> 2006 to 2016 </td>
       <td> noble and N V eng school gulberga</td>
     </tr>
     <tr>
       <td>20017 to 2019 </td>
       <td> Shree guru pre univesity collage gulberga</td>
     </tr>
       <tr>
        <td>2020 to ----</td>
        <td>Nation intiute of engneering Mysore</td>
      </tr>
</table>
```
<h1>My Education</h1>
   <table>
     <thead>
       <tr>
         <th> years</th>
         <th> School/collage</th>
         <tr>
     </thead>
     <tr>
       <td> 2006 to 2016 </td>
       <td> noble and N V eng school gulberga</td>
     </tr>
     <tr>
       <td>20017 to 2019 </td>
       <td> Shree guru pre univesity collage gulberga</td>
     </tr>
       <tr>
        <td>2020 to ----</td>
        <td>Nation intiute of engneering Mysore</td>
      </tr>
</table>
---
