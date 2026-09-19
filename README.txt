========================================
  THE MIDNIGHT JOURNAL
  Dark Academia Blog Template
========================================

Thank you for purchasing this template!
Below you will find everything you need to customize
and publish your own dark academia personal blog.


========================================
  FILES STRUCTURE
========================================

  dark-academia-template/
    index.html              <- Home page / blog entries
    archive.html            <- All entries list
    library.html            <- Reading list / bookshelf
    correspondence.html     <- Contact page
    style.css               <- All styles (colors, fonts, layout)
    profile.jpg             <- Sample profile image (replace with yours)
    statue.jpg              <- Sample post image (replace with yours)
    README.txt              <- This file


========================================
  GETTING STARTED
========================================

  1. Open any .html file in a text editor
     (VS Code, Notepad++, Sublime Text, or even Notepad)
  2. Replace the sample text with your own content
  3. Replace sample images with your own photos
  4. Save the file and open it in your browser to preview
  5. Upload all files to your hosting when ready


========================================
  HOW TO CHANGE TEXT
========================================

  - Open the HTML file you want to edit
  - Search for the text you want to replace
  - Change the title, dates, blog content, etc.
  - Save the file and refresh your browser

  Key text to replace:
    "The Midnight Journal"   -> Your blog name
    "MEMENTO MORI..."        -> Your tagline/quote
    Blog post titles          -> Your own titles
    Blog post content         -> Your own writing
    "1895"                    -> Your year


========================================
  HOW TO CHANGE IMAGES
========================================

  Profile picture:
    - Replace profile.jpg with your own photo
    - Keep the same filename, or update src in index.html
    - Square images (1:1) work best
    - The CSS applies a vintage filter automatically

  Blog post images:
    - Replace statue.jpg with your own photo
    - Or add new images and update src in the HTML
    - Any size works (images auto-resize to full width)
    - The CSS makes images darker/moodier automatically
    - Hover over an image to see it at full brightness

  To add an image to a blog post:
    <div class="post-image">
        <img src="your-photo.jpg" alt="Description">
        <p class="caption">"Your caption here."</p>
    </div>


========================================
  HOW TO CHANGE COLORS
========================================

  - Open style.css
  - Find the :root section at the very top
  - Replace the color codes with your own colors
  - Save and refresh your browser

  Current colors:
    --bg-color:    #1a1a1a    (background — soft black)
    --paper-color: #2c2c2c    (content box — dark gray)
    --text-main:   #d4c5b3    (main text — old cream)
    --text-dim:    #8a7d6e    (dates/subtle — muted brown)
    --accent:      #6b4e3d    (borders/links — burnt brown)

  Dark Academia color suggestions:
    Deep burgundy:   #6b1d2a
    Forest green:    #2d4a3e
    Midnight blue:   #1a2744
    Antique gold:    #b8943e
    Dusty rose:      #8a5a6a


========================================
  HOW TO ADD A BLOG POST
========================================

  - Open index.html
  - Copy an existing <article class="post"> block
  - Paste it below the last post
  - Change the date, title, content, and tags
  - Optionally add a post-image block

  Template for a new post:

    <article class="post">
        <span class="date">November 5, 23:30</span>
        <h2>Your Post Title</h2>

        <div class="post-image">
            <img src="your-image.jpg" alt="Description">
            <p class="caption">"Your caption."</p>
        </div>

        <div class="content">
            <p>Your text here...</p>
        </div>
        <div class="tags">#YourTag #AnotherTag</div>
    </article>


========================================
  HOW TO CHANGE PROFILE IMAGE SHAPE
========================================

  - Open style.css
  - Find .profile-img
  - Change border-radius:

    border-radius: 50%;     Circle (default)
    border-radius: 0%;      Square
    border-radius: 10px;    Rounded square


========================================
  HOW TO UPLOAD TO NEOCITIES
========================================

  1. Go to neocities.org and create a free account
  2. Log in and go to your Dashboard
  3. Upload all HTML files
  4. Upload style.css
  5. Upload your image files
  6. Make sure index.html is in the main/root folder
  7. Visit your site at yourname.neocities.org

  Other free hosting options:
    - Netlify (netlify.com)
    - GitHub Pages (pages.github.com)
    - Vercel (vercel.com)
    - Any static file hosting


========================================
  DESIGN ELEMENTS
========================================

  This template uses a Dark Academia / literary aesthetic:
    - Monospace typewriter font (Courier New)
    - Serif headings (Georgia, italic)
    - Vintage image filters (sepia, grayscale, dim)
    - Hover-to-reveal full brightness images
    - Accent left-border on content blocks
    - Minimalist layout with vertical rules
    - Muted earth-tone color palette
    - Old parchment text color

  CSS classes available:
    .profile-img   - Circular profile photo with vintage filter
    .post-image    - Full-width image container
    .caption       - Italic caption under images
    .content       - Text block with accent left-border
    .date          - Muted date/timestamp
    .tags          - Hashtag labels
    .subtitle      - Header tagline


========================================
  IMPORTANT NOTES
========================================

  - The contact page (correspondence.html) is static.
    Replace the sample email/social links with your own.

  - Keep all files in the same folder unless you know
    how to update file paths.

  - Do not rename style.css unless you also update
    the link in every HTML file.

  - This template uses system fonts only (Courier New,
    Georgia) — no external font loading required.
    Works offline and loads instantly.


========================================
  DISCLAIMER
========================================

  This is a static HTML website template.
  It does not include WordPress, hosting, domain setup,
  backend forms, or email automation.
  Basic HTML editing is required.


========================================
  LICENSE
========================================

  Personal use. One site per purchase.
  Do not redistribute or resell the template files.


Written by candlelight. Enjoy your corner of the dark web.
