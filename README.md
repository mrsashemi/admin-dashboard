# odin-admin-dashboard
Created as a part of the Odin Project curriculum

All images used are my own personal copyright @wizardsrobbingkids

**Introduction**

The goal of this project was to practice using intermediate level CSS and HTML to create an admin dashboard. More specifically, the goal is to practice CSS Grid. 

The example the odin project gave seemed to have somewhat of a social media theme, so I decided to create a chicken-theme'd parody of facebook called facebok!

**Functionality**

Displays as a simple dashboard that is split into 3 sections– the navigation sidebar, the search menu, and the activity dashboard. 

The navigation sidebar includes a header and two unordered lists displaying various links. The layout for the entire sidebar and each unordered list is made with grid. The various links include hover effects, and each icon is made creatively using CSS before and after pseudo elements. The chicken icon next to the Facebok header was also made with CSS! The icons are thus dynamic to the page itself, and no images were imported into this section.

The search menu includes two divs stacked on top of each other. Each div is layed out with grid. The icons in this section were also made using CSS except for the profile images, which is actually an NFT of myself. The search bar, buttons, and profile images include hover effects, and the bell notification icon has a hover animation. 

The activity dashboard displays a posts section, announcements, and a trending section. The entire section is layed out with grid, and the container holding the posts is also grid. The background is a chicken themed artwork that I created. Inset box shadow is used to create the illusion of depth. Each grid item has a frosted glass effect which upon hovering slowly clears up to show the background image underneath– I was conservative with this effect as I wanted the text to still be legible. Per the theme, the various icons were also made using CSS. The only images in this section are the trending users profile photos, which are 8bit, pokemon-style characters of me and my friends that I personally created.

**Process**

The process of creating this dashboard was fairly straight forward– it just took a while to get the styles to properly match my vision. My steps were as follows:

1) Create 3 distinct sections in HTML to form the basic layout.
2) Fill HTML with placeholder content.
3) CSS Grid to layout page properly.
4) Decide on a theme
5) Tackle styling each section one at a time starting with the navigation sidebar, then search menu, then activity dashboard. Focus on the theme first. 
    a) When styling start by formating text and desired fonts.
    b) Adjust positioning
    c) Create necessary icons with before and after pseudo elements
6) Once the theme is there, add additional styles for links and buttons using hover pseudo element.
7) Test in different window sizes
8) Add final adjustments

I found positioning with grid to be a breeze. The thing that gave me the most trouble however, was the overflow. I used viewport units on most all elements to make the page dynamic to different window sizes. However, the icons I made introduced overflow issues. No matter how I adjusted the sizes of the various divs, there always seemed to be a little bit of a scroll bar. I deduced that this was due to the absolutely-positioned icons I created. It would've been too much for me to go back, change the positioning, and then recreate the icons. I found that adding overflow:hidden to the body fixed this, but it created an issue with the dashboard portion where I was unable to scroll when the dashboard overflowed upon shrinking the window size. The solution here was to give the dashboard container a specific height and add overflow:auto. 

**Conclusion**

Overall, this project was very fun! It gave me many ideas for a future NFT project involving my artwork. I'm quite satisfied as to how it came back, and I do intent on expanding on this idea in the near future. 

