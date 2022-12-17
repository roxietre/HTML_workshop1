
## Step 1: learn the basique Tags

[Tags](https://html.com/tags/) are the core of HTML. They represent a single element in a web page, like a `text` box, a `button`, a `div` etc. All combined together, they create a fully working web page.

You will learn how to use the [text](https://html.com/tags/heading/) one right now in the first step

```html
<h1>This is a title h1</h1>
    <h2>This is a title h2</h2>
    <h3>This is a title h3</h3>
    <h4>This is a title h4</h4>
    <p>
        <b>in bold</b>
        then in 
        <i>italics</i>
    </p>
```

To look at your page its easy just copy the path of your file in your web browser and done

<details>
    <summary>✔️ Result preview</summary>
	<title>Coding Club</title>
    <h1>This is a title h1</h1>
    <h2>This is a title h2</h2>
    <h3>This is a title h3</h3>
    <h4>This is a title h4</h4>
    <p>
        <b>in bold</b>
        then in 
        <i>italics</i>
    </p>
</details>

<br/>
 
## Step 2: more complexe Tags

Now lets see some more specifique Tags first lets add some colors and image.

to add some color in our text 2 solution [<font>](https://www.w3schools.com/tags/tag_font.asp) but its a old solution now a day wee use css and [style](https://www.w3schools.com/tags/tag_font.asp)
```html
<p>A word in <font color="#1E90FF">blue</font></p>
<p>A word in <p style="color:blue">blue</p></p>
```

to add image in our html page wee gonna use [<img>](https://www.w3schools.com/tags/tag_img.asp)
```html
<img src="./marmotte.png" alt="Groundhog image" />
```

<details>
    <p>A word in <font color="#1E90FF">blue</font></p>
    <img src="https://user-images.githubusercontent.com/49811529/182241478-40f5e380-8de1-4062-96c3-1acde999ad90.png" alt="backround image"/>
</details>

wee can also add a link to a other page or even a list.

to add a link in our text or other tags wee use [href=](https://www.w3schools.com/tags/att_a_href.asp)

for a list wee use a [<li>](https://www.w3schools.com/tags/tag_li.asp)

<details>
    <p>This is a <a href="https://google.com">link to google</a>.</p>
    <ul>
        <li>First element of the list</li>
        <li>Second element of the list</li>
    </ul>
</details>

<br/>

## Step 3: input and table

lets start with [<table>](https://www.w3schools.com/tags/tag_table.asp) that consists of one [<table>](https://www.w3schools.com/tags/tag_table.asp) and one or more [<tr>](https://www.w3schools.com/tags/tag_tr.asp), [<th>](https://www.w3schools.com/tags/tag_th.asp), and [<td>](https://www.w3schools.com/tags/tag_td.asp) elements.
The [<tr>](https://www.w3schools.com/tags/tag_tr.asp) element defines a table row, the [<th>](https://www.w3schools.com/tags/tag_th.asp) element defines a table header, and the <td> element defines a table cell.

And now [<input>](https://www.w3schools.com/tags/tag_input.asp) 

<details>
    <table>
    <caption>Un titre</caption>
    <tr>
        <th>Important 1</th>
        <td>Ici, il y</td>
        <td>a du texte</td>
    </tr>
    <tr>
        <th>Important 2</th>
        <td>Ici, aussi</td>
        <td rowspan="2">Fusion !</td>
    </tr>
    <tr>
        <th>Important 3</th>
        <td>Ici, pareil</td>
    </tr>
    <tr>
        <td colspan="3">Cette ligne fait toute la longueur</td>
    </tr>
</table>
<p> Please specify the date : <input type= "date"></p>
<p> Enter your username : <input type= "text"></p>
<button type= “button”> Click me ! </button>
</details>

<br/>

## Bonus

Congratulations, you know how to use tags in htlm now its time for full personalisation of your page, here are some examples:

- You can add sond
- You can do css and not using style=
- you can make a image link to a other page
- you can look for new tags to add 


<br/><br/>
## Authors
| [<img src="https://github.com/roxietre.png?size=85" width=85><br><sub>roxietre</sub>] |