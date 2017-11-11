# CSS Transforms

- Lets you move, warp, rotate, and scale elements
- Transforms without transitions don't have any animation

## Syntax

transform: <function>(params...);

## Common Functions

- Translation: move something around
	transform: translateX(x);
	transform: translateY(y);
	transform: translate(x,y);

- Scale: increase or decrease the size of a given element
	transform: scaleX(factorX);
	transform: scaleY(factorY);
	transform: scale(factor);
	transform: scale(factorX, factorY);

- Transform-Origin: modify the origin of the element
	transform-origin: 0 0;
	transform-origin: left;
	transform-origin: left top;
	transform-origin: left right;
	transform-origin: center;

- Rotate: rotate element on a page
	transform: rotate(degrees);
	transform: rotate(45deg);

* To use multiple transforms, you must include them in the same transform tag