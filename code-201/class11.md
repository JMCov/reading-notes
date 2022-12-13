# Audio, Video, and Images

## Video and Audio Content

**Explain how the ability to use video and audio on the web has evolved since the early 2000s.**

Early videos and audio files on websites were limited, less secure, and less accessible than today.

**Describe the use of the `src` and `controls` attributes in the `<video>` element.**

- `<src>` works the same way as `<img>` it contains a path to the video you want to embed

- `<controls>` makes the browsers control interface to appear on a video so users can control the video.

**Why is it important to have fallback content inside the `<video>` element?**

A fallback is implemented with a `<p>` tag and will be displayed if the browser accessing the page doesn't support the `<video>` element, allowing us to provide a fallback for older browsers.

**Write a very short story where `<audio>` and `<video>` are characters.**

The `<audio>` and `<video>` elements hoped the browser that read them supported their videos and audio. It would make them happy if it did.

## A Complete Guide To Grid

**How does Grid layout differ from Flex?**

 Flexbox is also a very great layout tool, but its one-directional flow has different use cases — and they actually work together quite well! Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites. From [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

**Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**

- Grid container - The element on which display: grid is applied. It’s the direct parent of all the grid items.

- Grid Item - The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.

- Grid Line - The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.

From [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Responsive Images

**Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

It allows your webpage's pictures visually appealing across all screen sizes. For instance, a picture on a smartphone will look different if they are not responsive to shrink their size down.

**Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.**

- `srcset` - defines the set of images we will allow the browser to choose between, and what size each image is

- `sizes` - defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose

If you had a picture that was large you could load the image with different sizes with `srcset` to give the browser options. The `sizes attribute would tell the browser what size images to use in certain situations

**How is `srcset` more helpful for responsive images than CSS or JavaScript?**

When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — hence the need to implement solutions like srcset. For example, you couldn't load the `<img>` element, then detect the viewport width with JavaScript, and then dynamically change the source image to a smaller one if desired. By then, the original image would already have been loaded, and you would load the small image as well, which is even worse in responsive image terms. From [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

## Things I want to know more about

I want to learn more about responsive images so I can make my website visually appealing in the future.

[Back to Home](../README.md)
