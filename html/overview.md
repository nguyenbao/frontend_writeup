## Overview of HTML


HTML is composed by many **Tag**. The structure of the HTML file should be like below

```html
<html>
<head>
<!-- Some definition come here -->
</head>
<body>
<!-- Some definition come here -->
</body>
</html>
```

### Open Tag and Close Tag

A specific tag should be opened and closed properly. Open tag and close tag should look as below:

```html
<div> : Open tag of div
</div>: Close tag of div
```

You can place an open and close tag inline with thin the syntax: 

```html
<img src="/src/to/image" />
```

The character ```/``` means this is a close tag.

Below is an example of html code that tags are opened and closed properly: 

```html
<div>
   <label>Username</label>
   <input type="text" />
</div>
<div>
   <label>Password</label>
   <input type="password" />
</div>
```

You can see that each tag ```div``` has two children tags ```label``` and ```input```. Each tag is opened and closed properly. 

Below is an example of html code that tags are opened and closed improperly: 

```html
<div>
   <label>Username </div>
   <input type='text' />
</label>
```

You can see that the tag ```div``` is opened, then comes the ```label``` tag. This means ```label``` is supposed to be the child tag of ```div```. But then come the close tag of ```div``` before the close tag of ```label```. This make the browser will not display properly. 


### HTML Structure

The whole html code will be surrounded by the tag ```html``. 

```html
<html>
Your html content will come inside this tag
</html>
```

Inside the tag ```html``` are the two children tags ```head``` and ```body```

```html
<html>
    <head>
        ...
    </head>
    <body>
        Here you define actual DOM tag to display to the user. This part is visible to the user.
    </body>
</html>
```

#### Head tag

The **```head```** tag let the browser knows aditional resource to load. You can also put ```meta``` tag here to describe about information about your html code. **The browser will not display content in ```head``` tag to user**. 

```html
<head>
    <meta charset="UTF-8" />
    <meta name="description" content="HTML Tutorial" />
    <title>Title of the page</title>
    <link rel="stylesheet" type="text/css" href="theme.css" />
    <script src="my_javascript.js"></script>
</head>
```

The following tags can be used inside the ```head``` tag.

* ```meta```: To put information to describe more about your html content. 
* ```link```: This tag is to describe the link of stylesheet file (css) to let browser load when it opens this html content. 
* ```script```: This tag is to describe the link of javascript file (js) to let browser load when it opens this html content.

#### Body tag

### Tag structure

A tag can has many attributes. Each attribute can be assigned value. Attribute is defined in open tag. 

```html
<div id="Test" class="Test" name="Test">

</div>
```

The abovee ```div``` tag has three attributes ```id``` ,```class``` and ```name```. All three attributes have the same value as **Test**.

