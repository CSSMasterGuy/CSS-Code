<h1>YouTube</h1>
<br>
<p>BorderTweaks.css</p>

```
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
