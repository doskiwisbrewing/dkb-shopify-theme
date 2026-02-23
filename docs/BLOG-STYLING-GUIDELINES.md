# Blog Styling Guidelines

### How to Use Custom Layout Blocks in Shopify Articles

This guide explains how to use our custom layout classes when editing
blog posts in Shopify.

You **do not need to know HTML** --- just copy and paste the examples
below and replace the content.

------------------------------------------------------------------------

# 1. How to Add Custom Layouts in Shopify

1.  Go to **Online Store → Blog Posts**
2.  Open the blog post
3.  Switch to **HTML view** (\<\> button in the editor)
4.  Paste the block structure you need
5.  Replace the example content with your own text or images

------------------------------------------------------------------------

# 2. Full Width Image (100% Screen Width)

Use this when you want an image to take the entire width of the screen.

## Example

``` html
<div class="article-template--full-size">
  <img src="IMAGE-URL-HERE.jpg" alt="">
</div>
```

Replace `IMAGE-URL-HERE.jpg` with your image URL.

------------------------------------------------------------------------

# 3. Two Column Layout

Use this to create content in two vertical columns.

You can use:

- Text + Image
- Image + Text
- Image + Image
- Text + Text

## Two Images Side by Side

``` html
<div class="article-template-block-2-col">
  <p><img src="IMAGE-1.jpg" alt=""></p>
  <p><img src="IMAGE-2.jpg" alt=""></p>
</div>
```

## Text Left -- Image Right

``` html
<div class="article-template-block-2-col">
  <div>
    <h3>Title</h3>
    <p>Your text goes here.</p>
  </div>
  <p><img src="IMAGE.jpg" alt=""></p>
</div>
```

## Image Left -- Text Right

``` html
<div class="article-template-block-2-col">
  <p><img src="IMAGE.jpg" alt=""></p>
  <div>
    <h3>Title</h3>
    <p>Your text goes here.</p>
  </div>
</div>
```

------------------------------------------------------------------------

# 4. Three Column Grid

Use this for:
- 3 images in a row
- 3 content blocks
- Gallery sections

## Three Images Example

``` html
<div class="article-template-block-3-col">
  <p><img src="IMAGE-1.jpg" alt=""></p>
  <p><img src="IMAGE-2.jpg" alt=""></p>
  <p><img src="IMAGE-3.jpg" alt=""></p>
</div>
```

## Three Text Blocks Example

``` html
<div class="article-template-block-3-col">
  <div>
    <h3>Title 1</h3>
    <p>Text here.</p>
  </div>
  <div>
    <h3>Title 2</h3>
    <p>Text here.</p>
  </div>
  <div>
    <h3>Title 3</h3>
    <p>Text here.</p>
  </div>
</div>
```

------------------------------------------------------------------------

# 5. Centered Content (Normal Reading Width)

Use this to keep text readable and centered.

``` html
<div class="page-width">
  <h2>Your section title</h2>
  <p>Your paragraph text goes here.</p>
</div>
```

------------------------------------------------------------------------

# 6. Block Quote / Highlight Text

Use this to highlight important paragraphs.

``` html
<div class="article-template-block-quote">
  <p>Your highlighted text goes here.</p>
</div>
```

------------------------------------------------------------------------

# 7. Good Practices

✅ Keep layouts clean\
✅ Use full width blocks to create rhythm\
✅ Always preview before publishing

------------------------------------------------------------------------

# 8. Things to Avoid

❌ Do not nest column blocks inside other column blocks\
❌ Do not add extra empty `<p>` tags\
❌ Do not forget to close `</div>`
