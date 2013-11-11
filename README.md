# QSTNS

View the project page at [https://github.com/mrmrs/qstns](http://mrmrs.github.io/qstns "QSTNS - Promises to Users.")

QSTNS is our promise to to try to make the internet better a better place.
Our core tenet is that the internet should be consumable by everyone with
a focus on typography and readability.

# Getting started

Users can start enjoying the benefits of the improved internet if you just start reading and applying the principles that QSTNS outlines.  You can find the site at the link above.

Or if you want to have your own running local copy or want to contribute to the
proejct follow the steps below:

* In terminal run
```bash
    git clone git@github.com:mrmrs/qstns.git [yourNewRepoName]
    cd [yourNewRepoName]
    git remote rm origin
    git remote add origin git@github.com:[yourUserName]/[yourNewRepoName].git
    git remote -v
```

* git remote -v will allow you to check that you have changed the remote origin correctly. The output should look like:
```bash
    origin git@github.com:[yourUserName]/[yourNewRepoName].git (fetch)
    origin  git@github.com:[yourUserName]/[yourNewRepoName].git (push)
```

* Once you add & commit files you are ready to publish run:
```bash
git push -u origin master
```

* To contibute to the project, please submit a pull request to the original
  GitHub project repo.

# What is it?

Mostly a check-list of truths about typography and accessibility with a focus on responsive web
design to ensure maximum readability.

## Directory structure
```
    mnml/
        ├── README.md
        ├── css
        │   └── i.css                 (2 kb minified - 1.2kb gzipped)
        ├── index.html                (386 bytes)
        └── sass                      CSS source
            ├── _normalize.scss
            ├── _grid.scss
            ├── _type.scss
            ├── _styles.scss
            └── i.scss
```

## Rake tasks

Install sass if you don't already have it installed
```bash
gem install sass
```

Start sass development - watches the sass folder and updates css/i.css with every file change
```bash
rake sass
```

Start sass - output is minified to css/i.css
```bash
rake minify
```

# Viewing Check-list locally

Start local python HTTPServer
```bash
python -m SimpleHTTPServer 8000
```

# Authors

[MRMRS](http://mrmrs.cc "Adam Morse - Designer Developer")

[Donielle Berg](http://www.donielleberg.com "Donielle Berg - Developer")

[Xiao (Sean) G. Wu](http://xiaogwu.com "Xiao G. Wu - Web Development Engineer")

# License

The MIT License (MIT)

Copyright (c) 2013 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

