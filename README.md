# rouge-themes
A set of CSS theme files for [Rouge](https://github.com/rouge-ruby/rouge) (Ruby-based code highlighting tool) ready for use e.g. with [Jekyll](https://jekyllrb.com/docs/liquid/tags/#code-snippet-highlighting). These themes were downloaded from original source with `rougify` command, you can download it yourself with tutorial below.

### About Rouge
Rouge is a syntax highlighter written in Ruby inspired by [Pygments](https://github.com/pygments/pygments). It is a default syntax highlighter for Jekyll static sites. It can highlight over 200 different languages, and output HTML or ANSI 256-color text. 

### List of Rouge themes
```
base16
base16.dark
base16.light
base16.monokai
base16.monokai.dark
base16.monokai.light
base16.solarized
base16.solarized.dark
base16.solarized.light
bw
colorful
github
gruvbox
gruvbox.dark
gruvbox.light
igorpro
magritte
molokai
monokai
monokai.sublime
pastie
thankful_eyes
tulip
```
### Get Rouge CSS themes with rougify
You can get Rouge CSS themes yourself with [rougify](http://manpages.ubuntu.com/manpages/bionic/man1/rougify.1.html) command, just follow steps below:
- Make sure you have Ruby and RubyGems installed
- Install rouge with command `gem install rouge`
- Get list of all available rouge styles with command: `rougify help style`
- Download e.g. "monokai" theme to current directory with command `rougify style monokai > monokai.css`

### References
- https://github.com/rouge-ruby/rouge
- http://manpages.ubuntu.com/manpages/bionic/man1/rougify.1.html
- https://jekyllrb.com/docs/liquid/tags/#code-snippet-highlighting
- https://github.com/pygments/pygments