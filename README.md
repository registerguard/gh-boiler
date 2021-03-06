Quickly install (or replace) **only** the dotfiles using `curl` and `tar`:

```bash
# Navigate to your project‘s root:
$ cd foo/
# Backup existing dotfiles (optional):
$ mv .editorconfig .editorconfig_bak && mv .gitattributes .gitattributes_bak && mv .gitignore .gitignore_bak
# Install dotfiles:
$ curl -#L https://github.com/mhulse/gh-boiler/tarball/master | tar -xzv --strip-components 1 --include=*/{.editorconfig,.gitattributes,.gitignore} --exclude=*/**/*
```

Boilerplate `README.md` verbiage follows …

---

# Lorem Ipsum

[![ScreenShot](top.png)](#)

**A quick brown fox jumps over the lazy dog.**

## Table of contents

<img align="right" width="200" src="side.png">

- [About](#about)
	- [Subsection A](#subsection-a)
	- [Subsection B](#subsection-b)
	- [Subsection C](#subsection-c)
	- [Subsection D](#subsection-d)
	- [Subsection E](#subsection-e)
- [Demonstration](#demonstration)
- [Installation](#installation)
- [Links](#links)
	- [GitHub](#github)
	- [Markdown](#markdown)
	- [Licensing](#licensing)
- [Contributing](#contributing)
- [Feedback](#feedback)
- [Release history](#release-history)
- [LEGAL](#legal)

## About [<img width="32" height="32" align="right" src="https://assets-cdn.github.com/images/icons/emoji/unicode/261d.png" class="emoji" title="TOC">](#table-of-contents)

<p align="center">
	<a href="#">
		<img width="400" height="100" src="center.png">
	</a>
</p>

A quick brown fox jumps over the lazy dog.

### Subsection A

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa.

### Subsection B

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.

### Subsection C

Nullam quis ante. Etiam sit amet orci eget eros faucibus tincidunt. Duis leo. Sed fringilla mauris sit amet nibh. Donec sodales sagittis magna.

### Subsection D

Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum.

### Subsection E

Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. Maecenas nec odio et ante tincidunt tempus. Donec vitae sapien ut libero venenatis faucibus.

## Demonstration [<img width="32" height="32" align="right" src="https://assets-cdn.github.com/images/icons/emoji/unicode/261d.png" class="emoji" title="TOC">](#table-of-contents)

Click or scan:

DEVELOPMENT | PRODUCTION
:-: | :-:
[![qr code](http://chart.apis.google.com/chart?cht=qr&chl=https://github.com/user/repo&chs=240x240)](http://user.github.io/repo/dev/) | [![qr code](http://chart.apis.google.com/chart?cht=qr&chl=https://github.com/user/repo/&chs=240x240)](http://user.github.io/repo/prod/)

## Installation [<img width="32" height="32" align="right" src="https://assets-cdn.github.com/images/icons/emoji/unicode/261d.png" class="emoji" title="TOC">](#table-of-contents)

A quick brown fox jumps over the lazy dog.

1. Lorem ipsum dolor sit amet.
1. Phasellus viverra nulla ut metus varius laoreet.
1. Aenean vulputate eleifend tellus.
1. Donec vitae sapien ut libero venenatis faucibus.

## Links [<img width="32" height="32" align="right" src="https://assets-cdn.github.com/images/icons/emoji/unicode/261d.png" class="emoji" title="TOC">](#table-of-contents)

### GitHub

* [GitHub help](https://help.github.com/)
	* [Setting up a custom domain with Pages](https://help.github.com/articles/setting-up-a-custom-domain-with-pages)
	* [GitHub Pages](https://help.github.com/categories/20/articles)
* [The GitHub Blog](https://github.com/blog/):
	* [New Features](https://github.com/blog/category/ship)
	* [Broadcasts](https://github.com/blog/broadcasts)
* [Apps](http://git-scm.com/downloads/guis):
	* [GitHub Mobile](http://mobile.github.com/)
	* [GitHub for Mac](http://mac.github.com/)
	* [GitHub for Windows](http://windows.github.com/)

### Markdown

* [GitHub Flavored Markdown](http://github.github.com/github-flavored-markdown/)
* [Markdown: Syntax](http://daringfireball.net/projects/markdown/syntax)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Licensing

* [Choose an OSS License](http://choosealicense.com/)
* [Pick a License, Any License](http://www.codinghorror.com/blog/2007/04/pick-a-license-any-license.html)

## Contributing [<img width="32" height="32" align="right" src="https://assets-cdn.github.com/images/icons/emoji/unicode/261d.png" class="emoji" title="TOC">](#table-of-contents)

Please read the [CONTRIBUTING.md](CONTRIBUTING.md).

## Feedback [<img width="32" height="32" align="right" src="https://assets-cdn.github.com/images/icons/emoji/unicode/261d.png" class="emoji" title="TOC">](#table-of-contents)

[Bugs? Constructive feedback? Questions?](https://github.com/mhulse/gh-boiler/issues/new?title=Nymphs%20blitz%20quick%20vex%20dwarf%20jog!&body=A%20very%20bad%20quack%20might%20jinx%20zippy%20fowls%20…)

## Changelog [<img width="32" height="32" align="right" src="https://assets-cdn.github.com/images/icons/emoji/unicode/261d.png" class="emoji" title="TOC">](#table-of-contents)

* [v1.0.0 milestones](https://github.com/mhulse/gh-boiler/issues?direction=desc&milestone=1&page=1&sort=updated&state=closed)

## [Release history](https://github.com/mhulse/gh-boiler/releases) [<img width="32" height="32" align="right" src="https://assets-cdn.github.com/images/icons/emoji/unicode/261d.png" class="emoji" title="TOC">](#table-of-contents)

* 2013-01-01   [v1.0.0](https://github.com/mhulse/gh-boiler/releases/tag/v1.0.0)   Lorem ipsum dolor sit amet.
* 1970-01-01   [v0.1.0](https://github.com/mhulse/gh-boiler/releases/tag/v0.1.0)   Lorem ipsum dolor sit amet.

---

Copyright © YYYY-YY [First Last](#). **All rights reserved.**

Unauthorized use and/or duplication of this material, without express and written permission from the owner, is strictly prohibited.

---

#### LEGAL

Copyright © YYYY-YY [First Last](#).

Licensed under the Apache License, Version 2.0 (the “License”); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

<img src="https://github.global.ssl.fastly.net/images/icons/emoji/octocat.png">
