---
description: >-
  This page contains an overview of aspects of HTML including definitions, names
  of attributes,  keyboard shortcuts, and examples.
---

# HTML

### Defining HTML

HTML \(Hypertext Markup Language\) is used to structure the content within a website. This is useful when creating websites because it not only makes it possible to display content such as text, images, videos, links, and so on, but it also helps keep everything organized and sectioned off. 

### Briefly Defining CSS\*

CSS \(Cascading Style Sheets\) is used to make the website look beautiful. Before implementing the CSS, a website looks more like a chunk of information. Coders \(you\) use CSS to take that chunk of information and display it in a way that helps the user \(people viewing your website\) digest the material effortlessly by making the website more visually appealing. 

\*You will learn more about CSS in tomorrow's lesson!

{% hint style="info" %}
A well-written HTML file that is neatly organized will make styling the website with CSS much easier and more enjoyable.
{% endhint %}

### Real-World Examples

To give you a better idea of times you may have experienced HTML, I've provided some examples.

![](.gitbook/assets/instagram.jpg)

![](.gitbook/assets/target.jpg)

![](.gitbook/assets/spotify.jpg)

All three of these platforms use HTML to deliver content to their users. However, it is important to note that while HTML is a very powerful tool, CSS is styling the page. Here is an example of what I mean:

With HTML and CSS:

![](.gitbook/assets/targetnocss.jpg)

Without CSS: 

![](.gitbook/assets/targetnostyle.png)

The Target site still has all of it's functionality and displays all of the required information, however, the website is no longer condensed, images are not formatted, and fonts are not set. What other differences do you notice?



### Coding in HTML

In this section, we will go over the fundamentals of HTML.

#### Tags

Tags are used to tell the computer what kind of content the coder \(you\) is wanting to display. Here are some examples of tags in HTML:

```markup
<p>This is the paragraph tag! You can use this for displaying text!</p>
<h1>This is a heading tag! You can use this to display text as headers!</h1>
<h2>Also a heading tag! </h2>
<h3>Another heading tag! Heading tags go all the way up to h6!</h3>
<div>This is a div tag! You can use this to section off information! </div>
<br> ^ This is a break tag! You can use it to make a break in text!
<!-- This is a comment tag! You can use it to help other coders navigate through your code or to set reminders for yourself! -->


```

{% hint style="info" %}
Notice how each tag \(except for break\) has an opening tag \(ex. &lt;p&gt;\) and a closing tag \(ex. &lt;/p&gt;\). This is the common structure for most but not all HTML tags!
{% endhint %}

 [You can find more HTML Tags here!](https://www.w3schools.com/tags/default.asp)

#### Tags, but with _Attributes_

Some tags call for extra information in order to be entirely useful. This extra information is provided in what is called an **attribute**. 

Every attribute has a **name** and a **value**. Here is an example using an anchor tag, which is used for links:

```markup
<a href="www.youtube.com"> Click here to go to Youtube! </a>
```

In this example, "href" is the attribute name, and "www.youtube.com" is the attribute value!

#### &lt;img&gt; Tag

The image tag is especially unique because it can take on many different attributes at a time, and it does not contain a closing tag. For a simple example of the different ways you can implement images into your websites, check out this [link](https://www.w3schools.com/tags/tag_img.asp)!



