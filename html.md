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
Notice how each tag \(except for break\) has an opening tag \(ex. &lt;p&gt;\) and a closing tag \(ex. &lt;/p&gt;\). This is the common structure for most HTML tags!
{% endhint %}

 [You can find more HTML Tags here!](https://www.w3schools.com/tags/default.asp)

#### Tags, but with _Attributes_

Some tags call for extra information in order to be entirely useful. This extra information is provided in what is called an **attribute**. 

Every attribute has a **name** and a **value**. Here is an example using an anchor tag, which is used for links:

```markup
<a href="www.youtube.com"> Click here to go to Youtube! </a>
```

In this example, "href" is the attribute name, and "www.youtube.com" is the attribute value!

<quiz name="Gitbook Quiz">
    <question multiple>
        <p>What is gitbook used for?</p>
        <answer correct>To read books</answer>
        <answer>To book hotel named git</answer>
        <answer correct>To write and publish beautiful books</answer>
        <explanation>GitBook.com lets you write, publish and manage your books online as a service.</explanation>
    </question>
    <question>
        <p>Is it quiz?</p>
        <answer correct>Yes</answer>
        <answer>No</answer>
    </question>
    <question>
        <p>This is multiple dropdown quiz, in each dropdown select a correct number corresponding to the dropdown's order</p>
        <answer>
            <option correct>First</option>
            <option>Second</option>
            <option>Third</option>
            <option>Fourth</option>
        </answer>
        <answer>
            <option>First</option>
            <option correct>Second</option>
            <option>Third</option>
            <option>Fourth</option>
        </answer>
        <answer>
            <option>First</option>
            <option>Second</option>
            <option correct>Third</option>
            <option>Fourth</option>
        </answer>
        <answer>
            <option>First</option>
            <option>Second</option>
            <option>Third</option>
            <option correct>Fourth</option>
        </answer>
    </question>
</quiz>



