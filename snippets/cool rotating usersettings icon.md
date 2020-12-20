## Simple Target
```css
.container-3baos1 .button-14-BFJ:last-child:hover svg {
	transform: rotate(360deg);
	transition: transform .69 /*NICE*/ linear;
	color: rgb(var(--accentcolor));
}
```

## Keyframe Target
```css
@keyframes rotate360 {
	to {
		transform: rotate(360deg);
	}
}
.container-3baos1 .button-14-BFJ:last-child:hover svg {
	animation:rotate360 .69s /*NICE*/ linear infinite;
	color: rgb(var(--accentcolor));
}
```
