# Creative Advanced CSS & JavaScript Animations

## CSS Transitions Basics

The `transition` property will help turn a static and mechanical change in appearance into a more smooth and nicer interaction.

- `transition-property`: the particular css property that will be affected by the change. Can accept `1s` (seconds) or `3000ms` (milliseconds)
- `transition-duration`: the amount of time for the change to complete
- `transition-timing-function`: defines how the change in the property will occur
- `transition-delay`: the delay before the change happens

Not every property can be animated, such as font-family, display or background-image.

## CSS Transform/Translate Basics

```css
transform: translate(the value);
```

### Moving horizontally and vertically

```css
img {
	/* ... */
	transition: transform 2s;
}

img:hover {
	transform: translateX(500px);
	transform: translateY(500px);

	/* or */

	transform: translate(500px, -500px);
}
```

### Scaling

```css
img:hover {
	transform: scaleX(2); /* doubles the size horizontally */
	transform: scaleY(0.5);

	/* or */

	transform: scale(1.5, 0.5);
}
```
