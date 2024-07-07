---
title: Generic
---

A paragraph looks like this — Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. Quickly drive clicks-and-mortar catalysts for change before vertical architectures. Credibly reintermediate backend ideas for cross-platform models. Continually reintermediate integrated processes through technically sound intellectual capital. Holistically foster superior methodologies.

***

## Headings by default:

# H1 Default styles for headings
## H2 Default styles for headings
### H3 Default styles for headings
#### H4 Default styles for headings
##### H5 Default styles for headings
###### H6 Default styles for headings

***

## Lists

### Ordered list example:

1. Morbi lectus risus iaculis vel suscipit turpis quis.
2. Curabitur sit amet mauris morbi in dui quis est pulvinar ullamcorper nulla facilisi.
3. Nullam mauris orci aliquet iaculis et neque viverra vitae ligula.
4. Proin quam etiam ultrices suspendisse in justo eu magna luctus lacinia suscipit.
5. Aenean lectus elit fermentum non convallis id sagittis at neque mauris orci.

***

### Unordered list example:

* Etiam ultrices. Suspendisse in justo massa fusce non.
* Sed non quam. In vel mi sit amet augue congue elementum.
* Suspendisse in justo eu magna luctus suscipit sed lectus.
* Quisque volutpat condimentum velit class aptent taciti sociosqu torquent.
* Aenean lectus elit fermentum non convallis id sagittis at neque.

***

## Table

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

***

## Quotes

#### A quote looks like this:

> The longer I live, the more I realize that I am never wrong about anything, and that all the pains I have so humbly taken to verify my notions have only wasted my time!
>
> <cite>– George Bernard Shaw</cite>

***



## Syntax Highlighter

```css
body {
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100vw;
  background-color: #1c2021;
}

li {
  width: 200px;
  min-height: 250px;
  border: 1px solid #000;
  display: inline-block;
  vertical-align: top;
  margin: 5px;
}
```

```js
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
```

{{< image src="images/blog/01.jpg"  >}}