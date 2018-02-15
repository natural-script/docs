# Introduction

Welcome to Jste ! The first translated plain text based JS framework in the world !

This documentation is a reference to everything related to Jste starting from how to get started to the most advanced functions and commands including sample codes for every section.

If you faced any problem while using this documentation, feel free to send us on <a href="mailto:project-jste@outlook.com">project-jste@outlook.com</a>

# Get Started
```html
<meta charset="UTF-8">
<link rel="import" href="https://jste-manager.herokuapp.com/loader.min.js">
// All of your code will be only here
```
1\. To get started, you have to be sure first that you have the following requirements:

* Any text editor supports UTF-8 <code>e.g. Notepad, Brackets or MS Visual Studio Code</code>.
* Any browser powered by Webkit like Google Chrome or Gecko like Mozilla Firefox.

2\. Open your favourite text editor and initialize your project by entering the code mentioned.

3\. Save your code at any location on your PC after naming it <code>YOUR_DESIRED_NAME.html</code> and setting its encoding to <code>UTF-8</code>.

# Components
## Setup
```javascript
configure this site with the following properties:
its title is Jste Demo,
its logo is https://preview.ibb.co/c4Knwv/STEM_Alex_Logo.jpg,
its default window resolution is 1366 × 644 in the case of the landscape mode and 412 × 732 in the case of the portrait mode.
```
Setting up the site or the app.

### Properties {docsify-ignore}


Property | Description | Default | Value
-------- | ----------- | ------- | -----
mode | The mode or the type of your project | site | site or app
title | The name of your site or app <code>Usually shown in the site title in the browser tabs bar if the project is a site or in the app toolbar if it is an app</code> | null | YOUR_DESIRED_TITLE
logo | The logo of your site or app <code>Usually shown in the site title in the browser tabs bar if the project is a site | null | THE_URL_OF_YOUR_LOGO
default window resolution | The default resolution of your site | the current window resolution | A global resolution or unique resolution for each of the landscape and the portrait modes

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
remote scrolling | Make the user be able to scroll remotly using the camera through the hand geasture <code>Requires the approval camera acsess</code>.

## Firebase Centre
```javascript
add a firebase centre with the following properties:
its username is jste-9584c,
its password is AIzaSyDMGk_SFlEto93zfGHUbVLwxYiSq00aknk.
```
Google Firebase services initialization.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
username | Your unique username on firebase. | null | FIREBASE_USERNAME
password | Your API key for your firebase. | null | FIREBASE_API_KEY

## Login Form
```javascript
add.login_form();
```
A login form and users system for your app or project powered by Google Firebase.

<aside class="note">Till now this component is added as it is without any properties</aside>

## Page
```javascript
add a page with the following properties:
its name is A_sample_page.
```
Initailizing a page as a container.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this page. | null | THE_NAME

<aside class="note">You can acsess the pages by adding the param <code>?page=THE_PAGE_NAME</code> to the URL</aside>

## Text
```javascript
add a text with the following properties:
its name is A_sample_text,
its text is This is a sample text,
its colour is white,
its background is black,
its font size is 50 pixels,
its font thickness is thick,
its animation is bouncing,
its transparency is 50,
its distance from the top is 50 pixels,
its distance from the right is 100 pixels,
its When it has been clicked, remove it.
```
Any texts including headings, titles and paragraphs.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container or the page which will contain this element | null | THE_NAME_OF_YOUR_DESIRED_CONTAINER
direction | The direction of the text | The default direction of your language | from right to left or from left to right
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
text | The text you have been inserted.
font colour | The colour of the text | null | <a href="#colours">See the colours section</a><a href="#colours">See the colours section</a>.
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

## Image
```javascript
add an image with the following properties:
its name is Maher_Zain_One_Cover,
its title is Maher Zain One Cover,
its FX is rain,
its source is https://i.ytimg.com/vi/gnZjSui_Mc4/maxresdefault.jpg,
its width is 980 pixels,
its length is 500 pixels,
its animation is bounce,
its distance from the top is 50 pixels,
its distance from the right is 100 pixels,
its When it has been clicked, remove it.
```
Any images including the transparent logos and icons.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
title | The description of the image which will appear below it. | null | THE_IMAGE_TITLE
type | The type of that image. ( Only useful if the image is an icon or a logo ) | null | icon
FX | Applying the FX effect you have specified on this image. | null | rain
container | The name of the container or the page which will contain this element | null | THE_NAME_OF_YOUR_DESIRED_CONTAINER
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a><a href="#colours">See the colours section</a>.
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>


