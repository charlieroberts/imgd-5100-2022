### Some Technical Hints: Using AFrame

[A-Frame](https://aframe.io/) is a simple, web-based design platform that uses HTML to create VR scenes. In addition, a companion website - [Glitch](https://glitch.com/) - provides a fantastic web-based development environment that will allow you to see your code + output simultaneously. Although the building blocks of aframe are basic, don't underestimate its powerful potential. Before you start, [check out all of the interesting work people in the AFrame community are up to](https://aframe.io/blog/).

There are a number of resources to get you up to speed - [aframe school](https://aframe.io/aframe-school), [aframe slack](https://aframevr-slack.herokuapp.com/), and various other tutorials blog posts if you simply Google _aframe_

#### Getting Familiar with AFrame
_Some tips from Gabbi LaBorwit ('20)_

  1. Take a few minutes to play with the examples provided on A-Frame's [home page](https://aframe.io/examples/showcase/helloworld/).
  2. Once you've looked around, go to the first example called "Hello WebVR" and click "Visual Inspector" in the top right-hand corner. Two boxes should pop up containing the source code and each HTML element's properties.
  3. In the leftmost box outlining the source code, click the third line that reads `<a-box...>`. Now the rightmost box shows the blue cube's design properties. Edit the `position` field and hit enter to see how it affects the scene. Play with the other elements/properties as well to get a feel for the code.


#### Remixing AFrame on Glitch
- Read the first half of the ["Getting Started"](https://aframe.io/docs/0.5.0/introduction/#getting-started) instructions and click the link provided to remix the starter example. When a box appears with 3 options, select "Remix your own" and sign in to your Github account from the button in the top-right corner.

- Back on the Glitch web-editor go to `index.html` and click "Show Live" in the top left corner to view what you have so far. Now go back and "remix" the code to make it your own.
  - Note: There's no need to constantly refresh the Live page, it automatically updates itself and saves the code.

- In the top-left corner click the drop-down menu with your glitch username and select "Remix This". Replace the code in `index.html` with the following basic template:

```
<html>
  <head>
    <script src="https://aframe.io/releases/0.5.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
    <!-- Your code here -->
    </a-scene>
  </body>
</html>
```

#### Some tips

- You can use this [tutorial](https://aframe.io/docs/1.3.0/guides/building-a-basic-scene.html) to build a basic scene and go from there, too.
- Scroll down the left-sidebar on the [documentation](https://aframe.io/docs/1.3.0/introduction/) page to find a bunch of tutorials for animations, sound, and more.
- Some cool [animations](https://aframe.io/docs/1.3.0/components/animation.html) to play with.
- To take your own 360º picture download the free app on an iPhone called "360 Panorama" by Occipital, Inc and send  yourself the photo to get it on your computer. An [example](https://ambiguous-hare.glitch.me/) I made.
- *Interacting with objects*: If you want to be able to click on objects or do things when you look at an object, look at this [tutorial](https://www.youtube.com/watch?v=yM89f0GLzB0) on youtube as well as the [code](https://github.com/SonarSystems/A-Frame-WebVR-Tutorials/blob/master/%5B6%5D%20Interacting%20With%20Objects/index.html) that comes with it.
