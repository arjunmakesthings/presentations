in the last 7 years, i've given a few talks (see a list [here](https://arjunmakesthings.github.io/cv.html)).

now, i'm tired of making (and storing) large-size keynote presentations, and then attempting to retrieve similar content for future-presentations. i've also grown fond of a visual-tyle that i frequent, to document & present my work over the web or otherwise. 

so, this repository will contain all of my future presentations, which are now formatted using the following: 

- presentations are 'written' in [markdown](https://en.wikipedia.org/wiki/Markdown). 
- [remark.js](https://github.com/gnab/remark) converts the markdown file into an 'html' presentation. i found remark on [this](https://gist.github.com/johnloy/27dd124ad40e210e91c70dd1c24ac8c8) list.
- global-styles are applied via ../assets/scripts/style.css. most of the attributes are borrowed from [my website's css](https://github.com/arjunmakesthings/arjunmakesthings.github.io/blob/main/style.css).
- images are converted into `.webp`. short-videos are stored as 720p, 30fps files transcoded using [handbrake](https://handbrake.fr). both are stored in presentation-specific folders in ../assets/media.
- if a piece of media has to be reused in a presentation, it just references the file-path on this github repository. 
- all shared presentations (i.e `.html` file used to deliver my presentation) are stored in ../slides.
- diagrams, flowcharts, circuits are either sketched on my ipad or made using [google-typograms](https://google.github.io/typograms/).

---

### acknowledgements: 
sangarshanan's [talks repository](https://github.com/Sangarshanan/talks) for the inspiration, and ole petter bang's work on [remark.js](https://github.com/gnab/remark).