## Video
```javascript
add a video with the following properties:
its name is big_buck_bunny_video,
its title is Big Buck Bunny,
its source is https://archive.org/download/BigBuckBunny_328/BigBuckBunny_512kb.mp4,
its width is 980,
its length is 500,
its animation is bounce,
its distance from the top is 100 pixels,
its distance from the left is 50 pixels.
```
Any videos including those are hosted on Youtube and Vimeo.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
title | The title of your video which will appear in the top region of the video player. | null | THE_VIDEO_TITLE
container | The name of the container or the page which will contain this element | null | THE_NAME_OF_YOUR_DESIRED_CONTAINER
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a><a href="#colours">See the colours section</a>.
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

## Audio Player
```javascript
add an audio player with the following properties:
its name is Maher_Zain_One_Playlist,
its width is 300,
its distance from the top is 760 pixels,
its distance from the left is 760 pixels.
```
An audio player which supports playlist and lyrics.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
container | The name of the container or the page which will contain this element | null | THE_NAME_OF_YOUR_DESIRED_CONTAINER
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a><a href="#colours">See the colours section</a>.
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
autoplay | Make that audio player plays the track automatically once it has been loaded.

## Audio
```javascript
add an audio_player with the following properties:
its name is Maher_Zain_One_Playlist,
its width is 300,
its distance from the top is 760 pixels,
its distance from the left is 760 pixels.

add an audio with the following properties:
its audio_player is Maher_Zain_One_Playlist,
its source is https://server3.samaanetwork.net/full.albums/One(Vocals-Only)(International-Version)/09.Rabbee.Yebarik(Vocals-Only.English).mp3,
its title is Rabbee Yebarik,
its cover is https://anghamicoverart.akamaized.net/?id=3510779&size=320,
its author is Maher Zain.
```
An audio item for the audio player component.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
title | The title of the inserted audio file. | null | THE_TRACK_TITLE
author | The author of the inserted audio file. | null | THE_AUTHOR'S_NAME
cover | The cover art of the inserted audio file. | THE_COVER_URL
source | The source of the inserted audio file. | null | THE_AUDIO_FILE_URL
container | The name of the container or the page which will contain this element | null | THE_NAME_OF_YOUR_DESIRED_CONTAINER
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a><a href="#colours">See the colours section</a>.
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

## Slideshow
```javascript
add a page with the following properties:
its name is test.

add a slideshow with the following properties:
its name is A_sample_slideshow,
its container is test.
```
A responsive carousel which supports images and videos including Youtube and Vimeo streamed videos.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container or the page which will contain this element | null | THE_NAME_OF_YOUR_DESIRED_CONTAINER
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a><a href="#colours">See the colours section</a>.
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
autoplay | Make that carousel play automatically once it has been loaded.

## Container
```javascript
add a page with the following properties:
its name is welcome.

add a container with the following properties:
its name is shape1,
its shape is triangle,
its container is welcome,
its width is 50 pixels,
its length is 50 pixels,
its animation is fadeInLeft,
its distance from the top is 45%,
its distance from the left is 10%,
its background is red.
```
A responsive carousel which supports images and videos including Youtube and Vimeo streamed videos.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container or the page which will contain this element | null | THE_NAME_OF_YOUR_DESIRED_CONTAINER
shape | The shape mask of that element | null | triangle, trapezoid, parallelogram, rhombus, pentagon, hexagon, heptagon, octagon, decagon, circle or ellipse.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a><a href="#colours">See the colours section</a>.
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
grid | set all the children to be appeared as a responsive row.

## Button
```javascript
add a raised and switched button with the following properties:
its name is A_sample_button,
its text is This is a sample button,
its width is 200 pixels,
its length is 100 pixels,
its font colour is red,
its font thickness is thick,
its animation is bouncing,
its transparency is 50,
its distance from the top is 50 pixels,
its distance from the right is 100 pixels,
its When it has been clicked, remove it.
```
Buttons with various styles and customizations for your app or site.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
text | The text you have been inserted.
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
switched | Determine if this button is switched on or not.
raised | Determine if this button is raised with a slightly shadow or not.
disabled | Determine if this button is disabled or not.

## Tooltip
```javascript
add a button with the following properties:
its name is A_sample_button,
its text is This is a sample button,
its animation is bouncing,
its When it has been clicked, remove it.

add a tooltip with the following properties:
its name is A_sample_tooltip,
its text is This is a sample tooltip,
its font colour is white,
its emitter is A_sample_button,
its direction is from_the_bottom,
its transparency is 50,
its When it has been clicked, remove it.
```
Tooltip to make it easier for you to add a description for any of your elements.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
text | The description of the element from which the tooltip will be emitted.
emitter | The element from which the tooltip will be emitted.
direction | The direction from which the tooltip will be emitted | from the bottom | from the right, from the left, from the top or from the bottom
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font colour | The colour of the icon.
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the icon.
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

