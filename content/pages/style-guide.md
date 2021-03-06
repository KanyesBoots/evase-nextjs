---
title: Style Guide
subtitle: The style guide provides you with a blueprint of default post and page styles.
image: images/5.jpg
seo:
  title: Theme Style Guide
  description: A reference for suggested typographic treatment and styles for your content
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Theme Style Guide
      keyName: property
    - name: 'og:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
      keyName: property
    - name: 'og:image'
      value: images/5.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Theme Style Guide
    - name: 'twitter:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
    - name: 'twitter:image'
      value: images/5.jpg
      relativeUrl: true
layout: page
---
# This is an H1
## This is an H2
### This is an H3
#### This is an H4
**This is a paragraph**. [Style Guide](https://evase.net/style-guide/)

```
# This is an H1
## This is an H2
### This is an H3
#### This is an H4
**This is a paragraph**. 
[Style Guide](https://evase.net/style-guide/)
```

## Quoting

Learn how to add a quote to your sentence. 

Example:
>When Evase was introduced, it was revolutionary! ~ Founder of Evase

<mark>In order to use a quote in your sentence, use the tag</mark> 

```
Start with <q> and end with </q> in your sentence or use >[text]
```
<hr />

## Unordered Lists

+ Line 1
+ Line 2
+ Line 3

## Ordered Lists

1. Line 1
2. Line 2
3. Line 3

## Video Embeds

<iframe width="640" height="360" src="https://www.youtube.com/embed/8uuFIi-ghPI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Code Blocks

Blocks of code are either fenced by `lines with three back-ticks`, or are indented with four spaces.

```
<!-- Some example CSS code -->
body {
  color:red;
}
```

```
window.$docsify = {
  coverpage: true,

  // Custom file name
  coverpage: 'cover.md',

  // mutiple covers
  coverpage: ['/', '/zh-cn/'],

  // mutiple covers and custom file name
  coverpage: {
    '/': 'cover.md',
    '/zh-cn/': 'cover.md'
  }
};
```

## Tables

<div class="responsive-table">
  <table>
    <caption>Table with thead, tfoot, and tbody</caption>
    <thead>
      <tr>
        <th>Header content 1</th>
        <th>Header content 2</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Body content 1</td>
        <td>Body content 2</td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <td>Footer content 1</td>
        <td>Footer content 2</td>
      </tr>
    </tfoot>
  </table>
</div>

<div class="note"><strong>Note:</strong> Both of the features you used above are parts of the Document Object Model (DOM) API, which allows you to manipulate documents.</div>

<div class="important"><strong>Important:</strong> In this article, try entering the example code lines into your JavaScript console to see what happens. For more details on JavaScript consoles, see Discover browser developer tools.</div>
