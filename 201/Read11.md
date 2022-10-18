# Audio, Video, Images

> ## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
   * In the early 2000, the use of video and audio was made possible by flash or silverlight. However, they are no longer in use because of the many security issues and accessibility issues.

2. Describe the use of the src and controls attributes in the \<video> element.
   * src is used the same way as within an img tag. It contains a path to the video you want to embed.
   * controls is a way the user can stop/play videos and audio. Plus it gives the user the ability to control the volume.

3. Why is it important to have fallback content inside the \<video> element?
   * If the browser doesn't support the video playback. It is a way to provide the user a link to it or whatever else you feel is important to tell the user.

4. Write a very short story where <audio> and <video> are characters.
   * audio was once playing sound in his room. However, he was bored of just listing to it all day long. until one day, a video element walked by his house. audio ran outside and asked if he can play for of his music to video playbacks. thus becoming friends for life.

References:
[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

> ## A Complete Guide To Grid

1. How does Grid layout differ from Flex?

* flex was meant for one dimensional layout. While grid is designed for two dimensional layouts.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
   * Grid container
   : The element on which display grid will be applied to.
   * Grid item
   : The children of the grid container.
   * Grid line
   : Is the dividing lines that make up the structure of the grid.

References:
[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

> ## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
   * Lets say your on a phone. You dont want to waste bandwidth to download a large picture meant to be viewed on a desktop.

2. Define the following \<img> attributes srcset and sizes. Write an example of how they are used.
   * srcset
   : Defines the set of images we will allow the browser to choose between, and what size each image is. depending on the users specs, the browser pics which photo would best fit in it.

   * Sizes
   : defines a set of media conditions and indicates what image size would be best to choose, when certain media conditions are true. If you using a small phone. sizes will tell srcset to display a small image to the screen.

3. How is srcset more helpful for responsive images than CSS or JavaScript?
   * The browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. Basically, by the time it realizes it needs a smaller photos. the original photo would have loaded and than the smaller photo would load afterwards. Which is not what we want.

References:
[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

> ### Other good reads
* [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML),
[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

> Things I want to know more about
* Is there a reason not to use grid for?


[Return home](../README.md)