## Writing Zone
```javascript
add a writing zone with a counter with the following properties:
its name is A_sample_textbox,
its title is Enter some numbers here,
its maximum is 10,
its requirement is [a-zA-Z],
its width is 200 pixels,
its length is 100 pixels,
its font colour is red,
its font thickness is thick,
its animation is bouncing,
its transparency is 50,
its distance from the top is 50 pixels,
its distance from the right is 100 pixels,
its When it has been clicked, remove it.
```
Textboxes including date & time pickers.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
title | The title of the input field which appears in the field when it's empty and above it and above it after inputting. | null | YOUR_DESIRED_TITLE
prefix | A fixed prefix for the text input field. | null | YOUR_DESIRED_PREFIX
suffix | A fixed suffix for the text input field. | null | YOUR_DESIRED_SUFFIX
maximum | The maximum number for the characters which can be entered in the field | null | YOUR_DESIRED_MAXIMUM_NUMBER
minimum | The minimum number for the characters which can be entered in the field | null | YOUR_DESIRED_MINIMUM_NUMBER
requirement | The required input to be entered in the field | null | REGULAR_EXPRESSION
input type | The type of the value which will be entered in the field | null | password, number, date and time
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
with a counter | Adds a chars counter to the field.
disabled | Disables this field.

## Slider
```javascript
add a slider with a pin and with a digital value editor with the following properties:
its name is A_sample_textbox,
its maximum is 100,
its step is 20,
its width is 200 pixels,
its length is 100 pixels,
its font colour is red,
its font thickness is thick,
its animation is bouncing,
its transparency is 50,
its distance from the top is 50 pixels,
its distance from the right is 100 pixels,
its When it has been clicked, remove it.
```
Sliders with many customizations useful for various purposes.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
maximum | The maximum limit of the slider value. | null | YOUR_DESIRED_MAXIMUM_NUMBER
minimum | The minimum limit of the slider value. | null | YOUR_DESIRED_MINIMUM_NUMBER
step | The number increased or decreased with every slider step | 1 | YOUR_DESIRED_NUMBER
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
with a digital value editor | Adds an input field next to the slider with which you can edit the slider current value.
with a pin | Adds a pin shows the current value when sliding the slider.
disabled | Disables this slider.

## Dropdown Menu
```javascript
add a dropdown menu with the following properties:
its name is features_menu,
its items are Prepared Labs &&& Delicious Meals,
its emitter is features_link,
the commands of the item Prepared Labs are that When it has been clicked, go to the page features &&& When it has been clicked, go to the element feature1,
the commands of the item Delicious Meals are that When it has been clicked, go to the page features &&& When it has been clicked, go to the element feature2.
```
Dropdown menus useful for for the navigation bars.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
items | The items of the menu | null | YOUR_DESIRED_ITEMS_SPLITTED_WITH_&&&
emitter | The element from which the menu emits | null | THE_EMITTER_NAME
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

<aside class="note">To know how to set commands for every specific item in the menu, please refer to the example code mentioned.</aside>

## Table
```javascript
add a table with the following properties:
its name is A_sample_table,
its data is Lucy in the cell Name &&& 18 years old in the cell Age &&&& Frank in the cell Name &&& 20 years old in the cell Age,
its distance from the top is 50 pixels,
its distance from the right is 100 pixels.
```
Tables for many purposes like time tables.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
data | The data of this table | null | See the example to learn more about the table data syntax
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

## Checkbox
```javascript
add a checked checkbox with the following properties:
its name is A_sample_table,
its distance from the top is 50 pixels,
its distance from the right is 100 pixels.
```
Checkboxes to let the user select specific options.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
title | The title of the checkbox | null | YOUR_DESIRED_TITLE
description | The subtitle of the checkbox ( Shown below the main title ). | null | YOUR_DESIRED_SUBTITLE
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
checked | Makes this checkbox checked by default.
disabled | Disables the selection of this checkbox.

## Select Menu
```javascript
add a select menu with the following properties:
its name is message_type,
its title is Message Type,
its items are complaint &&& enquiry,
its container is contact_page_container,
its width is 800 pixels in the case of the landscape mode and 320 pixels in the case of the portrait mode,
its distance from the left is 40 pixels in the case of the landscape mode and 30 pixels in the case of the portrait mode,
its distance from the top is 60 pixels in the case of the landscape mode and 60 pixels in the case of the portrait mode.
```
Select menus to let the user choose an option from several options which you specified for him/her.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
items | The options from which the user will select. | null | YOUR_DESIRED_OPTIONS_SPLITTED_WITH_&&&
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

