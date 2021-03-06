https://lisonallie.github.io/Allison-trap/


# Framework

This is my own framework. I kept it simple because I am new to all of the elements of this project but I am learning more every day. I added 6 elements in addition to having Buttons, Grid layout, and Form design:
1. Navigation Bar
2. Card
3. Header
4. Blockquote
5. Code block
6. Footer

### Navbar

This navigation bar has a professional and sleek design with a slate-grey-blue background color and white text that can be used in many settings. I chose to place the **LOGO** in the center so it is the main focal point of each navbar. The default navbar design today normally has the logo in the top left and menu options to the right as a default. I wanted to create a symmetrical design and try something different.

### Card

My card is a simple example of a box you can fill with anything you like. I've placed one of my buttons inside to show this effect. It has a nice thin border to indicate its' thresholds which can be changed depending on your choice of grid columns.

### Header

I wanted to create some unique-looking styles for headers that would stand out. I tried to provide different styles and emphasis for different users.

### Blockquote

I wanted to design a blockquote that would easily stand out from the page. In one of my earlier assignments when I was learning all the elements still, I created a blockquote with a border and the instructions said that it looked ~~ugly~~bad in the initial placement of CSS and told us how to change it to make it look nice. Therefore, I thought "Why not make the nice-looking quote the default?".

### Code Block

Every website has their own aesthetic for how they want a code block to stand out. I kept the default font because it gets the message across as-is. I did however decide to darken the background of the code because the default is barely noticeable. I gave it a nice dark color in unison with my navbar design.

### Footer

The footer design of my framework is made to let whichever company it concerns do more. Usually a footer is all links to social media or other platforms. The footer is the last content a user sees when they finish scrolling a page. I thought it would be nice if the company had space to put a message for the visitors to their website. The links, which are a given in footers, are placed to the sides where they are noticeable but not overbearing, and the company has space to write a 'farewell' or whatever they want in the remaining space.


## How to Use My Framework

### Grid System

Using this system is fairly straightforward as I have a 6x6 column setup with unlimited row choice. I eliminated the center section because it didn't end up condusive to the design. So I tried something different and made the grid simple.

`.grid-row` This defines where a grid row should start. THis grid creates 12 columns, the height of the rows adapt to the content within, and they have a padding of 3px.
`.grid-right` This defines where content in a row should be placed. `.grid-right` spans 6 columns starting from the 7th column of your row and is center-aligned.
`.grid-left` spans 6 columns starting from the left of your row.
`.grid-all` uses the entire width of the grid.

### Navbar

The navbar places your logo in the middle and links to content on either side, maintaining a symmetrical and professional style.

### Buttons

`.btn-stop` Normal: rounded circular button with red 2px border and transparent background. 
Hover: red color of all borders and text becomes scarlet red (darker).
`.btn-go` Normal: slightly rounded corners, green background, light-weight white text. 
Hover: small grey drop shadow to the right and bold font.
`.btn-slow` Normal: square, dark blue border, yellow background, dark blue text. 
Hover: padding grows from 6x15 to 10x20.
`.btn-small` Normal: very small text button, light blue border, dark blue text, transparent background. 
Hover: font color becomes dark blue.
`.btn-medium` Normal: circular button, lavender background, muted pink text. 
Hover: background becomes darker purple and text becomes a slightly lighter pink.
`.btn-large` Normal: rounded corners, orange border, light orange background, off-white text. 
Hover: text color changes to yellow and background becomes darker shade of orange.

### Card

`.card` Makes a card with a max height of 250px that adjusts to the size of the column-area. The classes `.card-category` and `.card-description` indicate the head area of the card and the content of the card, respectively. All content is centered.

### Form

`.outside` Indicates the dimensions of the input form box. There are two input fields for the standard Username and Password and a Submit and Nevermind button. Upon clicking, the border of the input fields becomes dashed.

### Headers

Here the framework offers a variety of different effects as default headers. h1 provides a periwinkle background with white text. h2 the text is changed to Artifika. h3 changes the font color to a light green. h4 has a box shadow to the right and a slight blur. h5 sets the text in small caps. h6 sets a grey background with pink text.

### Blockquote

Blockquote places a colored 2px border on the left and bottom with a padding of 10px.

### Code

Keeps the default font and sets a dark grey background.

### Footer

The links, which are a given in footers, are placed to the sides where they are noticeable but not overbearing, and the company has space to write a 'farewell' or whatever they want in the remaining space. There is a default background of seagreen. The text color is white.
