# Simple Polymer blog (based on Polymer App Toolbox - Starter Kit)
This is a simple and easy to fork blog template that I used for btopro.com. Using the Polymer App Toolbox Starter Kit option in polymer cli (`polymer init`), I then mixed in some elements to make it act as a simple blog and personal website. Take and do as you wish, there will be enhancements to the blog as I improve my own (this powers https://btopro.com).

## Remixing for your own use
Obviously you don't want btopro's blog so here's how to customize it without modifying any code (and then obviously you can always do that too).
- Install Polymer https://www.polymer-project.org/2.0/start/install-2-0
- Fork or download this repo
- run `bower install` to get it up and running
- if you want to play locally then do `polymer serve --open`
- Edit index.html and modify the `<my-blog>` tag to have your properties
- the `slot="links"` can be used to add custom links to the left menu panel
- To add / edit your postings you can find and modify anything in `/data/`.
- To add a thought to your blog, edit `/data/thoughts.json` and reference a markdown file in the `/data/thoughts/` directory

I'll be adding to this as I go so I don't think it'll have any point releases or anything but it'll at least be interesting as you'll be able to pick apart anything on the site with the raw files.