### Attributes {docsify-ignore}

Attribute | Description
--------- | -----------
disabled | Disables the selection from this menu.

## Dialog Box
```javascript
add a dialog box with the following properties:
its name is intro_video_container,
its width is 800 pixels in the case of the landscape mode and 300 pixels in the case of the portrait mode,
its commands are When it becomes out of the viewport, pause intro_video_about_stem.
```
Modal windows and popups.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

## Sidebar
```javascript
add a sidebar with the following properties:
its name is primary_sidebar,
its distance from the top is 275 pixels,
its background is #69F0AE,
its length is 400 pixels.
```
Sidebars useful for mobile side navigation menus.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element.
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

## Loader
```javascript
add a loader with the following properties:
its name is loading_spinner,
its distance from the top is 275 pixels,
its length is 400 pixels,
its width is 400 pixels.
```
Stylish loaders to show that something is in the loading state.

### Properties {docsify-ignore}

Property | Description | Default | Value
-------- | ----------- | ------- | -----
name | The name you have given to this element | null | YOUR_DESIRED_NAME
container | The name of the container which will contain this element. | null | THE_NAME_OF_YOUR_DESIRED_CONTAINER
type | The type of the loader. | spinner | spinner or bar
width | The generic width of this element | null | YOUR_DESIRED_WIDTH
length | The generic length of this element | null | YOUR_DESIRED_LENGTH
font colour | The colour of the text | null | <a href="#colours">See the colours section</a>
background | The background of this element. | null | <a href="#colours">See the colours section</a>
font size | The size of the text in this element. | null | YOUR_DESIRED_FONT_SIZE
font style | The font style of the text in this element | null | YOUR_DESIRED_FONT_STYLE
font thickness | The thickness of the font of the text in this element | null | thick
animation | The animation of this element on loading it | null | <a href="#animations">See the animations section</a>
transparency | The transparency of this element | null | 0~100
distance from the top | The distance between the top edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the bottom | The distance between the bottom edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the left | The distance between the left edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
distance from the right | The distance between the right edge of the container contains this element and this element | null | YOUR_DESIRED_DISTANCE
attributes | The attributes of this element. <code>Multiple attributes are splitted by '&&&'</code>.
commands | The commands which will be executed when making a specific action on this element | null | <a href="#commands">See commands section</a>

<aside class="note">Bar loaders requires a value which can be set dynamically using the commands.</aside>

<aside class="note">Every spinner loader should has the same values for both of its width and length.</aside>

# Text Operators

In Jste Framework, there are a group of specific universal keywords and operators used to enter special or dynamic text, and in the following you will find a list of all of these operators and their descriptions:

Text customizing operators:

Operator | Description
-------- | -----------
<< write this text in a bold font: YOUR_TEXT_HERE >> | Make the text bold.
<< write this text in an italic font: YOUR_TEXT_HERE >> | Make the text italic.
<< write this text in an underlined font: YOUR_TEXT_HERE >> | Make the text underlined.
<< write this text in a bold and italic font: YOUR_TEXT_HERE >> | Make the text bold and italic.
<< write this text in a bold and underlined font: YOUR_TEXT_HERE >> | Make the text bold and underlined.
<< write this text in an italic and bold font: YOUR_TEXT_HERE >> | Make the text bold and italic.
<< write this text in an italic and underlined font: YOUR_TEXT_HERE >> | Make the text italic and underlined.
<< write this text in an underlined and bold font: YOUR_TEXT_HERE >> | Make the text bold and underlined.
<< write this text in an underlined and italic font: YOUR_TEXT_HERE >> | Make the text italic and underlined.
<< write this text in an underlined, italic and bold font: YOUR_TEXT_HERE >> | Make the text italic, underlined and bold.
<< write this text in an underlined, bold and italic font: YOUR_TEXT_HERE >> | Make the text italic, underlined and bold.
<< write this text in a bold, italic and underlined font: YOUR_TEXT_HERE >> | Make the text italic, underlined and bold.
<< write this text in a bold, underlined and italic font: YOUR_TEXT_HERE >> | Make the text italic, underlined and bold.
<< write this text in an italic, bold and underlined font: YOUR_TEXT_HERE >> | Make the text italic, underlined and bold.
<< write this text in an italic, underlined and bold font: YOUR_TEXT_HERE >> | Make the text italic, underlined and bold.
<< a line break >> | Break the current line starting a new line.

