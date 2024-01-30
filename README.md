# Nirvana Rock Band Website
 Nirvana Rock Band's website features their discography, upcoming events, and band members.

Section - Hero Section

Functionality:
    Background video: Automatically plays a muted video in the background of the hero section.
    Navigation menu: Provides links to different sections of the page, likely using in-page scrolling.
    Menu toggle: Allows hiding and showing the navigation menu, 
    Logo: Displays the website's logo prominently in the hero section, both as a smaller version in the navigation and a larger version within the hero itself.

Structure:
    section with class "hero" and id "home": This defines a main section of the page, likely the hero or header area.
    video with various attributes: This creates a background video that plays automatically, loops, is muted, and plays inline (not fullscreen).
    nav: This creates the navigation menu for the page.
    div with class "logo-hero": This holds a larger version of the logo within the hero section.

Elements:
    video: Embeds a video for a background visual.
    source: Specifies the video source file.
    nav: Containers for navigation links.
    div: Generic containers for grouping elements.
    img: Displays images (the logo in this case).
    input (checkbox): Creates a checkbox for menu toggling.
    label: Labels the checkbox for accessibility.
    svg: Defines an SVG icon for the menu toggle.
    ul: Unordered list for the navigation links.
    li: List items for individual links.
    a: Anchor tags for creating hyperlinks.

Section - discography-section

Structure:
    section with id "discography-section": This is the main container for the entire discography section.
    h1: Displays the heading "Our Discography".
    h3: Subheading that says "Studio Albums".
    div with class "row": Creates a row layout for displaying album cards.
    Three div with class "column": Each column holds a single album card.
    div with class "card": Defines the individual album card container.
    img: Displays the album cover image.
    div with class "container": Holds the album information within the card.
    h2: Shows the album title.
    Two p with class "title": Display release date and label information.
    div with class "albumButton-div": Holds the "View Tracklist" button.
    a with href attribute: Creates a link to the detailed tracklist page.
    button with class "album-button": Displays the "View Tracklist" text.

Functionality:
    Displays three album cards in a row layout.
    Each card features an album cover, title, release date, label, and a "View Tracklist" button.
    Clicking the button likely leads to a dedicated page for each album with further details and tracklist.

Section - biography-section

Section ID and Headings:
    <section id="biography-section">: This defines the main container for the entire biography section.
    <h2>Biography</h2>: Displays the main heading "Biography".
    <h3>About Us</h3>: This is a subheading introducing the band.
    Band Image:
    <img src="assets/nirvana editorial.jpg" alt="Band image" class="biography-img" />: This displays an image of the band with appropriate alt text and a class for styling.
    Biography Text:
    <div class="biography-text">: This container holds the main text content of the biography.
    Paragraphs describing the band's formation, breakthrough, cultural impact, later years, and legacy.
    Each paragraph includes relevant details and historical context.
    Additional Band Image:
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRU5U8knHWUjoNF7HxBjg2TktPzeb4xeoO69y1UjYZSGfnKKBRt" alt="Band image" class="biography-img" />: This adds another image of the band, likely at a different stage of their career, further enriching the visual presentation.

Overall Structure and Content:
    The code effectively presents a comprehensive biography of Nirvana, covering their origins, rise to fame, cultural impact, and lasting legacy. The use of images alongside the text enhances the storytelling and engagement for the reader.

Section - band-members

Structure and Headings:
    section with id "band-members": This is the main container for the entire section.
    h2 and h3: Display the main heading "BAND MEMBERS" and the subheading "NIRVANA BAND MEMBERS".

Timeline Image:
img with class "timeline-img": Shows a timeline image, likely illustrating the band's history and member tenures.

Band Member Cards:
    div with class "band-members": This container holds the individual member cards.
    div with class "row": Creates a row layout to display the cards horizontally.
    Three div with class "column": Each column holds a single card.
    div with class "card": Defines the individual member card container.
    img: Displays the member's photo (note: missing for Krist Novoselic).
    div with class "container": Holds the member's information within the card.
    h2: Displays the member's name.
    p with class "title": Shows their roles (e.g., lead vocals, guitar).
    p with class "title": Indicates their years with the band.

Functionality:
    Presents a timeline of the band's history.
    Showcases individual members in a visually appealing card format.
    Provides key information about each member's role and tenure.

Section - upcoming-events

Structure and Headings:
    section with id "upcoming-events": This is the main container for the entire section.
    h2 and h3: Display the main heading "UPCOMING EVENTS" and the subheading "nirvana uk tour dates 2024 - 2025".
Event Table:
    div with class "table-div": This container holds the event table.
    table: Creates the table structure to display the events.
    tr with th: Defines the table header row with column names: "Date", "Location", and "Tickets".

    Multiple tr with td: Each row represents a single event, with cells for the date, location, and ticket button.

    td with date and location: Display the event's date and venue.
    td with ticket button: Contains a link to the ticket purchase page, embedded within a button for user interaction.

Functionality:
    Presents a clear and organized list of upcoming events.
    Provides essential information about each event, including date, location, and ticket availability.
    Offers direct links to ticket purchase pages, allowing users to easily buy tickets.


Section - footer

The code starts with a <section> element with the id attribute set to "footer-section". This is a semantic element used to define a section of the webpage that contains the footer content.

Inside the <section> element, there is a <footer> element. The <footer> element represents the footer of the webpage and is used to contain information such as copyright notices, authorship details, and other relevant information about the webpage.

Within the <footer> element, there are two <p> elements. The first <p> element has the id attribute set to "copyright" and contains the copyright notice:


The second <p> element has the id attribute set to "author-text" and contains information about the developers and designers of the webpage:

Overall, this code creates a semantic section for the footer of the webpage. It includes a <footer> element that contains relevant information such as the copyright notice and details about the developers and designers of the webpage. The use of semantic elements and attributes helps structure and style the footer section effectively.


