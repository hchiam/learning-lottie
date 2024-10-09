# Learning Lottie

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Lottie files are a JSON-based image/animation format that uses [runtimes](https://lottiefiles.com/runtimes) to actually run them.

- <https://lottiefiles.com> for [free animations](https://lottiefiles.com/featured-free-animations) and much more

- <https://lottiefiles.com/runtimes> for runtimes for Web, iOS, Android, React, VueJS, Svelte

  - ```js
    import { DotLottie } from '@lottiefiles/dotlottie-web';

    const dotLottie = new DotLottie({
        autoplay: true,
        loop: true,
        canvas: document.querySelector('#dotlottie-canvas'),
        src: "https://lottie.host/4db68bbd-31f6-4cd8-84eb-189de081159a/IGmMCqhzpt.lottie", // or .json file
    });
    ```

## Quickly create animations

- 2 steps in [Fireship.io tutorial](https://www.youtube.com/watch?v=UTHgr6NLeEw):
    1) **draw SVG shapes** in **Figma**, then
    2) **animate/interact**/etc. with **CSS/JS**.

or based on [this Lottie Figma plugin tutorial](https://www.youtube.com/watch?v=ajfKecCyNOs):

- use a [Lottie plugin](https://lottiefiles.com/plugins/figma) for [Figma](https://github.com/hchiam/learning-figma) makes it much easier to create animations than trying to manually code SVGs: <https://lottiefiles.com/plugins/figma>
    1) draw in **Figma** (use smart animate between frames) > **LottieFiles plugin** > **Export** to (a) Lottie file.
    2) bonus: Figma stroke paths will automatically get path animation suggestions in the LottieFiles plugin.
