# Hashwanth Gogineni
I am a person who is upbeat in all aspects of life. I enjoy doing, seeing, and experiencing new things. I enjoy reading and writing; I enjoy thinking and dreaming; I enjoy talking and listening.

Click here to view a picture of mine
![Its Hashwanth Gogineni](hashwanth_gogineni.jpg)

***

## Countries I recommend that you visit

This table contains the countries that I enjoy visiting and would recommend to others.

| Country | Reason to travel | Days to spend	|
| ----------- | ----------- | ----------- |
|  Italy | beautiful scenery, a storied past, and a thriving culture, but also for the wonderful cuisine of Italy  | 5 |
| The Maldives | gorgeous beaches, a thriving culture, a lot of greenery, and interesting landmarks | 4 |
| United Arab Emirates | Beautiful, gleaming skyscrapers, cutting-edge structures, as well as stunning beaches and sand dunes | 7 | 

***

## Laughable quotes

> I want my children to have all the things I couldn't afford. Then I want to move in with them — *Phyllis Diller*

> My advice to you is get married: If you find a good wife you’ll be happy; if not, you’ll become a philosopher - *Socrates*

***

## Code Fencing 

>[Programmatically Lighten or Darken a hex color (or rgb, and blend colors)](https://stackoverflow.com/questions/5560248/programmatically-lighten-or-darken-a-hex-color-or-rgb-and-blend-colors)

~~~
function LightenDarkenColor(col, amt) {
  
    var usePound = false;
  
    if (col[0] == "#") {
        col = col.slice(1);
        usePound = true;
    }
 
    var num = parseInt(col,16);
 
    var r = (num >> 16) + amt;
 
    if (r > 255) r = 255;
    else if  (r < 0) r = 0;
 
    var b = ((num >> 8) & 0x00FF) + amt;
 
    if (b > 255) b = 255;
    else if  (b < 0) b = 0;
 
    var g = (num & 0x0000FF) + amt;
 
    if (g > 255) g = 255;
    else if (g < 0) g = 0;
 
    return (usePound?"#":"") + (g | (b << 8) | (r << 16)).toString(16);
  
}
~~~

[Lighten / Darken Color using Javascript](https://css-tricks.com/snippets/javascript/lighten-darken-color/)