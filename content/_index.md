---
keepAspectRatio: true
---

## Ciao!

My name is Dylan Roy-Leo, and this is my website! This is a simple homepage written as content so the `hugo-brewm` theme can render its hero, listing and other homepage components automatically. Soon I will update this page to be super-duper cool!

Testing paragraphs?? Wow `paragraphs` are so cool!

What about LaTeX?? Inline?? $$inline \ \delta x$$ hmmm inline LaTeX does *not* want to render...

Block LaTeX??

$$
\delta x
$$

Nope. Bummer. Testing from the [Hugo-Tufte](https://foxihd.github.io/hugo-brewm/en/post/tufte-features/#we-really-like-cats) website:

{{< marginpar >}}This is Marginpar.{{< /marginpar >}}
$e^{i \pi} = -1$
 and $\sqrt{-1} = i $
and $ a_2 = 3 $.

Ok lets test code now:

```python
import numpy np
import scipy as sp
import matplotlib.pyplot as plt

# Gotta use those comments!!
# Comments are fun!!

arr = np.zeros((10,10))
```
And that's some Python code!

Testing epigraphs:
{{< epigraph pre="Shawn O'Hare, " cite="Math is Fun" post=", p.8"  >}}
This is an example of an epigraph with some math
$ \mathbb N \subseteq \mathbb R $
to start the beginning of a section.
{{< /epigraph >}}

### About

I write about software, tooling, and small experiments. This homepage uses the theme's shortcodes and partials to render a hero, featured content and post listing.

Feel free to edit this file at `content/_index.md` to change the hero text, cover image, or add extra sections using the `section` shortcode.


<!-- Optionally add more sections or shortcodes here -->
