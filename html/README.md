### HTML Tags:

1. head - It is the place where all the content that are not to shown in the forntend is present. like \<title\> , metadatas, etc...

2. body - It contins all the code that are to be shown to the user/ frontend html tags like \<h1\>, \<img\>, etc...

3. div - It takes the items and align then vertically every time.
   example:

```html
<div>
  <h1>hello</h1>
  <div>I am Shahbaz Hashmi</div>
</div>

<div>a web dev beginner</div>
```

4. span - it takes the items and align them horizontally every time.
   Example:

```html
<div>
  <h1>hello</h1>
  <div>I am Shahbaz Hashmi</div>
</div>

<div>a web dev beginner</div>
```

5. br - it is simply the brake line.
   writting way:

```html
<br />
```

4. h1 to h6 - These are the heading tags, where h1 is the biggest and h6 is smallest font size for the heading text.
   writting way:

```html
<h1>Hello World</h1>
```

5. b, i, u - "b" is for bold, "i" is for italic, and "u" is for underline
   writting way:

```html
<span
  ><b>hello there I am <i>looking for job</i> <u>hire me!</u></b></span
>
```

6. Comments -
   Writting way:

```html
<!-- Foirmating tags -->
```

7. List - we can put the list of items in porpely format over here.
   Example:

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ul>
```

- \<ul\> stands for **unordered list**
- \<ol\> stands for **ordered list**

8. Tables: To show any data in the tabular format.
Example:

```html
<table>
  <tr>
    <th>SI NO.</th>
    <th>Name</th>
    <th>Passing Year</th>
  </tr>
  <tr>
    <td>1</td>
    <td>St. James' School, Binnaguri</td>
    <td>2024</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Siliguri Institue Of Technology</td>
    <td>2028</td>
  </tr>
</table>
```
- \<tr\> stands for the **table row**
- \<th\> stands for the **table head**
- \<td\> stands for the **table data**

9. a - Thsi is a hyperlink tag, we can give url, email address, etc..
Example: 
```html
<a href="https://google.com" target="_blank">Search here!</a>
```

- herf: is the place you put the links.
- target: is the place you define the link should open in the same tab or new tab.
    - _self - Default. Opens the document in the same window/tab as it was clicked
    - _blank - Opens the document in a new window or tab
    - _parent - Opens the document in the parent frame
    - _top - Opens the document in the full body of the window
- email: ``` <a href="mailto:someone@example.com">Send email</a> ```

10. img - this tag is used for showing the images.
Example:
```html
<img src="./Shahbaz.png" width="100px" alt="This is Shahbaz Photo"/>
```
- src: is used for givimng the image path. the path can be local dir location or web link.
- alt: is used in seo for describing the image.
- width & height: these are the predefined attributes for img tag.