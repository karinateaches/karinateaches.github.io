## Examples aligning text and images

![image-left](/assets/images/my-img.png){: .align-left} You can left align images by adding `{: .align-left}` after you create your typical image mark down. This is some useless text to hopefully make it clear just how left aligned that bad boy is.

![image-center](/assets/images/my-img.png){: .align-center}
This is centered using `{: .align-center}`

<figure style="width: 100px" class="align-left">
  <img src="/assets/images/my-img.png" alt="">
  <figcaption>Itty-bitty caption.</figcaption>
</figure> 
If you feel like getting a little more funky you can embed some html into your markdown file using `figure` tags and a `figcaption` which gives off a better presentation of text wrap. This is some useless text to hopefully make it clear just how funky that bad boy is.

```html
<figure style="width: 100px" class="align-left">
  <img src="/assets/images/my-img.png" alt="">
  <figcaption>Itty-bitty caption.</figcaption>
</figure>
```
Just change the path in `<img src="/assets/yourimage/...` and set the width and height appropriately (or just remove it entirely)


## Notices

**Woah** watch out for this weird notice guy, make with the `{: .notice}` class.
{: .notice}

```
Here's the text of your notice!
{: .notice} 
```
In place of `{: .notice}` you can also use `{: .notice--level}` where `level` is `primary | info | warning | success | danger`

Here's the text of your notice!
{: .notice--info} 

Here's the text of your notice!
{: .notice--danger} 

## Miscellaneous mark up
### Abbreviation

HTML stands for "Hyper-text markup language".

*[HTML]: Hyper-text markup language


`*[HTML]: Hyper-text markup language`

### Cite
"I read books" ---<cite>Bookman</cite>

`"I read books" ---<cite>Bookman</cite>`

### Sub/Superscript
H<sub>2</sub>O

x<sup>2</sup>


`
H<sub>2</sub>O
x<sup>2</sup>
`
