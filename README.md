# r3dkoiarts
Portfolio Website (University Assignment)


Images
https://thenounproject.com/icon/dark-mode-toggle-6747810/

CSS Guides Used
https://www.w3schools.com/howto/howto_css_flip_card.asp
https://www.w3schools.com/html/html5_video.asp
https://www.w3schools.com/css/css3_fonts.asp
https://www.w3schools.com/howto/howto_css_fixed_footer.asp
https://freefrontend.com/css-theme-switches/
https://imabi.org/ 
https://www.w3schools.com/css/css3_gradients.asp

ACCESSIBILITY TOOLS USED
https://webaim.org/resources/contrastchecker/
https://www.w3.org/TR/WCAG22/

BRAINSTORMING SITE LAYOUT
https://app.milanote.com/1Wt8jS12PQJI2V?p=ItmVtxrK2mR

FONTS
https://freefonts.co/fonts/altero-regular
https://fonts.google.com/specimen/Questrial?preview.script=Latn

GALLERY CHANGES (important)
1. Gallery cards were originally hardcoded directly in gallery.html as static HTML 
required its own hand-written <div class="card"> block. This was refactored to a data-driven approach as specified in project brief. 

2. Gallery data was initially structured as gallery.json and loaded via fetch() but fetch() is blocked by browsers on local file:// URLs, so when the site's extracted from ZIP file it would break when reviewing locally.
3. The data was therefore moved to gallery-data.js as a plain JavaScript array.


AI USAGE
Claude (claude-sonnet-4-6) was used for AI-assisted editing and refinement of this project's CSS, HTML, and JavaScript outputs. This included refining layout and responsiveness, correcting selector bugs, and improving code structure and comments. All creative decisions, content, and artwork remain the author's own.

Anthropic. (2026). Claude (claude-sonnet-4-6) [Large language model]. https://claude.ai/
