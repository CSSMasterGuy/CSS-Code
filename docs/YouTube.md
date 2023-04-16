<h1>YouTube</h1>
<p>BorderTweaks.css</p>

```css
/* To use this on YouTube, install Stylus in your browser then head to YouTube and click 'Write Style For...' in the Stylus extension,
then copy and paste the desired content.
Removes the border around the 'Login' button */

.yt-spec-button-shape-next--size-m.yt-spec-button-shape-next--outline {
    
    border: none;
    
}

/* Removes the border (and subsequently the rounded edges) of playlists */

ytd-playlist-panel-renderer[modern-panels]:not([within-miniplayer]) #container.ytd-playlist-panel-renderer {
    
    border: none;
    
}

/* Removes the background of video descriptions. */

ytd-watch-metadata[modern-metapanel] #description.ytd-watch-metadata {
    
    border: none; /* Doesn't work for some reason */
    background: none;
    
}
```
<br>
<p>NewSearchBar.css</p>

```css

/* To use this on YouTube, install Stylus in your browser then head to YouTube and click 'Write Style For...' in the Stylus extension,
then copy and paste the desired content*/

/* Searchbox stuff */

#container.style-scope.ytd-searchbox {
    
    border: 0px;
    border-radius: 10px 0 0 10px;
    background-color: hsl(0, 0%, 13.3%);
    
    
}

ytd-searchbox[has-focus] #container.ytd-searchbox {
    
    background-color: hsl(0, 0%, 9%); /* Background color of searchbox when selected */
    border: none;
    
}

#search-icon-legacy.ytd-searchbox {
    
    border-radius: 0 10px 10px 0;
    
}

/* Changing the font of the Search box */

#search-input.ytd-searchbox-spt input {
    
    font-family: 'YouTube Sans', sans-serif; /* Change this to whatever font you want (keep font within quote marks) */
    font-weight: 600;
    font-size: 18px;
    
    
}

#search-icon-legacy.style-scope.ytd-searchbox {
    
    border: 0px;
    
}

/* Honestly the search dropdown is a mess of <div> and <div> over and over. I'll try to provide an explanation for each. */

.sbsb_b {
    
    font-family: 'YouTube Sans', sans-serif; /* Change this to change the font of the text on the search dropdown */
    font-weight: 600;
    background-color: hsl(0, 0%, 9%); /* Change this to change the background color of the dropdown */
    border-color: hsl(0, 0%, 9%); /* Border color of the dropdown, generally works best if you leave it the same as the background */
    
}

.sbsb_a {
    
    background-color: hsl(0, 0%, 9%); /* Background color of results when hovered over */
    border-color: hsl(0, 0%, 9%);
    
}

.sbsb_c.gsfs.sbsb_d {
    
    color: white; /* don't ask what this is, i forget */
    background-color: hsl(0, 0%, 13%);
    
}

.sbqs_c {
    
    color: white;
    
}

.sbdd_b {
    
    border-color: #222;
    
}

.sbfl_b {
    
    background-color: hsl(0, 0%, 9%);
    
}

/* Disables the search clear button, as it overlaps with the main search button. Desktop users (whom this is intended for) should have no problem using the text cursor to select all of it and delete it. */

.yt-spec-button-shape-next.yt-spec-button-shape-next--text.yt-spec-button-shape-next--mono.yt-spec-button-shape-next--size-m.yt-spec-button-shape-next--icon-only-default {
    
    display: none; 
    
}

```
<br>
<p>NoFilters.css</p>

```css

/* To use this on YouTube, install Stylus in your browser then head to YouTube and click 'Write Style For...' in the Stylus extension,
then copy and paste the desired content
Below code disables the area above the videos in search (aka 'Filters' button and 'About these results' link). It removes the ability to filter videos. 
If you do not use filters and wish to remove them, use this block of code.
*/

#container.style-scope.ytd-search-sub-menu-renderer {
    
    display: none;
    
}

```
<br>
<p>NoShorts.css</p>

```css

/* To use this on YouTube, install Stylus in your browser then head to YouTube and click 'Write Style For...' in the Stylus extension,
then copy and paste the desired content*/

/* Disables YouTube Shorts on the home page */

#content.style-scope.ytd-rich-section-renderer {
    
    display: none; /* If you want shorts to remain on the home page, delete this line. */
    
}

/* Disables YouTube Shorts section on the Search page [DOES NOT REMOVE SHORTS LISTED LIKE VIDEOS] */

ytd-reel-shelf-renderer.style-scope.ytd-item-section-renderer {
    
    display: none;

}

```
<br>
<p>Other.css</p>

```css

/* To use this on YouTube, install Stylus in your browser then head to YouTube and click 'Write Style For...' in the Stylus extension,
then copy and paste the desired content*/

/* Disables YouTube Shorts on the home page */

#content.style-scope.ytd-rich-section-renderer {
    
    display: none; /* If you want shorts to remain on the home page, delete this line. */
    
}

/* Disables YouTube Shorts section on the Search page [DOES NOT REMOVE SHORTS LISTED LIKE VIDEOS] */

ytd-reel-shelf-renderer.style-scope.ytd-item-section-renderer {
    
    display: none;

}

```
