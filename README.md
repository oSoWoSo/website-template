# Website template
To quickly create website with our design  
(Which you can easily change to your own)  
From any md file in repository

Look at [website](https://osowoso.github.io/website-template/)

# How to
- Copy all files from template branch to your repository
- (pandoc needed) run `./create build`
- (optionaly) (python3 needed) You can quickly test in browser with `./create serve`
- Enable pages on GitHub or elsewhere
- Create pages from branch directory docs/
- Action should automaticaly build your new site

# What does
- Create html files for any md file in repository
- If is only README.md file, It will create index.html from it
- If there are more md files it will create menu structure for all md files
- Will create dark/light theme switcher

---
layout: default
---

### Preview Page Types
[Listing Pages](samples/listings-page)

Text can be **bold**, _italic_, or ~~strikethrough~~.

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## [](#header-2)Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](favicon.jpg)

### Large image

![](https://avatars.githubusercontent.com/u/82756042?s=400&u=2f72a4c44a585158e40c7f4f1dcc674a25b3d51e&v=4)

### Spoiler

# 😉 click for open PREVIEW spoiler 🔽
<p>
<details>
  <summary>gumák preview (SVG)</summary>

![gumák](https://raw.githubusercontent.com/oSoWoSo/gumak/refs/heads/main/docs/gumak.svg)
</details>
</p>

# 😉 click for open PREVIEW spoiler 🔼

# Recolor svg

## Original color  
<img src="https://raw.githubusercontent.com/oSoWoSo/quickemu-font-and-logos/refs/heads/quickemu/vectors/midnightbsd.svg" width="24">

## Color depending on theme  
<img src="https://raw.githubusercontent.com/oSoWoSo/quickemu-font-and-logos/refs/heads/quickemu/vectors/midnightbsd.svg" width="24" data-colorize>

### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