Dynamic text operators:

Operator | Description
-------- | -----------
<< the value of AN_ELEMENT_NAME >> | A dynamic text updated every 5 seconds contains the value of the mentioned element <code>Till now, it's supported only by the text property of the text component</code>
<< the user's name >> | The current user's registered name
<< the user's email >> | The current user's registered E-mail

Constants operators:

Operator | Description
-------- | -----------
<< the window length >> | The height of the current viewport in pixels.
<< the window width >> | The width of the current viewport in pixels.
<< the screen length >> | The height of the device screen in pixels.
<< the screen width >> | The width of the device screen in pixels.

Icons operators:

Operator | Description
-------- | -----------
<< an icon of THE_ICON_NAME >> | Inserts the mentioned icon.

<aside class="note">You can get the names of the supported icons at <a href="http://fontawesome.io/icons/">the fontawesome cheatsheet</a></aside>

#Commands
From the most exclusive features of Jste is the ability of programming in your natural local language which you speaks in your daily life.

This section is a reference to all the commands and functions which Jste supports till now.

<aside class="warning">Please don't use the experimental functions in the production, as we haven't finished buildng them yet, so using them will be very risky for your application</aside>

## Events
Most of the events in Jste English edition are started with the word <code> When </code> and end with <code> , </code> to facilitate writing and reading them and in the following you will find a list of all of these events and their descriptions:

Event | Description
----- | -----------
When it has been clicked, | It is fired when someone clicks the element.
When the mouse pointer has been moved over it, | It is fired when someone moves the mouse pointer over the element.
When the mouse pointer has been moved away from it, | It is fired if someone was moving the mouse pointer over the element and then moved it away from it.
When the mouse pointer is being moved out of it, | It is fired when the mouse pointer is in the state of moving outside the element zone.
When the mouse pointer is being moved over it, | It is fired when the mouse pointer is in the state of moving over the element zone.
When it is no longer clicked, | It is fired if someone was clicking the element and then relased the mouse button up.
When it has been double clicked, | It is fired when someone double clicked the element.
When it has been right clicked, | It is fired when someone right clicked the element.
When a key has been pressed while focusing it, | It is fired when someone pressed a keyboard key while focusing the element <code>Mostly used for textboxes</code>.
When a key is being pressed while focusing it, | It is fired when someone is pressing a keyboard key while focusing the element <code>Mostly used for textboxes</code>.
When its contents have been modified, | It is fired when the value of the element has been changed <code>e.g. The text in the textbox</code>.
When it has been focused, | It is fired when the element is focused <code>Mostly used for textboxes</code>.
When it is being focused, | It is fired when the element is being focused <code>Mostly used for textboxes</code>.
When it is no longer focused, | It is fired when the element is no longer focused <code>Mostly used for textboxes</code>.
When the data of this form has been sent, | It is fired when the data of the element has been sent <code>Can be used only for forms</code>.
When it has been scrolled, | It is fired if someone scrolled this element in any direction.
When the user said: A_HOT_WORD, | It is fired if someone said the special hot word mentioned <code>Requires the approval microphone acsess</code>.
When it becomes in the viewport, | It is fired if the element entered the viewport.
When it becomes out of the viewport, | It is fired if the element escaped from the viewport.

## Conditional Statements

While developing your app or website using Jste Framework, you may want to specifiy conditions under which the commands will only execute and run, so Jste Framework supports the conditional statements including the mathematical comparisons and the absolute conditions as in the following:

### Mathematical Comparisons
```javascript
When it has been clicked, remove it in the case that the value of angle_field is greater than the result_field
```

Operator | Equivalent
-------- | ----------
is | ==
isn't | !=
is greater than | >
is smaller than | <

### Absolute Conditions
```javascript
When it has been clicked, remove it in the case that the device is a phone
```

Condition | Description
--------- | -----------
the keyboard is shown | Check if the On-Screen keyboard is opened ( In app mode only ).
the device is a phone | Check if the current device is a phone.
the device is a tablet | Check if the current device is a tablet.
the device is a desktop | Check if the current device is a desktop.
the bluetooth is turned on | Check if the bluetooth is turned on ( In app mode only ).
the bluetooth is turned off | Check if the bluetooth is turned off ( In app mode only ).
the WIFI is turned on | Check if the WIFI is turned on ( In app mode only ).
the WIFI is turned off | Check if the WIFI is turned off ( In app mode only ).

## Timed Commands

In many cases, you don't want to execute the commands once the event has been fired as you may want to execute it after or every a specific time, so Jste Framework offers the option to modify the timing of any command you want as in the following:

