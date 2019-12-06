# leetcode-frontend-development

## Questions

1. If you have to development a button for mobile, how would you handle onMouse and onTouch events? 
2. What is the difference between SASS variables and custom CSS properties? Show code examples how they work differently.

[Challenge 01](#Challenge-01)
[Challenge 02](#Challenge-02)

## Challenge 01

You have a form with a submit button `<button type="submit">Submit</button>` that uses the event listener onMouseDown to trigger the submit logic.

The problem is that your project manager came with new data about the users. Most of the visitors of your website do not use a mouse. 
Some of them even use a stylus pen to interact with the website. 

How can you solve that in a way that you cover all users (mobile/desktop/mouse/pen)? 
Accoring to your project manager, all the users should be able to active the button submit and send their information regardless of their device or size screen.

Tip: You should explore the correct event listeners.

## Challenge 02

You were assigned a ticket to create a fixed navbar on the bottom of screen. According to the requirments, the navbar should sticky to the bottom all the time during the user navigaton.
A previous developer wrote the code below. However, the navbar implemented stays in a wrong position. 

You have just some minutes to fix that and show the navbar in a demo for the managment team.  How would you solve it changing only one property of CSS?

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="x-ua-compatible" content="ie=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <title>My website</title>

    <link rel="stylesheet" href="css/main.css" />
    <link rel="icon" href="images/favicon.png" />

    <style>

    .main {
      position: relative;
    }

    .navigation {
      background-color: red;
      bottom: 0;
      left: 0;
      min-height: 300px;
      position: absolute,
      width: 100%;
    }

    .footer {
      background-color: black;
      width: 100%;
      height: 500px;
    }

    </style>

  </head>

  <body>
    <section class="main">
      <nav class="navigation"><button>send</button></nav>
    </section>
    <section class="footer">
        I am a footer
    </section>
  </body>
</html>


```






