# Learning HTML 💻

This is very concise learning guide for HTML, I know HTML in general but this is a comparitively deep dive into HTML. Please join me in this journey.

## Meta tags used inside head

- `<meta name="keywords" content="Learning, HTML" />`, here we can put keywords inside here for SEO optimization, but we don't use it for that purpose these days.

## General tags used inside body tag

- We generally don't use the below tags now as they're deprecated because we should not html for styling and use css only for styling
  - `<b></b>` tag is used for writing something in bold
  - `<i></i>` tag is used for writing something in italic
- `<em></em>` tag is used for emphasizing certain content, it's italic by default. It's majorly used for SEO optimization where we want to put emphasis on certain keywords
- `<strong></strong>` tag is used for same like `<em></em>` but its bold by default but we can change its styling using css

### All about texts ✏️

- Heading tags should only be used for setting a hierarchy among them. Common mistake that people do is that they use it for styling purposes but we can always change the styling of some tag. We should only use `<h1></h1>` tag once in our web page for setting a hierarchy. If we use multiple h1 tags it'd confuse SEO engines. Therefore, using multiple h1 tags for styling reasons only is not a good SEO practice.

```HTML
<h1>Heading 1</h1>
<h2>HTML</h2>
<p>HTML Tutorial</p>
<h3>Code</h3>
<h3>Exercise</h3>
<h2>CSS</h2>
<p>CSS Tutorial</p>
```

### HTML entities

- `<HTML>` won't word work for browser if you try to type it in h1 tag. That's why we have entities.
- Here is an example of **HTML entities** below:-

  ```HTML
  <p>I love to teach you &lt;HTML&gt;! &copy;</p>
  ```

- You might not need entities during 99% of your coding time but here's the link if you'd like to check entities.
  https://tools.w3cub.com/html-entities
- One more example -> `&nbsp;` used for non braking space, if we want 2 words in the same line.

  ```HTML
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam labore
    sapiente doloremque atque ut dignissimos voluptas quae asperiores
    explicabo blanditiis, illum enim rerum&nbsp;accusantium. Quas placeat
    dolor quis dolore perspiciatis porro blanditiis, temporibus cupiditate
    sunt nesciunt deleniti quibusdam non dolores quo dicta. Blanditiis
    doloremque commodi totam molestias similique? Ex, rem?
  </p>
  ```