### Setting the command timeout {docsify-ignore}
```javascript
When it has been clicked, remove it after a period of 2 hours
```

To determine the time after which the command will be executed you have to write <code>after a period of THE_PERIOD_HERE</code> after the whole command as in the example.

### Setting the command time interval {docsify-ignore}
```javascript
When it has been clicked, remove it every a period of 2 hours
```

To determine the time every which the command will be executed you have to write <code>every a period of THE_PERIOD_HERE</code> after the whole command as in the example.

<aside class="note">To learn more about the period units, please refer to <a href="#time-periods">the periods section</a></aside>

## Removing Elements
You can remove any element or component programmatically while the running of your site or app through the removing commands as in the following:

### Removing the same element on which the event has been applied
```javascript
When it has been clicked, remove it
```
You can remove the same element on which the event has been applied through the command <code>remove it</code> as in the example.

### Removing another element rather than the one on which the event has been applied
```javascript
When it has been clicked, remove THE_ELEMENT_NAME
```
You can remove another element rather than the one on which the event has been applied by mentioning it by its name through the command <code>remove THE_ELEMENT_NAME</code> as in the example.


## Hyperlinking

Through Jste Framework, you have the ability to add hyperlinks to any element you want. Not only activated on clicking that element, but on firing any event you specifiy.

You can add six hyperlinks types as in the following:

### URL
```javascript
When it has been clicked, go to the url https://www.google.com.eg/
```

You can add a hyperlink to any URL through the code <code>go to the url THE_DESIRED_URL</code> as in the example.

### Email

```javascript
When it has been clicked, go to the email project-jste@outlook.com
```

You can add a hyperlink to any Email through the code <code>go to the email THE_DESIRED_EMAIL</code> as in the example.

### Page

```javascript
When it has been clicked, go to the page welcome_page
```

You can add a hyperlink to any page in your site or app through the code <code>go to the page THE_DESIRED_PAGE_NAME</code> as in the example.

### Element

```javascript
When it has been clicked, go to the element post_container
```

You can add a hyperlink to any element or component exists in your page through the code <code>go to the element THE_DESIRED_ELEMENT_NAME</code> as in the example.

### Dialog Box

```javascript
When it has been clicked, open the dialog box learn_more
```

You can add a hyperlink to any dialog box exists in your page through the code <code>open the dialog box THE_DESIRED_DIALOG_BOX_NAME</code> as in the example.

### Sidebar

```javascript
When it has been clicked, open the sidebar side_nav
```

You can add a hyperlink to any sidebar exists in your page through the code <code>open the dialog box THE_DESIRED_SIDEBAR_NAME</code> as in the example.

## Media Controls

You can control the media players programmatically and apply many commands on them like playing or pausing them as in the following:

### Playing
```javascript
When it has been clicked, play THE_ELEMENT_NAME
```
You can play any video or audio on firing an event on any element you want by its name through the command <code>play THE_ELEMENT_NAME</code> as in the example.

### Pausing
```javascript
When it has been clicked, pasue THE_ELEMENT_NAME
```
You can pause any video or audio on firing an event on any element you want by its name through the command <code>pause THE_ELEMENT_NAME</code> as in the example.

### Setting the time position to an absolute value
```javascript
When it has been clicked, set the time position of THE_ELEMENT_NAME to 5
```
You can set the current time position of any video or audio to any value in seconds by its name through the command <code>set the time position of THE_ELEMENT_NAME to THE_VALUE</code> as in the example.

<aside class="note">To learn more about the absolute values syntax, please refer to <a href="#absolute-values">the absolute values section</a>.</aside>

### Setting the time position to a value of another element
```javascript
When it has been clicked, set the time position of THE_ELEMENT_NAME to the value of THE_RESOURCE_ELEMENT_NAME
```
You can set the current time position of any video or audio to a value requested from another element by its name through the command <code>set the time position of THE_ELEMENT_NAME to the value of THE_RESOURCE_ELEMENT_NAME</code> as in the example.

## Elements values

You can change the value of any element or component you want programmatically during the runtime of you site or app as in the following:

### Setting the value of the current element to an absolute value
```javascript
When it has been clicked, set its value to Hello World !
```

You can change the value of the element on which the event has been fired to an absolute value through the command <code>set the value of THE_ELEMENT_NAME to THE_ABSOLUTE_VALUE</code> as in the example.

<aside class="note">To learn more about the absolute values syntax, please refer to <a href="#absolute-values">the absolute values section</a>.</aside>

### Setting the value of the current element to the value of another element
```javascript
When it has been clicked, set its value to the value of THE_RESOURCE_ELEMENT_NAME
```

