# Contributing to Altinn docs

The Altinn docs site is generated from [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 
using the [Hugo](https://gohugo.io/overview/introduction/) static site generator.


## Instructions 

### Initial setup
1. Download and install [Git](https://git-scm.com/downloads) and clone the [docs repository](https://github.com/altinn/docs) to a local folder.
2. We also recommend downloading and using [vs code](https://code.visualstudio.com) for editing markdown
3. [Download Hugo](https://github.com/spf13/hugo/releases) (version 0.21 or newer) for your platform, and place it in the same folder named as "hugo.exe"

### Build / Edit / Test
1. Open the docs repo-folder in vs code (or another editor)
2. Run `hugo -serve` or click "Run Altinn docs" (Ctrl-Shift-D) in vs code. This generates the site and opens Chrome at [http://loalhost:1313/docs](http://loalhost:1313/docs)
3. Edit any markdown (.md) file in the content-folder to get a new build of the docs site refreshed in your browser. We use YAML as front matter.

### Deploy
Whenever changes are pushed to the docs-repository, an automatic build is triggered updating [https://altinn.github.io/docs](https://altinn.github.io/docs)


If you don't have write access to the docs-repo, you need to [create a fork](https://help.github.com/articles/fork-a-repo/)
and submit a [pull request](https://help.github.com/articles/about-pull-requests/).


## Links

 - [docDock theme documentation](https://themes.gohugo.io/theme/docdock/)
 - [Markdown cheat-sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
 - [Hugo configuration](https://gohugo.io/overview/configuration/)
 - [Hugo front matter](https://gohugo.io/content/front-matter/)
 
