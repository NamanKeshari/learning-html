# Learning HTML 💻

This is very concise learning guide for HTML, I know HTML in general but this is a comparitively deep dive into HTML. Please join me in this journey.
[Reference Video](https://youtu.be/qz0aGYrrlhU "HTML Crash Course")

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

#### HTML entities

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

### HyperLinks

- href -> hypertext reference
- You can either write relative url or absolute url
  - url -> Uniform Resource Locator
  - relative url -> from your current file, eg:- `href="../index.html"`
  - absolute url -> starts from root directory, eg:- `href="/index.html"`
- Difference between link and hyperlinks
  - A link is just an address(url)[location of the target page]
  - A hyperlink is an element that user can click on to navigate to that target page.
- <details>
    <summary>Important example below:-</summary>
    <p>
    ```HTML
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta name="keywords" content="Learning, HTML" />
        <meta
          name="description"
          content="Here I can descibe what my website is doing or just general desciption about my website"
        />
        <title>Learning HTML</title>
        <style>
          img {
            height: 500px;
            width: 500px;
            object-fit: contain;
          }
        </style>
      </head>
      <body>
        <a href="/company/about.html">About Me</a>
        <a href="images/naman-image.jpg" download>My photo</a>
        <a href="#section-CSS">CSS</a>
        <a href="http://google.com">Open Google in this tab itself</a>
        <a href="http://google.com" target="_blank">Open google in new tab</a>
        <a href="mailto:naman.manjul@gmail.com">Email me</a>
        <h2>HTML</h2>
        <img src="images/coffee.jpg" alt="A coffee mug on a table." />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus
          vitae, consectetur provident atque labore, quisquam nam neque dignissimos
          aperiam distinctio accusamus amet aut cumque a sunt et commodi corporis
          est assumenda. Aliquid quas sed quasi eveniet quibusdam. Iure facere
          suscipit neque sed eligendi a numquam asperiores dolorem ex ducimus nisi
          nam doloribus quis consectetur nostrum, commodi illum recusandae hic
          quaerat id. Excepturi rem vitae magnam minima porro ullam, aperiam
          reprehenderit dolor ut eum expedita id repellat totam tenetur nesciunt
          minus in quibusdam dicta tempora saepe! Excepturi in, velit obcaecati
          adipisci impedit magni accusantium praesentium voluptate distinctio nam
          modi ea ex voluptatem, et, dolorem numquam. Quaerat dignissimos
          accusantium expedita molestiae voluptas amet ullam perspiciatis,
          architecto voluptates omnis dolorem! Magnam, impedit sapiente minus magni
          consequatur sint corrupti autem eius ipsam maiores aliquid officiis
          officia iure fugiat. Voluptatum temporibus asperiores, quas veniam alias
          autem nostrum, excepturi consequuntur ex facilis libero fuga, obcaecati
          aut ullam voluptate voluptates iusto omnis. Architecto voluptatem sit
          facilis quos, hic numquam. Sapiente ad omnis iusto quaerat numquam impedit
          alias eaque quae harum maxime dolore ratione, dolorum reprehenderit amet
          maiores atque temporibus ea libero rem provident nihil a at magni nostrum.
          Vero quod quam nobis vitae commodi, nostrum unde reprehenderit ipsam,
          autem incidunt eos id officia molestiae, at quis? Asperiores voluptatem
          illum ab. Sunt ea, odio earum sed magni molestias dolorum. Ratione
          perspiciatis iusto eius error vel labore officia iure vitae totam harum
          doloremque commodi atque nostrum natus qui, dolores ut assumenda at ab
          esse quia numquam. Quis cum harum asperiores beatae fugiat, maxime
          incidunt dolorem dolore aut sit iure vel maiores, et distinctio illum
          debitis quod nam fuga nobis similique dolor. Delectus suscipit corporis
          aspernatur iure odit, ea soluta rem sit accusamus eum quidem sequi ex
          modi, amet id aliquid minima asperiores beatae! Consectetur recusandae
          dolorum vitae. Vel debitis laborum nemo consequatur unde assumenda maiores
          voluptas molestiae veniam et? Sit soluta velit excepturi nulla ducimus
          quae officiis cupiditate eligendi expedita error sed, ut consequuntur
          mollitia blanditiis totam et reiciendis iusto ad natus corporis deserunt
          tempora tempore. Impedit assumenda dolore porro dolor similique dolores
          amet saepe velit vero? Sit, facilis! Ea placeat animi expedita iure sed
          perspiciatis minima, architecto, ducimus at doloremque nemo nisi labore.
          Architecto nam molestias natus similique corrupti accusantium, tenetur
          fugit voluptate fugiat nisi accusamus reprehenderit at quia eos,
          dignissimos esse dolorum qui voluptas rem. A neque molestias est assumenda
          aspernatur voluptatum porro, laudantium aliquam sed nam sapiente tempore
          nesciunt culpa esse, minima magni? Voluptate, molestias harum sapiente
          quia quisquam voluptatibus cumque perspiciatis esse dicta neque possimus
          minima vero, obcaecati earum repudiandae nesciunt, optio vitae repellendus
          odit architecto non ut incidunt! Earum accusamus rerum rem assumenda
          obcaecati, quo molestias in a excepturi nam repudiandae illo sapiente,
          eaque, odit non sed? Commodi quisquam, blanditiis reprehenderit natus
          praesentium totam illo? Reiciendis nisi facere nihil minus soluta
          obcaecati aliquid nobis illum ea, culpa ab laboriosam. Non, nemo. Animi
          quae reprehenderit sequi est aut magni impedit magnam, qui illum libero
          quasi, recusandae fugit eos? Nesciunt dolore perspiciatis quasi libero.
          Corrupti, impedit.
        </p>
        <h2 id="section-CSS">CSS</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque
          impedit veniam reprehenderit vel esse, dolorem blanditiis corporis optio
          dicta dolores non incidunt voluptatem quam eum similique repudiandae
          dolorum iusto in fuga aliquam alias expedita? Ea ut itaque eveniet
          temporibus vel ullam distinctio assumenda necessitatibus rem, laudantium
          id at repudiandae voluptatum quisquam modi dolorum voluptas magni nostrum
          mollitia exercitationem? Similique deserunt temporibus commodi voluptatum
          voluptas, asperiores nam assumenda maiores natus nihil, culpa unde sunt
          libero veniam voluptate, quibusdam aliquid quidem iste a magnam.
          Voluptatum ratione vel rerum consectetur officia maxime porro culpa sint
          rem, amet eligendi soluta voluptates unde, incidunt distinctio sequi
          facere itaque repellendus ab labore sed ad sapiente fuga. Sint aut rem
          molestiae consequatur tenetur deserunt non minus ipsum quibusdam, velit
          amet eos nam in adipisci, repudiandae optio fuga alias harum? Dolor nihil
          quae reprehenderit provident voluptates fugiat, incidunt tempore
          inventore, asperiores laboriosam quo. Distinctio officiis amet cum
          voluptas rerum nulla quos perferendis cumque molestias quia, odit,
          assumenda laboriosam itaque facilis. Praesentium adipisci labore ipsam
          provident. Vel voluptatibus aspernatur eveniet possimus culpa aliquid
          maiores beatae nemo inventore quia. Earum nam necessitatibus, provident
          minima nemo molestias neque sint laudantium magni recusandae, facere sequi
          corrupti ipsam voluptates in itaque non maxime.
        </p>
        <button>
          <a href="#">Jump to top</a>
        </button>
      </body>
    </html>
  ```
  </p>
  </details>

### Images 🖼️

- alt prop is important in img tag as it is very helpful for visually impaired people, also it shows alt text if your image is not loaded properly in the browser.
- Example - `<img src="images/coffee.jpg" alt="A coffee mug on a table." />`

```

```