You can change the value of the element on which the event has been fired to the value of another element through the command <code>set the value of THE_ELEMENT_NAME to the value of THE_RESOURCE_ELEMENT_NAME</code> as in the example.

### Setting the value of any element to an absolute value
```javascript
When it has been clicked, set the value of THE_ELEMENT_NAME to Hello World !
```

You can change the value of any element to an absolute value through the command <code>set the value of THE_ELEMENT_NAME to THE_ABSOLUTE_VALUE</code> as in the example.

<aside class="note">To learn more about the absolute values syntax, please refer to <a href="#absolute-values">the absolute values section</a>.</aside>


### Setting the value of any element to the value of another element
```javascript
When it has been clicked, set the value of THE_ELEMENT_NAME to the value of THE_RESOURCE_ELEMENT_NAME
```

You can change the value of any element to the value of another element through the command <code>set the value of THE_ELEMENT_NAME to the value of THE_RESOURCE_ELEMENT_NAME</code> as in the example.

## Elements Properties:
```javascript
When it has been clicked, set the width of THE_ELEMENT_NAME to 30 pixels
```
```javascript
When it has been clicked, set its background to a random dark colour
```

You can change various properties of any element or component you want programmatically during the runtime of you site or app, and these properties are:

1. background
2. width
3. length
4. font colour

and you can set them easily by replacing the word value in the example code in the <a href="#elements-values">elements values section</a> as in these two examples.

## Databases Managament

<aside class="note">To use the databases management features you have to provide your firebase app information. <b>For more information: <a href="#firebase-centre">See the Firebase Centre component section.</a></b></aside>.

Jste Framework offers various commands to manage you Google Firebase Database without any experiences as in the following:

### Inserting Data

You can insert any data based on the values of the other elements in your Firebase database as in the following:

#### Inserting Data To The Public Database
```javascript
When it has been clicked, go to the public database egypt the branch citizines and then insert the following data: the value of name_input in the slot name, the value of address_input in the slot address
```
To insert data in the public database, you have to use the command <code>go to the public database THE_DATABASE_NAME the branch THE_BRANCH_NAME and then insert the following data: the value of THE_RESOURCE_ELEMENT in the slot THE_NAME_OF_THE_SLOT_IN_WHICH_THE_DATA_WILL_BE_STORED</code> splitting each data with <code>, </code> as in the example.

#### Inserting Data To The User's Private Database
```javascript
When it has been clicked, go to the private database hobbies the branch sports and then insert the following data: the value of sport1_input in the slot sport1, the value of sport2_input in the slot sport2
```

To insert data in the user's private database, you have to use the command <code>go to the private database THE_DATABASE_NAME the branch THE_BRANCH_NAME and then insert the following data: the value of THE_RESOURCE_ELEMENT in the slot THE_NAME_OF_THE_SLOT_IN_WHICH_THE_DATA_WILL_BE_STORED</code> splitting each data with <code>, </code> as in the example.

<aside class="note">To use this option, you have to add a login form to your site or app. <b>For more information: <a href="#login-form">See the Login Form component section.</a></b></aside>.

### Requesting Data

After inserting data in your Google Firebase database, you may want to request them later to use them in various purposes like setting them as values of the elements and the components of your site or app as in the following:

#### Requesting Data From The Public Database
```javascript
When it has been clicked, go to the public database egypt the branch citizines and then get the value of the slot address which has the same class of the value of name_input in the slot name and set it as the value of the_citizin_address
```

To request data from the public database, you have to use the command <code>go to the public database THE_DATABASE_NAME the branch THE_BRANCH_NAME and then get the value of the slot THE_RESOURCE_SLOT which has the same class of the value of THE_ELEMENT_WHICH_ITS_VALUE_IS_THE_COMPARING_SLOT in the slot THE_COMPARING_SLOT and set it as the value of THE_ELEMENT_WHICH_ITS_VALUE_WILL_BE_CHANGED</code>.

#### Requesting Data From The User's Private Database
```javascript
When it has been clicked, go to the private database hobbies the branch sports and then get the value of the slot sport2 which has the same class of the value of sport1_input in the slot sport1 and set it as the value of sport2
```

To request data from the user's private database, you have to use the command <code>go to the private database THE_DATABASE_NAME the branch THE_BRANCH_NAME and then get the value of the slot THE_RESOURCE_SLOT which has the same class of the value of THE_ELEMENT_WHICH_ITS_VALUE_IS_THE_COMPARING_SLOT in the slot THE_COMPARING_SLOT and set it as the value of THE_ELEMENT_WHICH_ITS_VALUE_WILL_BE_CHANGED</code>.

