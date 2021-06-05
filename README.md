# LIFEGUARD BEACHES!

This site hopes to be a hub of information for lifeguard beaches located in South East England. The primary focus will be to provide weather and beach locations with lifeguards on duty. Secondary focus will be on marine safety equipment for watersports; to showcase public beach events about lifesaving such as public demonstrations, safety seminars, and competitions. The site is targeted at the general public: young people wishing to compete or become a lifesaver, parents / adults wanting to enjoy their time on the beach with family in relative safety, marine sports enthusiasts, and lifesavers. 

![Lifebuoy](https://c.pxhere.com/photos/2f/99/lifeguard_summer_beach_sand_sea-224.jpg!d)

## Features

The features are set out in a way to display consumable data to the user in small bite-sized pieces.

### Existing Features

+ __Hero Image__

    + Spanning 4 pages is a "Hero" image depicting a beach with a lifesaving device.
    + The image will make it clear to the purpose of the site

+ __Navigation Bar__

    + Spanning 4 pages is a set of 4 navigation buttons on a mobile-first responsive navigation bar.
    + The buttons are be styled in such a way to make it easily distinguishable which page you are on and to provide context to the content on the page below.
    + The buttons have an on-hover event with radial shadow
    + The navigation buttons are large and coloured separately to make them easy to select on mobile devices.
    + Use of device navigation is unnecessary as the navigation is intuitive and easy to understand.

+ __Home / Landing Page__

    + __Weather Section__

        + Two mobile responsive panes of consumable weather information for the user.
        + The panes display the weather for today versus tomorrow.
        + Information will be on Tides, UV Index, Wind, Temperatures, and Surf Conditions
        + Useful to decide if tomorrow is better to attend the beach for activities.

    + __Maps Section__

        + A mobile section with an embedded map - defaulted to a search on beaches in SE England with Lifeguards on duty
        + Useful for "on the fly" quick view to get an idea of where to go for some time on the beach or for marine watersports

+ __Safety Equipment Page__

    + A mobile-responsive list of safety equipment for the beach and other marine sports
    + Examples include high-vis swimming buoys, helmets, harnesses, gloves, lifesaving buoys, etc.
    + Useful for general information to make encourage users to be informed
    + Not a sales page!

+ __Events & Activities Page__

    + A list of upcoming events and activities - focus on beaches and marine sports and tageted at all ages
    + Will be updated based on date and events

+ __Contact Page__

    + A section to for general enquiries
    + Useful for question about the site and for further information

+ __Footer__

    + Spanning 4 pages is the footer section
    + Links to external resources (ICE - In Case of Emergency contact information)
    + Links to social media to encourage interaction with the events and available services

### Features Left to Implement

## Design Choices

+ Core colour: #e50000 [Lifeguard Red](https://icolorpalette.com/color/lifeguard-red)
+ Palette selection based on core colour: [Matching Gradient](https://mycolor.space/?hex=%23E50000&sub=1)
    + #E50000 #F70068 #D217BF #5A66FE #0088FF #0097E8
+ CSS Color Gradient: [ColorSpace 3-Color Gradient](https://mycolor.space/gradient3) `background-image: linear-gradient(to right top, #e50000, #f10031, #f60054, #f50075, #ec0095, #e020ad, #ce36c5, #b549da, #9a5eea, #7b6ff5, #537dfc, #0088ff);`
+ Button CSS hover events: [cdjns hover.css](https://cdnjs.com/libraries/hover.css) | [IanLunn / Hover](https://github.com/IanLunn/Hover/blob/master/css/hover.css) /* Shadow Radial */
+ Layout: [Bootstrap 5.0 Grid System](https://getbootstrap.com/docs/5.0/layout/grid/)
+ Font pairing: [2020 Most Popular Fonts](https://govisually.com/blog/2020s-top-20-google-font-pairs-for-your-next-project/)
    + Montserrat | Oswald - "The Monsterrat font was designed in agreement with the urban typography of the 20th century. The generous spacing between the letters is one of the striking characteristics of this font and makes it so convenient to follow. On the other hand, the Oswald font is known for its narrow appearance in spacing and letters. Together, they make an ideal impact in the mind of viewers."
+ Able to have responsive map and weather together. This means ICE information will move to left side of map and social media will remain the footer.

## Testing

### Validator Testing 

HTML - green
CSS - green

### Unfixed Bugs

Coming soon...

## Deployment

Coming soon...

## Credits

### Reference Sites

+ [GitHub](https://github.com/)
+ [GitPod](https://gitpod.io/)
+ [Bootstrap](https://getbootstrap.com/)
+ [Font Awesome](https://fontawesome.com/)
+ [Google Fonts](https://fonts.google.com/)
+ [iColorPalette](https://icolorpalette.com/)
+ [ColorSpace](https://mycolor.space/)
+ [cdjns](https://cdnjs.com/)
+ [Map & Weather](https://www.windy.com/-Embed-widget-on-page/widgets?50.870,-1.309,5)

### Content

+ README file help
    + [Code Institute README Template](https://github.com/Code-Institute-Solutions/readme-template)
    + [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
    + [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

### Media

+ The images / photos used on all the pages are from the following Open-Source sites and are part of the Creative Commons Licensing.
    + [PX Here site](https://pxhere.com/) - "Free of copyrights under CC0. Do whatever you want."

### Wireframes
+ ![Home Page](https://github.com/greggo58/CI-MS1-LifeguardBeaches/blob/master/assets/images/Lifeguard%20Static%20Site%20Home%20Page.png)
+ ![Safety Equipment Page](https://github.com/greggo58/CI-MS1-LifeguardBeaches/blob/master/assets/images/Lifeguard%20Static%20Site%20Safety%20Equipment%20Page.png)
+ ![Events & Activities Page](https://github.com/greggo58/CI-MS1-LifeguardBeaches/blob/master/assets/images/Lifeguard%20Static%20Site%20Events%20Page.png)
+ ![Contact Page](https://github.com/greggo58/CI-MS1-LifeguardBeaches/blob/master/assets/images/Lifeguard%20Static%20Site%20Emergency%20Contact%20Page.png)