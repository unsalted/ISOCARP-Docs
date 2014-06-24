# Mou

![Mou icon](http://mouapp.com/Mou_128.png)

## Overview

**Mou**, the missing Markdown editor for *web developers*.

### Syntax

#### Strong and Emphasize 

**strong** or __strong__ ( Cmd + B )

*emphasize* or _emphasize_ ( Cmd + I )

**Sometimes I want a lot of text to be bold.
Like, seriously, a _LOT_ of text**

#### Blockquotes

> Right angle brackets &gt; are used for block quotes.

#### Links and Email

An email <example@example.com> link.

Simple inline link <http://chenluois.com>, another inline link [Smaller](http://smallerapp.com), one more inline link with title [Resize](http://resizesafari.com "a Safari extension").

A [reference style][id] link. Input id, then anywhere in the doc, define the link with corresponding id:

[id]: http://mouapp.com "Markdown editor on Mac OS X"

Titles ( or called tool tips ) in the links are optional.

#### Images

An inline image ![Smaller icon](http://smallerapp.com/favicon.ico "Title here"), title is optional.

A ![Resize icon][2] reference style image.

[2]: http://resizesafari.com/favicon.ico "Title"

#### Inline code and Block code

Inline code are surround by `backtick` key. To create a block code:

	Indent each line by at least 1 tab, or 4 spaces.
    var Mou = exactlyTheAppIwant; 

####  Ordered Lists

Ordered lists are created using "1." + Space:

1. Ordered list item
2. Ordered list item
3. Ordered list item

#### Unordered Lists

Unordered list are created using "*" + Space:

* Unordered list item
* Unordered list item
* Unordered list item 

Or using "-" + Space:

- Unordered list item
- Unordered list item
- Unordered list item

#### Hard Linebreak

End a line with two or more spaces will create a hard linebreak, called `<br />` in HTML. ( Control + Return )  
Above line ended with 2 spaces.

#### Horizontal Rules

Three or more asterisks or dashes:

***

---

- - - -

#### Headers

Setext-style:

This is H1
==========

This is H2
----------

atx-style:

# This is H1
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6


### Extra Syntax

#### Footnotes

Footnotes work mostly like reference-style links. A footnote is made of two things: a marker in the text that will become a superscript number; a footnote definition that will be placed in a list of footnotes at the end of the document. A footnote looks like this:

That's some text with a footnote.[^1]

[^1]: And that's the footnote.


#### Strikethrough

Wrap with 2 tilde characters:

~~Strikethrough~~


#### Fenced Code Blocks

Start with a line containing 3 or more backticks, and ends with the first line with the same number of backticks:

```
Fenced code blocks are like Stardard Markdown’s regular code
blocks, except that they’re not indented and instead rely on
a start and end fence lines to delimit the code block.
```

#### Tables

A simple table looks like this:

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell

If you wish, you can add a leading and tailing pipe to each line of the table:

| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |

Specify alignement for each column by adding colons to separator lines:

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right


### Shortcuts

#### View

* Toggle live preview: Shift + Cmd + I
* Toggle Words Counter: Shift + Cmd + W
* Toggle Transparent: Shift + Cmd + T
* Toggle Floating: Shift + Cmd + F
* Left/Right = 1/1: Cmd + 0
* Left/Right = 3/1: Cmd + +
* Left/Right = 1/3: Cmd + -
* Toggle Writing orientation: Cmd + L
* Toggle fullscreen: Control + Cmd + F

#### Actions

* Copy HTML: Option + Cmd + C
* Strong: Select text, Cmd + B
* Emphasize: Select text, Cmd + I
* Inline Code: Select text, Cmd + K
* Strikethrough: Select text, Cmd + U
* Link: Select text, Control + Shift + L
* Image: Select text, Control + Shift + I
* Select Word: Control + Option + W
* Select Line: Shift + Cmd + L
* Select All: Cmd + A
* Deselect All: Cmd + D
* Convert to Uppercase: Select text, Control + U
* Convert to Lowercase: Select text, Control + Shift + U
* Convert to Titlecase: Select text, Control + Option + U
* Convert to List: Select lines, Control + L
* Convert to Blockquote: Select lines, Control + Q
* Convert to H1: Cmd + 1
* Convert to H2: Cmd + 2
* Convert to H3: Cmd + 3
* Convert to H4: Cmd + 4
* Convert to H5: Cmd + 5
* Convert to H6: Cmd + 6
* Convert Spaces to Tabs: Control + [
* Convert Tabs to Spaces: Control + ]
* Insert Current Date: Control + Shift + 1
* Insert Current Time: Control + Shift + 2
* Insert entity <: Control + Shift + ,
* Insert entity >: Control + Shift + .
* Insert entity &: Control + Shift + 7
* Insert entity Space: Control + Shift + Space
* Insert Scriptogr.am Header: Control + Shift + G
* Shift Line Left: Select lines, Cmd + [
* Shift Line Right: Select lines, Cmd + ]
* New Line: Cmd + Return
* Comment: Cmd + /
* Hard Linebreak: Control + Return

#### Edit

* Auto complete current word: Esc
* Find: Cmd + F
* Close find bar: Esc

#### Post

* Post on Scriptogr.am: Control + Shift + S
* Post on Tumblr: Control + Shift + T

#### Export

* Export HTML: Option + Cmd + E
* Export PDF:  Option + Cmd + P


### And more?

Don't forget to check Preferences, lots of useful options are there.

Follow [@chenluois](http://twitter.com/chenluois) on Twitter for the latest news.

For feedback, use the menu `Help` - `Send Feedback`

***

#ISOCARP USER HANDBOOK

##Content

####General
- How do I log into the panel/ back end?
- How do I find my way in the directory? How do I navigate in the panel?
- How can I change content?
- What can I change?
- How do I know which content to fill in where?
- How can I change content on th
e main page?
- How can I add a theme?
- Do i have to define type sizes and fonts?

####Basic Rules

####Talking Points

- How do I create a new talking point? p.3
- How do I add files to a talking point (document, pictures)? p.4
- Which sort of files can i upload?
- How can I rename, replace or delete files?
- How do I create a slideshow in a talking point?
- Tips for creating a slideshow
- How do I embed a video into a talking point? (Vimeo)
- How do I embed a video into a talking point? (Youtube)
- What can I upload?
- Can I preview my talking point before other people see it?
- How to make my talking point visible on the webpage?
- How to change the order of talking points on the webpage?
- How can I delete a talking point?

####Text Styling

- How do I stylize text (header, bold, italic)? p.5
- How do I add a hyperlink? p.6

####Contributions

- How do i create a contribution page?
- How do I upload a contribution to a contribution page?
- What can I upload?
- How can I rename, replace or delete contributions?
- Can I preview contribution pages before other people see it?
- How to make a contribution page visible on the webpage?
- How to change the order of contribution pages on the webpage?
- How can I delete a contribution page?

####Calendar

- How do I add an event to the calendar? 
- What is the structure of the calendar?

####Who will be there?

- How does the “Who will be there?” section work?

####About

- How do I create an about section?
- Can I add pictures to the about sections?


####Vocabulary:

- backend
- master administrator
- theme administrator
- directory
- panel
- article
- hyperlink
- talking point
- contribution
- excerpt
- visible/ invisible subpages
- fold out menu
- pop-up window
- embed-link
- link

##General


### How do I log into the backend?

- go to the ISOCARP 2015 webpage (isocarp2015.org)
- behind the webpage name (URL) in the address bar you type: */panel*
(visual)
- hit enter
- you will see a window asking you for your username and password
- fill in the username and password you got from the main administrator
- hit enter or press the **“Login”** button
- you are now logged in to the panel/ back end





### How do I find my way in the directory? How do I navigate in the panel?

- on the left side of the panel, in the black area you find the directory
- here you can find your way to the the sections of the webpage you want to change
- the structure is directly related to the structure of the webpage
- see it as a folders (just like on the computer) which contain and organize the content of the webpage
- you can go back in the structure with hitting the **back arrow** on top of the directory (visual)
- you can also navigate by clicking the directory names on top of every page divided by small arrows. They show in which folder you are currently in

**TIP: don’t worry about the hidden pages by now, they are further explained [here](//)**


### How can I change content?

- find the right section in the directory that you want to change **(see page: [How to find your way in the directory](//))**
- you can work on the content like in any other text editor
- type or copy/ paste text from the panel or any external program
- hit the **“Safe”** button at the bottom of the page
- the changes of the content are visible on the webpage now

### What can I change?

- basically all content is editable
- yet there is content with different accessibilities
- the content on the main page can only be changed by the main administrator (Tom). 
- for editing menu items please contact the main administrator (Tom).
- for adding a theme please contact the main administrator (Tom).
- for changing the wording of buttons please contact the main administrator (Tom).


### How do I know which content to fill in where?

- there are different text fields in most sections
- they have titles according to the sort of information you have to fill in (title/ text/ description/ excerpt)
- some text fields have also small specifications underneath them to clarify the kind or the length of the text which is to be filled in 

### How can I change content on the main page?

- the content on the main page can only be changed by the main administrator (Tom)
- please contact Tom if you have any remarks

### How can I add a theme?

- themes can only be added by the main administrator (Tom)
- please contact Tom if you want to add a theme

### Do i have to define type sizes and fonts?

- no
- you don’t have to make any decisions about the type size or the font
- the program is formatting all text automatically, according to the section the content is filled in
- also when you copy text from other programs, it will make no difference in which type size or font the original text is formated in

**TIP: you can easily style text (header/ bold/ italic) for an explanation, please click [here](//)**


### Basic Rules

- don’t delete anything other than talking points, contributions and about sections and only if you have to
- don’t move too much stuff around and only move it if you know what you are moving and why
- don’t move work from other people without asking or permission from the administrators


##Talking Points

### How do I create a new talking point?

- from the **“Home”** directory
- go to **“Themes”** and pick your theme
- go to **“Talking Points”**
- you will see a list of existing talking points in the directory to the left
- hit the **“+”** button right above the list of talking points in the directory on the left
- a little window is opening called **“Add a new page”**
- fill in the title of your talking point
- click on the fold out menu under **“Template”** and select **“Article (article)”**
- hit **“Save”** to continue
- hit **“Cancel”** to cancel the action
- you will see a page with several text boxes
- fill them in according to the descriptions
- fields which are marked with a **“*”** are necessary to fill in
- hit the **“Save”** button at the end of the page
- the talking point is created now

**TIP: to see how to preview the talking point you created click [here](//)**

```
ATTENTION: The talking point you created is not visible on the ISOCARP2105 web page yet. You are only one simple step away. To see how to make the talking point visible on the ISOCARP2105 web page go to page: ...
```



### How do I add files to a talking point (documents, pictures)?

- go to the **“Talking Points”** section in the directory (Home>Theme>Theme Name>Talking Points)
- find the talking point to which you want to add files to in the directory or create a new one
- on top of the page of your talking point you see a menu, listing the points: **“Content”**, **“Files”**, **“URL”**
- you are currently on the **“Content”** section of the talking point, **“Content”** is highlighted red
- go to **“Files”**
- here you can see files which are uploaded already or a note saying: **“No files so far”** in case there are no files uploaded
- on the right top of the page there is a button saying **“Upload a new file”**
- hit the button to upload a new file
- a black pop-up window opens (upload window)
- hit the button **“Choose File”**
- another window opens showing the directory of your own computer
- find the file you want to upload in your system
- select the file and hit **“open”** or double click the file to open

```
ATTENTION: you can only select one file at a time
```
- you are now back in the upload window
- the name of the file you want to upload is shown in the bar behind the button **“Choose File”**
- hit **“Upload”**
- the file is now uploaded to the talking point
- it will show automatically on the webpage in case the talking point is visible

```
NOTICE: big files and slow internet connections result in longer loading times. Stay patient. The process should not take longer than 2 minutes.
```
- after your file is uploaded you see a little thumbnail of your file at the file page with the file’s name and it’s size
- you can upload pictures (jpg/ png/ …) or documents (word/ PDF/ …)

**TIP: To see how to create a talking point, please click [here](//)**

**TIP: To see how to change or delete files from a talking point, please click [here](//)**

**TIP: To see how to preview the talking point you created, please click [here](//)**

**TIP: To see how to sort the list of talking points, please click [here](//)**


### Which sort of files can i upload?

- you can upload pictures (jpg/ png/ …) or documents (word/ PDF/ …)


### How can I rename, replace or delete files?

- next to the thumbnail of the file you want to change, you see a little black menu with the buttons: **“Edit”**, **“Replace”**, **“Delete”**

- hit **“Edit”** when you want to change the name of your file
- a window opens in which you can change the name of the file
- don’t forget to hit **“Save”** in the window in order to apply the change

- hit **“Replace”** in order to replace a file
- a window opens (upload window)
- follow the instructions to replace the file
- the process is similar to uploading a file **(see page: [How to upload a file](//))
**
- hit **“Delete”** in order to delete a file
- a black window opens
- hit **“Delete”** to confirm deleting the file 
- hit **“Cancel”** to stop the process

### How do i create a slideshow in a talking point?

- to create a slideshow, please upload several pictures (jpg/ png) to the files section of your talking points
- the slideshow on the web page is generated automatically
- the images are automatically ordered by the alphabet
- the order of images on web page will be the same like the order on the files section of the talking point
- to change the order of images in a slideshow, please rename them according to an alphabetical system (1filename , 2filename, 3filename, … or Afilename, Bfilename, Cfilename, …)
- to change the order of the images

**TIP: For tips on how to create a good slideshow, please click [here](//)**

**TIP: To see how to change the name of a file, please click [here](//)**

### Tips for creating a slideshow

- all pictures are automatically scaled to the same height in the display on the webpage
- if the pictures you upload are very small or with a low resolution, they will appear pixelated or blurry on the webpage
- it is advisable to upload only pictures with the same orientation to the same slideshow (portrait or landscape) in order to create an even appearance
- don’t upload to many pictures (to reduce loading time of the webpage)
- only upload pictures which are important to support the story of the talking point
(to reduce loading time of the webpage and to not confuse the viewer)


### How do I embed a video into a talking point? (Vimeo)

```
INFO: Adding a video to a talking point works different from uploading files (pictures, documents). For embedding a video into a Talking Point, you need to get an “embed code” from the platform the video is hosted on
```

- go to the video page of the video you want to embed (Vimeo)
- click the **“Share”** button (little paper plane) that appears when you hover your mouse over the video player (visualisation)
- in the pop-up window, you'll see a field containing the embed code for the video
- just copy the code
- go back to the panel
- find the talking point to which you want to add a video in the directory or create a new one
- paste the code into the **“Video”** field on the talking point page
- hit **“Save”**
- the video is now embedded into you talking point

**TIP: To see how to upload pictures or documents, please click [here](//)**
### How do I embed a video into a talking point? (Youtube)

```
INFO: Adding a video to a talking point works different from uploading files (pictures, documents). For embedding a video into a Talking Point, you need to get an “embed code” from the platform the video is hosted on (Vimeo/ Youtube)
```

- go to the video page of the video you want to embed (Youtube)
- click the **“Share”** button under the video (right side, under the “Views”)
- click the **“Embed”** button in the menu that shows up
- copy the code provided in the expanded box
- go back to the panel
- find the talking point to which you want to add a video in the directory or create a new one
- paste the code into the **“Video”** field on the talking point page
- hit **“Save”**
- the video is now embedded into you talking point

**TIP: To see how to upload pictures or documents, please click [here](//)**
### What can I upload?

- general information
- inspiration
- thematically interesting papers
- relevant world news
- interesting discussions (from comments)
- interesting contributions
- inspirational quotes
- questions
- challenges

### Can I preview my talking point before other people see it?

- it is very simple to preview the changes you have made
- click the little symbol of a magnifying glass on the right top side of the talking point page
- a new tab will open with a preview to the talking point you created


### How to make my talking point visible on the ISOCARP2105 web page?

- go to the **“Talking Points”** section in the directory (Home>Theme>Theme Name>Talking Points)
- you will see a list with all existing talking points
- they are separated in “Visible subpages” and “Invisible subpages”
- all talking points in “Visible subpages” are displayed on the ISOCARP2015 web page
- all talking points in “Invisible subpages” can’t be viewed by visitors of the page
- newly created talking points are saved under “Invisible subpages” and are thus not visible
- to make them visible click the “Sort” button on top of the directory
- the icons of the talking points in the directory change to a list symbol and the cursor changes to direction arrows when you hover over them
- simply drag the new talking point into the list of “Visible subpages” to make it visible
- drop it in the position you want your talking point to appear in the list of talking points
- click “Ok” to save the changes
- click “Cancel” if you don’t want the changes to apply



### How to change the order of talking points on the webpage?

- go to the **“Talking Points”** section in the directory (Home>Theme>Theme Name>Talking Points)
- you will see a list with all existing talking points
- click the **“Sort”** button on top of the directory
- the icons in front of the talking points in the directory change to a list symbol and the cursor changes to direction arrows when you hover over them
- simply drag the talking points in **“Visible subpages”** into the order you wish for
- click **“Ok”** to save the changes
- click **“Cancel”** if you don’t want the changes to apply




### How can I delete a talking point?

- go to the **“Talking Points”** section in the directory (Home>Theme>Theme Name>Talking Points)
- you will see a list with all existing talking points
- in front of every talking point in the list you see a little circle icon with a cross inside
- click the icon of the talking point you wish to delete
- click **“Delete”** in the pop-up window to confirm the action
- click **“Cancel”** to not delete the talking point

##Text Styling


## How do I stylize text (header, bold, italic)?

```
INFO: You can stylise every piece of text (header, bold, italic, link, email) in order to highlight parts or create links. The text style is not immediately visible in the panel though and follows different rules than in usual text editors.
```

- on top of every text box you see buttons for the different style options (h1, h2, h3, bold, italic, link and email)
- **“h”** stands for header
- you can either mark the text you want to change and hit a style option (visual follows…)
- or you click a style button first, then you will see a place holder text within symbols (*/#, for example: \*\*bold text\*\*)
- simply replace the placeholder text with the text which needs to be styled, without deleting the symbols
- you can also type out the indications for stylised text by hand:

# # = header 1 (biggest header size)
## ## = header 2 (medium header size)
### ### = header 3 (smallest header size)

```
NOTE: Header styles are applied to all words which follow until the next line break. To end a header style insert a line break.
```

*\*…\* = italic text*

**\*\*…\*\* = bold text**

(link: URL text: ...) = link

(mail: mail address text: ...) > mail

```
NOTE: Whatever you write behind "text:" appears in your text as link.
``` 

**TIP: Your text won’t appear stylised in the panel. If you want to preview the changes you have made, press the small magnifying glass symbol on the top right of the page you are on.**


### How do I add a hyperlink?

- on top of every text box you see buttons for the different style options (h1, h2, h3, bold, italic, link and email)
- to insert a link click the **“Link”** button 
- a small pop-up window opens
- insert the URL of the webpage you want to link to in the **“Link”** text box
- in the **“Link Text”** text bar, fill in the words which should be highlighted as link in the text

**TIP: You can choose anything to fill in to the “Link Text”. If you are for example linking to www.youtube.com, your link text could be: “Youtube” or “Video” or “Movie Name”**

- click **“Insert Link”** to create the link 
- click **“Cancel”** if you don’t want to create a link


### How do I add a email link?

- on top of every text box you see buttons for the different style options (h1, h2, h3, bold, italic, link and email)
- to insert a link to a mail address click the **“Email”** button 
- a small pop-up window opens
- insert the email address you want you want to link to in the **“Email Address”** text box
- in the **“Link Text”** text bar, fill in the words which should be highlighted as mail-link in the text

**TIP: You can choose anything to fill in to the “Link Text”. If you are for example linking to the mail address of a member, your link text could be: “Contact” or “Name of the member"**

- click **“Insert Link”** to create the link 
- click **“Cancel”** if you don’t want to create a link

##Contributions


### How do i create a contribution page?

- find the **“Contributions”** in the directory (Home>Theme>Theme Name>Contributions)
- you will see a list of existing contribution pages in the directory to the left
- hit the **“+”** button right above the list of contribution pages in the directory
- a little pop-up window is opening called **“Add a new page”
**
- fill in the title of the contribution page
- click on the fold out menu under **“Template”** and select **“Article (article)”**
- hit **“Save”** to continue
- hit **“Cancel”** to cancel the action
- you will see a page with several text boxes
- fill them in according to the descriptions
- fields which are marked with a **“*”** are required to fill in
- hit the **“Save”** button at the end of the page to save the changes
- the contribution is created now

**TIP: to see how to preview the contribution you created please click [here](//)**

```
ATTENTION: The contribution you created is not visible on the ISOCARP2105 web page yet. You are only one simple step away. To see how to make the contribution visible on the ISOCARP2105 web page go to page: ...
```
### How do I upload a contribution to a contribution page?

- go to the **“Contributions”** section in the directory (Home>Theme>Theme Name>Contributions)
- find the contribution page to which you want to add a contribution to in the directory or create a new one 
- on top of the page of your contribution page you see a menu, listing the points: **“Content”**, **“Files”**, **“URL”**
- you are currently on the **“Content”** section of the contribution page, **“Content”** is highlighted red
- go to **“Files”**
- here you can see contributions which are uploaded already or a note saying: **“No files so far”** in case there are no contributions uploaded
- on the right top of the page there is a button saying **“Upload a new file”**
- hit the button to upload a new contribution
- a black pop-up window opens (upload window)
- hit the button **“Choose File”**
- another window opens showing the directory of your own computer
- find the contribution you want to upload in your system
- select the contribution and hit **“open”** or double click the file to open

```
ATTENTION: you can only select one file at a time.
```

- you are now back in the upload window
- the name of the contribution you want to upload is shown in the bar behind the button **“Choose File”**
- hit **“Upload”**
- the contribution is now uploaded to the contribution page
- it will show automatically on the webpage in case the contribution page is visible

```
NOTICE: big files and slow internet connections result in longer loading times. Stay patient. The process should not take longer than 2 minutes.
```

- after the contribution is uploaded you see a little thumbnail of your file at the file page with the contributions’s name and it’s size
- you can upload documents (word/ PDF/ …)

**TIP: To see how to create a contribution page, please click [here](//)**

**TIP: To see how to change or delete contributions from a talking point, please click [here](//)**

**TIP: To see how to preview the contribution page you created, please click [here](//)**

**TIP: To see how to sort the list of contribution pages, please click [here](//)**

### What can I upload?

- you can only upload documents (word/ PDF/ …)

### How can I rename, replace or delete contributions?

- go to the **“Contributions”** section in the directory (Home>Theme>Theme Name>Contributions)
- go to the **"Files"** section
- next to the thumbnail of the file you want to change, you see a little black menu with the buttons: **“Edit”**, **“Replace”**, **“Delete”**

- hit **“Edit”** when you want to change the name of your file
- a window opens in which you can change the name of the file
- don’t forget to hit **“Save”** in order to apply the change

- hit **“Replace”** in order to replace a file
- a pop-up window opens (upload window)
- follow the instructions to replace the file
- the process is similar to uploading a file **(see page: [How to upload a file](//))
**
- hit **“Delete”** in order to delete a file
- a pop-up window opens
- hit **“Delete”** to confirm deleting the file 
- hit **“Cancel”** to stop the process



### Can I preview contribution pages before other people see it?

- it is very simple to preview the changes you have made
- click the little symbol of a **magnifying glass** on the right top side of the contribution page in the panel
- a new tab will open with a preview to the contribution page you created on the ISOCARP2015 web page


### How to make a contribution page visible on the ISOCARP2105 web page?

- go to the **“Contributions”** section in the directory (Home>Theme>Theme Name>Contributions)
- you will see a list with all existing contribution pages
- they are separated in **“Visible subpages”** and **“Invisible subpages”**
- all contribution pages in **“Visible subpages”** are displayed on the ISOCARP2015 web page
- all contribution pages  in **“Invisible subpages”** can’t be viewed by visitors of the web page
- newly created contribution pages are saved under **“Invisible subpages”** and are thus not visible
- to make them visible click the **“Sort”** button on top of the directory
- the icons of the contribution pages in the directory change to a list symbol and the cursor changes to direction arrows when you hover over them
- simply drag the new contribution page into the list of **“Visible subpages”** to make it visible
- drop it in the position you want your contribution page to appear in the list of talking points
- click **“Ok”** to save the changes
- click **“Cancel”** if you don’t want the changes to apply



### How to change the order of contribution pages on the webpage?

- go to the **“Contributions”** section in the directory (Home>Theme>Theme Name>Contributions)
- you will see a list with all existing contribution pages
- click the **“Sort”** button on top of the directory
- the icons in front of the contribution pages in the directory change to a list symbol and the cursor changes to direction arrows when you hover over them
- simply drag the contribution pages in **“Visible subpages”** into the order you wish for
- click **“Ok”** to save the changes
- click **“Cancel”** if you don’t want the changes to apply




### How can I delete a contribution page?

- go to the **“Contributions”** section in the directory (Home>Theme>Theme Name>Contributions)
- you will see a list with all existing contribution pages
- in front of every contribution page in the list you see a little circle icon with a cross inside
- click the icon of the contribution page you wish to delete
- click **“Delete”** in the pop-up window to confirm the action
- click **“Cancel”** to not delete the contribution page

```
ATTENTION: Do not delete the “Contributions” section on your theme page
```
##Calendar


### How do I add an event to the calendar? 

```
INFO: The system of showing the calendar is based on text styling. There is no need to add extra pages. There is no opportunity to add files.
```

- find **“Calendar”** in the directory (Home>Theme>Theme Name>Calendar)
- simply edit the text in the text fields
- there are two columns
- you might have to copy and paste single events from one column to another to create a symmetric appearance of the calendar on the ISOCARP2015 web page
- hit “Save” to apply your changes

**TIP: To see how the Calendar has to be styled, please click [here](//)**

**TIP: To see how to preview your changes, please click [here](//)**

**TIP: To see how to stylise text, please click [here](//)**


### What is the structure of the calendar?

-

**TIP: To see how to stylise text, please click [here](//)**


##Who will be there?


### How does the “Who will be there?” section work?

```
INFO: The “Who will be there” page shows the names of all people who have signed up to participate or registered to stay updated for one specific theme. Since the registration process is controlled through an external service (MailChimp), the list of participants has to be downloaded from MailChimp and uploaded to the panel of the ISOCARP2015 web page. 
```

- the contacts and names on the **“Who will be there?”** page are imported from **MailChimp** by one of the theme administrators
- create and download a *.csv file* with the list of all a theme’s contacts from **MailChimp** to your computer

**TIP: To see how to create and download a *.csv file* from MailChimp, please go to the [handbook for external services](//), at page:…**

- go to **“Who will be there?”** in the directory (Home>Theme>Theme Name>Who will be there?)
- open the **“File”** section 
- click **“Upload a new file”** on the right top of the page
- upload the latest *.csv file* which was downloaded from **MailChimp**
- the **“Who will be there?”** page is now updated
- No further styling has to be done

##About

##Contact

##Sponsors

## Word Game

##Comments