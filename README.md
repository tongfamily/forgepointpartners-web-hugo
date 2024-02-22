# forgepointpartners-web-hugo
d 

Forgepoint Partners Web Site with @richtong's infe new stack including🀄

1. Hugo. https://gohugo.io/ site generator
2. Netlify. https://www.netlify.com/ site hosting (free for public repos)
3. Cloudinary. https://cloudinary.com/ cloud storage (free for small projects)
4. Themes. https://themes.gohugo.io/ themes

## Installation

You should first install hugo on your local machine with `brew install hugo`
and then create a new repository with  and then in the ./themes you will put in
the theme as a submodule (do not clone it!) so create a new site with `hugo new site .`

You will need the `--force` since this README is here

This makes it easy to use a git submodule as a theme and to switch and update
as needed. So `cd themes` and then git submodule add a theme from the Themes
repository.

And then copy up the template for the ./exampleSite to the root.

## Some Good Themes to Trying

While there are not as many themes as WordPress, there are some good themes to
try. So here's a list based on [Hugo Themes](https://themes.gohugo.io/) which
is sorted by GitHub star order which is convenient:

1. PaperMod. https://themes.gohugo.io/themes/hugo-papermod/ This is a very
   bare-bones sitte with no graphics, it's a popular one with 7616 GitHub Stars
1. [Hugo Blow Tailwind](https://themes.gohugo.io/hugo-blow-tailwind/) This is a
   widget based system so really nice and probably waht I will use.
1. [Stack](https://themes.gohugo.io/themes/hugo-theme-stack/) This is a card
   syste so good for blogs where you want a picture above the post. This is
   very much like what the current [Tongfamily](https://tongfamily.com/) has.
1. Academic. https://themes.gohugo.io/themes/theme-academic-cv/ This is the first theme that I
   tried, it is great for CVs and has papers, a blog and various elements. Not
   so great for company sites. It's popoular with 3261 stars on GitHub.
1. Tranquilpeak. https://themes.gohugo.io/themes/hugo-tranquilpeak-theme/  This
   has a nice responsive design, way prettier than Academic
1. [Docsy](https://themes.gohugo.io/themes/docsy/) This is designed for
   documentation sites .


Both Academic and Hugo Blow use the same Hugo Blox system and it seems to work
well. There are [Templates within this system](https://hugoblox.com/templates/)
for nearly every use.
