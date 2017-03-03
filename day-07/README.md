# Daily CSS Challenge
## Day 7 - Ruler (animation)
### Inspiration

##### Styles / Technics
- [Luke Skywalker Pixel Art CSS](http://codepen.io/cctina/pen/mWeeOx), by Henrique Rodrigues | CodePen.io
- [Nodepad (CSS only - Single div)](http://codepen.io/cctina/pen/VpvNGR), by dok de leon | CodePen.io

##### Tool
- [Piskel](http://www.piskelapp.com/)
	- A free online tool for creating Pixel Art and Animated Sprites.
	- Pros
		- Easy to draw pixel arts with its toolbox.
		- You can make animations by frames.
		- It can export images from frames for CSS sprite (animation).
		- It can export .gif files as animation images 

### Note
Wanted to keep it challenging but remain some time for other work. So I made it looks simple but tried something new like adapting pixel-art style, using units 'vw'/'vh' instead of 'px' etc. 

Thanks for many talented creators who also join this Daily CSS Images challenge. Their awesome works & techniques inspired me a lot!

PS. Got a little bug after resizing the width of the window. The animation become weird. The CSS sprite position seems shifted. Not sure what the root cause is for now.
I guess using JS to reload the page content when resizing might be a solution. Or return to use absolute units like `px` would avoid this bug too.

##### Keywords
- `box-shadow`
	- The keypoint for creating a pixel art.
	- How to:
		- Made a block `1vw` x `1vw` (Set to the least number '1' will be easier when drawing.)
		- Set `box-shadow` as your pixel
			- The poisition you want. (Shifted from the block element by disitance along **x-axis** & **y-axis**.)
			- **blur-radius** & **spread-radius** set to zero.
			-  Color for each pixel.
			-  Separate each pixel attribute above by comma.
- Viewport Units
	- "Viewport-percentage lengths defined a length relatively to the size of viewport, that is the visible portion of the document." ── from [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/length#Viewport-percentage_lengths).
		- `vw` = 1/100th of the height of the viewport
		- `vh` = 1/100th of the width of the viewport
		- `vmin` = 1/100th of the minimum value of the height and the width of the viewport
		- `vmax` = 1/100th of the maximum value of the height and the width of the viewport

### Final Work
- [07 :: Ruler | CodePen.io](http://codepen.io/cctina/pen/XMXxPo)

![Ruler](final.jpg)