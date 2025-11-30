# Academic Website

This repository contains source code of [my academic website](https://mkhangg.com/) using Jekyll as a static website generator. Feel free to clone this code for your personal use!


## Template from Khang Nguyen
Thanks for the great template and here is what I have done to make it my own! :)

[Orginal Reference Repo](https://github.com/mkhangg/academic-website/tree/main)
[Actual Website](https://mkhangg.com/)


## Test Run

```
gem install bundler jekyll 
```


## File Structure**

```
.
├───assets                      # folder including your images, files, etc
├───js                  
    └───scripts.js              # the JS file for functional buttons
├───styles              
    └───styles.css              # the CSS file for colors and stuffs 
├───_data               
    ├───about.yaml              # data file for About section
    ├───footer.yaml             # data file for Footer section
    ├───gallery.yaml            # data file for Gallery section
    ├───outreach.yaml           # data file for Outreach section
    └───research.yaml           # data file for Research section
├───_layouts      
    └───main.html               # the HTML layout for the webpage 
├───_libs      
    ├───footer_widget.html      # html file for Footer widget
    ├───gallery_widget.html     # html file for Gallery widget
    ├───outreach_widget.html    # html file for Outreach widget
    └───research_widget.html    # html file for Research widget     
├───_sections           
    ├───about.html              # html file for About section
    ├───footer.html             # html file for Footer section
    ├───gallery.html            # html file for Gallery section
    ├───outreach.html           # html file for Outreach section
    └───research.html           # html file for Research section
├───_site                       # all contents for deployable version here!
    ├───assets
    ├───js
    ├───styles
    └───index.html              # the generated HTML file
├───index.md                    # markdown file that uses main.html as layout
└───_config.yml                 # information for webpage title and favicon
```