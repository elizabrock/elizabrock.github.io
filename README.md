elizabrock.com
--------------

## Development Setup

This site is generated by [Jekyll](http://jekyllrb.com/). [Ruby](https://www.ruby-lang.org) is required to install/run Jekyll.

1. `bundle install` to install development dependencies.

You may need to `gem install bundler` if the `bundle` command is unavailable.

## Running Locally

Run `jekyll serve --watch` in the root of the project.

## Spell Checking

1. `brew install aspell`
2. `for f in **/*.md; do aspell check $f; done`
3. `for f in *.html; do aspell check $f; done`
4. `for f in **/*.html; do aspell check $f; done`

## Deploying

1. All code on master is automatically deployed by GitHub once it has been pushed to GitHub.

## 2020 Personal Site Update Checklist

1. ✔ Update dependencies
2. ✔ Set up SEO-friendly redirect from elizabrock.com to elizamarcum.com
3. ✔ Set up GitHub pages to use elizamarcum.com instead of elizabrock.com
5. ✔ Update markup (\_includes, \_layouts, \*.md)
6. ✔ Add Jekyll SEO plugin
7. ✔ Add Jekyll sitemap
8. ✔ Set up Google analytics snippet
9. ✔ Update content
  1. ✔ Headshot
  2. ✔ Bio
  3. ✔ Skill list
  4. ✔ Resume
6. ✔ Styling, from scratch with new color scheme
  * ✔ General
  * ✔ Don't forget about the 404 page
7. ✔ Perhaps a little rewriting of git history before moving this branch to master
8. ✔ Run spell check
10. ✔ Move Primitive to the vendor folder
9. ✔  Check on TO-DOs in the code
10. Eliminate unused CSS variables
11. Remove commented out CSS
12. Update updated\ats so that the sitemap will be accurate
12. Relaunch personal site (by pushing this branch to master)
4. Update personal URL on:
  * LinkedIn
  * GitHub
  * Twitter
13. Refine the merely acceptable status of the design implementation:
  *  Have navigation mark the current section
14. Set up SEO-friendly redirect from elizabrocksoftware.com to elizamarcum.com
15. Use [jekyll-redirect-from](https://rubygems.org/gems/jekyll-redirect-from) to:
  * rename /social to /contact
  * set up canonical URLs for the old EBS pages
16. Cancel Squarespace for elizabrocksoftware.com

## Future Improvements

1. More Styling
  * Use the version of the old logo with the outline, since that will look better on the dark background
  * Separate out my CSS into more appropriately named files
  * Make the nav look better at the in-between sizes
  * Only include the versions of the font that are currently in use
  * Set bq-border to something I actually like (maybe the background blue so that it looks cut out?)
  * Revisit the blockquote markup: http://html5doctor.com/cite-and-blockquote-reloaded/
  * Refine the footer styling when the two halves of the content don't end at the same point
  * Override in my CSS the changes that I made in Primitive's scaffolding css
2. More updated content:
  * Set proper descriptions on the various pages
  * Update student testimonials with their current job titles
  * Add a link to this repo in the site footer
2. Improve the case studies
  * Run all the logos through a resizer, a. la Gwen's Cookbook
  * Perhaps use CSS to greyscale the logos (`filter: grayscale(100%)`)
  * Add screenshots of the guided selling tool from iGoDigital, or maybe just embed the video?
3. Contribute my tweaks back to Primitive UI
2. Update favicon with new blue color (remember favicon.io)
18. Update GitHub settings to force https
17. Take a final pass at my resume to be sure it includes all the cool stuff from my website
1. Try implementing the skill chart I prototyped here: https://docs.google.com/spreadsheets/d/1-uCwT-ZM0ja8sknY5MjIQfv_uhB6QSa7uFVcxWzDC1c/edit#gid=0
1. Look in [Google Search Console](https://search.google.com/search-console?resource_id=sc-domain%3Aelizamarcum.com)
2. Confirm that Google still finds the site [mobile friendly](https://search.google.com/test/mobile-friendly?id=zAjMfzVVKLqkllC4862fSg)
3. Syntax Highlighting?
