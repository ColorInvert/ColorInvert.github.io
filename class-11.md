# Daily Reading 11




#### Explain how the ability to use video and audio on the web has evolved since the early 2000s.

Native functionality of video and audio embedding used to be a lot more primitive, clunky, and vulnerable to security issues. Flash and Silverlight were the two that made up the majority of the older embed methods. HTML now has native support for video and audio in the form of dedicated elements, `<video>` and `<audio>`

#### Describe the use of the src and controls attributes in the `<video>` element.

Src, like with images, is used to note the video file's home directory so it can be referenced.

Controls are for, well, the controls of the video. the play, pause, volume, and any other playback options such as speed. There is a default one available, but your own can be created using the JavaScript API should you wish.

#### Why is it important to have fallback content inside the `<video>` element?

the fallback content is simply a second option if the video embed itself fails. it can be a simple message saying "failed to embed video" or it can be used to provide a secondary mirror to the video, or a link to the direct path in which the video resides. Important for older browsers, and support for anyone who's embed happens to not work.


#### Write a very short story where `<audio>` and `<video>` are characters.

Audio walks down the street, feeling rather glum, and comes face to face with the object of his dismay. Video. They stop in front of each other, and Video is taken aback by Audio's sudden outburst. "What even am I, compared to you? What is it that I achieve that you cannot do better? Why do I even exist, when you do?"
Video smiles, and responds "Absolutely nothing. Hahaha, look at this scrub, just has support for scrubbing, volume, and pause."

Audio, without missing a beat, sucker punched video in the stomach. "At least I load faster, you compression addled wretch!"

#### How does Grid layout differ from Flex?

Grid has a two dimensional focus that flex does not. While flex has overflow onto another line if space runs out, grid is designed around elements being arbitrarily sized next to, above, and below each other.

#### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

Container: The over-arching bounding box that all grid items are within, not to be confused with the box-model-item like "grid item." A Container holds many grid items.

Grid Item: the children within the grid container, as mentioned above. Similar to a single box from the box model.

Grid Line: The division point between grid items. Is either vertical or horizontal, and are called "Column grid lines" or "Row grid lines" respectively.

#### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

Responsive images allow multiple different images to be displayed depending on the size of the screen browsing to the webpage. Computers used to have very standardized resolutions, and so it would be a reasonable bet that any visitors would have a screen that had one of a few different possible aspect ratios. Now that phones exist, this is no longer the case, and measures to ensure that your site's images display elegantly for unusual aspect ratios greatly improve accessibility.

#### Define the following `<img>` attributes srcset and sizes. Write an example of how they are used.

srcset: A set of different images with different cropping or zoom applied that will fit better at specific horizontal resolutions than the original version.

sizes: The set of conditions that should need to be met before the image is swapped out with one of the other variants.

A panorama image used at the top of a website, for wide screen monitors, but with a couple in the center that is the focus of the panorama. If the image were just scaled down for a portrait-oriented screen, then the people, the focus of the image, would be shrunk down to near invisibility. But having a secondary image available that truncates the bulk of the panorama view will allow a mobile viewer of the site to have a suitable header image that still maintains the focus on the couple.

#### How is srcset more helpful for responsive images than CSS or JavaScript?

The determination on which image variant is done in advance, saving on load time, and number of images loaded, which would not be doable with CSS.



#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)