## Snippet
```css
/*keyframe*/
@keyframes rotate360 {
	to {
		transform: rotate(360deg);
	}
}

/*application*/
.container-3baos1 .button-14-BFJ:last-child:hover svg {
	animation:rotate360 .69s /*NICE*/ linear infinite;
	color: rgb(var(--accentcolor));
}
```

## Extra
This also recolors the settings icon depeneding on the specified accent color (from a theme), to rmove that just remove the entire `color:` line.
