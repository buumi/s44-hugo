# Spring: 1944 homepage (test)

This is the content for a sketch of a new S44 home page, using `hugo`, a static
site generator.

To add content:

1. install `hugo`: http://gohugo.io/overview/quickstart/
2. clone this repo somewhere: `git clone --recursive git@github.com:spring1944/s44-hugo.git`
3. create a page: `hugo new blorg.md`
4. write/edit some content: `vim|emacs|nano|notepad++ blorg.md`
5. check out how it looks: `hugo server -t hugo-incorporated --watch --buildDrafts`, then browse to `localhost:1313`.
6. `goto 4 until $done;`
7. once you're happy with your stuff, kill `hugo`, then just run `hugo -t hugo-incorporated`.
8. `cd public/ && git commit -am "new page" && git push origin master`. Note: this is pushing to spring1944/spring1944.github.io, which is a module of s44-hugo.
9. Now your page is on spring1944.github.io. Yay!
10. You should probably also commit the markdown files and push them to this repo, if you want your changes to stick.
11. `cd s44-hugo && git commit -am "made a new page" && git push origin master`
12. Done!
13. Just kidding. Add more content!
