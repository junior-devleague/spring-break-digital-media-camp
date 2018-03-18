# Article Template

Follow the instructions to create a basic article template that you can then customize.

![Final Example](https://github.com/junior-devleague/spring-break-digital-media-camp/blob/master/day-5-journalism/images/example.png)


## Objective

Take your content and create a newsworthy article for the web!

## Your Challenge

## Part I: HTML

This will be the general overview of your article template. Look at the instructions farther down for more details:

  * ```div``` with ```id``` of "container"
    * ```div``` with ```id``` of "banner"
    * ```div``` with ```id``` of "content"
      * ```div``` with ```id``` of "title"
        * ```h1``` with text that has your article Title.
        * ```h4``` with text that has your name and date. Ex. "By Jane Doe March 19, 2018"
      * ```h2``` with a subheading text.
      * ```p``` with your paragraph text.
      * ```p``` with your paragraph text.
      * ```p``` with your paragraph text.

1. Create a ```div``` with an ```id``` of "container" like so:

``` html
<div id="container"></div>
```

2. Inside of this, create a ```div``` with an ```id``` of "banner". Now your HTML should look like the following:

``` HTML
<div id="container">
    <div id="banner"></div>
</div>
```

3. While still inside your container but outside of the banner, create a ```div``` with an ```id``` of "content" like so:

``` HTML
<div id="container">
    <div id="banner"></div>
    <div id="content"></div>
</div>
```

4. Inside of the content div, create a ```div``` with an ```id``` of "title" like so:

``` HTML
<div id="container">
    <div id="banner"></div>
    <div id="content">
      <div id="title"></div>
    </div>
</div>
```

4. Inside of this title div, create an ```h1``` for your article title, and an ```h4``` for the author and date like so:

``` HTML
<div id="container">
    <div id="banner"></div>
    <div id="content">
      <div id="title">
        <h1>An Article Title</h1>
        <h4>By Jane Doe March 16, 2018</h4>
      </div>
    </div>
</div>
```

5. Outside of your title div, but still within the content div, create an ```h2``` for a subheading if you have one. Then create ```p``` elements for the rest of your content like so:

``` HTML
<div id="container">
    <div id="banner"></div>
    <div id="content">
      <div id="title">
        <h1>An Article Title</h1>
        <h4>By Jane Doe March 16, 2018</h4>
      </div>

      <h2>Subheading 1</h2>
      <p>Hello this is my paragraph.</p>
      <p>Hello this is another paragraph. </p>
      <p>Yes another paragraph!</p>

    </div>
</div>
```

Great job so far!

## Part II: CSS

Go to your CSS file. We will now add some styles to make this look better. Follow the instructions below and change the values of each property to see what it does.

1. Target the ```body``` element.
  * Set the ```margin``` to "0px".
  * Set the ```line-height``` to "2".

For example:
``` CSS
body {
  margin: 0px;
  line-height: 2;
}
```
2. Target the ```id``` of "banner".
  * Set the ```height``` to "350px".
  * Set the ```width``` to "100%".
  * Set the ```background-image``` to "url('image address of your choice')". In the "image address of your choice" area, copy and paste a google image. Right click on the google image, "Copy Image Address", then paste it into the area. Make sure inside of the parenthesis next to the "url", the image address is in quotation marks.
  * Set the ```background-size``` to "cover".
  * Set the ```opacity``` to "0.5".

For example:
``` CSS
#banner {
  height: 350px;
  width: 100%;
  background-image: url("https://www.gettyimages.ca/gi-resources/images/Homepage/Hero/UK/CMS_Creative_164657191_Kingfisher.jpg");
  background-size: cover;
  opacity: 0.5;
}
```
3. Target the ```id``` of "content".
  * Set the ```padding-top``` to "50px".
  * Set the ```padding-left``` to "200px".
  * Set the ```padding-right``` to "200px".

Try this one on your own!

## Customize

1. Play around with various CSS effects: https://www.w3schools.com/cssref/default.asp
2. Add more HTML elements if needed: https://www.w3schools.com/html/
