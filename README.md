
# `dev.dispatch()`

Link to live site: https://code-for-canada.github.io/dev-dispatch/

Dev Dispatch: the Code for Canada blog written by developers, for developers.

## Instructions on publishing a blog post
Edit `/_posts/2018-11-3-update-1.md` to publish a post.

Merging to 'master' will publish your updates to the site within a few minutes. Creating a new branch with a pull request is a way to get a review/confirmation of your content before publishing.

If you need to make a new file to make an additional post, hit the + icon in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: year-month-day-update-#.md

This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) will be useful for formatting your post. It is recommended you use a markdown editor to preview your content before publishing. https://stackedit.io for example, can also help with auto-filling in markdown syntax.


## How this site works
We forked Jekyll Now to make this blog.

**Jekyll** is a static site generator that's perfect for GitHub hosted blogs ([Jekyll Repository](https://github.com/jekyll/jekyll))

### Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at http://127.0.0.1:4000/
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.
