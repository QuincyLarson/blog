---
title: "How to display code blocks in Medium"
description: "Update October 19, 2016: Medium also now supports the common convention of starting a code block with triple back-ticks. If you type ``` on a new line, Medium will now switch to code input mode. A…"
date: "2016-09-18T17:49:26.392Z"
categories: 
  - Medium
  - Programming
  - Web Development
  - Tech
  - Technology

published: true
canonical_link: https://medium.com/free-code-camp/how-to-add-code-to-medium-and-get-syntax-highlighting-d699761a5883
redirect_from:
  - /how-to-add-code-to-medium-and-get-syntax-highlighting-d699761a5883
---

## And how to write inline code and embed code for syntax highlighting

![Don’t use images of code like this.](./asset-1.png)

Medium makes it easy to add code blocks and inline

#### Medium has a hidden shortcut that will turn text plain text…

if (developer === true) {

follow(this.mediumPublication);

}

#### …into a formatted code block:

```
if (developer === true) {

  follow(this.mediumPublication);

}
```

To accomplish this, select the text, then push:

-   **Windows**: Control + Alt + 6
-   **Mac**: Command + Option + 6
-   **Linux**: Control + Alt + 6

---

**Update October 19, 2016:** Medium also now supports the common convention of starting a code block with triple back-ticks. If you type \`\`\` on a new line, Medium will now switch to code input mode. A huge thanks to [Luke Esterkyn](https://medium.com/@lukester) and the rest of the Medium team for implementing this!

---

You can also highlight code inline by selecting it, then clicking the backtick key (\`). For example, you can format text as code `freeCodeCamp()`right in the middle of a sentence.

You can also embed GitHub gists by pasting their URL into a blank line, then pressing enter:

<Embed src="https://gist.github.com/QuincyLarson/4bb1682ce590dc42402b2edddbca7aaa.js" aspectRatio={0.357} caption="" />

### How to Embed web apps

As a bonus, you can embed runnable apps right into Medium. Just in case these don’t render properly in Medium’s mobile apps, I recommend including links below each of the embeds as a fallback.

Paste a CodePen.io URL into Medium, then hit enter:

<Embed src="https://codepen.io/freeCodeCamp/embed/preview/NNvBQW?height=600&slug-hash=NNvBQW&default-tabs=html,result&host=https://codepen.io" aspectRatio={undefined} caption="" />

_View my CodePen_ [_here_](http://codepen.io/FreeCodeCamp/pen/NNvBQW)_._

You can also do this with JSFiddle.net:

<Embed src="https://jsfiddle.net/avegt5e5/3/embedded/" aspectRatio={undefined} caption="" />

_View my JSFiddle_ [_here_](https://jsfiddle.net/avegt5e5/3/)_._

### But don’t use images of code.

Even though it may seem convenient to take screenshots of your code and paste them into Medium, don’t do this.

Medium doesn’t yet have an alt-text option, so this will make your code completely inaccessible to developers who are visually impaired. And yes, [they are out there](https://medium.freecodecamp.com/looking-back-to-what-started-it-all-731ef5424aec#.fae9jgbx6).

You also can’t change the font size of a static images, which makes it a pain to read on a mobile phone (which is where most people read Medium).

Finally, this makes it impossible for readers to copy and paste your code.

I know, I know — you shouldn’t copy and paste code anyway.

But let’s face it — people do. And most people will quickly abandon your tutorial if faced with the prospect of manually typing out lots of code.

So to recap:

-   use Medium’s native code blocks
-   or embed GitHub gists
-   use working examples from CodePen and JSFiddle where possible
-   but don’t paste images of code

Happy coding and writing about coding!

**I only write about programming and technology. If you** [**follow me on Twitter**](https://twitter.com/ossia) **I won’t waste your time. 👍**