<aside class="note">To use this option, you have to add a login form to your site or app. <b>For more information: <a href="#login-form">See the Login Form component section.</a></b></aside>.

## Flashlight

You can control the flashlight of the Android or the IOS device if your app is running inside the Jste manager app as in the following:

### Toggling The Flashlight
```javascript
When it has been clicked, toggle the flashlight
```

You can toggle the flashlight programatically by using the command: toggle the flashlight

### Turning On The Flashlight
```javascript
When it has been clicked, turn on the flashlight
```

You can turn on the flashlight programatically using the command: turn on the flashlight

### Turning Off The Flashlight
```javascript
When it has been clicked, turn off the flashlight
```

You can turn off the flashlight programatically using the command: turn off the flashlight

## Bluetooth

You can control the bluetooth of the Android device if your app is running inside the Jste manager app as in the following:

### Turning On The Bluetooth
```javascript
When it has been clicked, turn on the bluetooth
```

You can turn on the bluetooth programatically using the command: turn on the bluetooth

## WIFI

You can control the WIFI of the Android device if your app is running inside the Jste manager app as in the following:

### Turning On The WIFI
```javascript
When it has been clicked, turn on the WIFI
```

You can turn on the WIFI programatically using the command: turn on the WIFI

### Turning Off The WIFI
```javascript
When it has been clicked, turn off the WIFI
```

You can turn off the WIFI programatically using the command: turn off the WIFI

## On-Screen Keyboard

You can control the on-scrren keyboard of the Android device if your app is running inside the Jste manager app as in the following:

### Showing The On-Screen Keyboard
```javascript
When it has been clicked, show the keyboard
```

You can show the on-screen keyboard programatically using the command: show the keyboard

### Hiding The On-Screen Keyboard
```javascript
When it has been clicked, hide the keyboard
```

You can hide the on-screen keyboard programatically using the command: hide the keyboard

# Absolute Values

When you set a value or a property to an absolute value programatically, you may include some variables in that value besides the static text as in the following:

Variable | Description
-------- | -----------
<< the value of THE_ELEMENT_NAME >> | The value of the inserted element.
<< the result of the mathematical expression: A_MATHEMATICAL_EXPRESSION >> | The result of the inserted mathematical expression.

# Colours

This section is a reference to all the colours you may use during the developing of you site or app:

* black
* white
* red
* blue
* cyan
* green
* gray
* yellow
* orange
* teal
* pink
* light green
* transparent
* a random colour
* a random light colour
* a random dark colour

# Animations

This section is a reference to all the animations you may use during the developing of you site or app:

* bounce
* flash
* pulse
* rubberBand
* shake
* headShake
* swing
* tada
* wobble
* jello
* bounceIn
* bounceInDown
* bounceInLeft
* bounceInRight
* bounceInUp
* bounceOut
* bounceOutDown
* bounceOutLeft
* bounceOutRight
* bounceOutUp
* fadeIn
* fadeInDown
* fadeInDownBig
* fadeInLeft
* fadeInLeftBig
* fadeInRight
* fadeInRightBig
* fadeInUp
* fadeInUpBig
* fadeOut
* fadeOutDown
* fadeOutDownBig
* fadeOutLeft
* fadeOutLeftBig
* fadeOutRight
* fadeOutRightBig
* fadeOutUp
* fadeOutUpBig
* flipInX
* flipInY
* flipOutX
* flipOutY
* lightSpeedIn
* lightSpeedOut
* rotateIn
* rotateInDownLeft
* rotateInDownRight
* rotateInUpLeft
* rotateInUpRight
* rotateOut
* rotateOutDownLeft
* rotateOutDownRight
* rotateOutUpLeft
* rotateOutUpRight
* hinge
* jackInTheBox
* rollIn
* rollOut
* zoomIn
* zoomInDown
* zoomInLeft
* zoomInRight
* zoomInUp
* zoomOut
* zoomOutDown
* zoomOutLeft
* zoomOutRight
* zoomOutUp
* slideInDown
* slideInLeft
* slideInRight
* slideInUp
* slideOutDown
* slideOutLeft
* slideOutRight
* slideOutUp

# Measuring Units

This section is a reference to all the measuring units you may use during the developing of you site or app:

## Lengths

* x pixel(s)
* x centimetre(s)
* x millimetre(s)
* x inche(s)
* x point(s)
* x pica(s)

## Time Periods

* a minuit / x minuits
* a millisecond / x milliseconds
* a second / x seconds
* an hour / x hours
* a day / x days
