# Rotating wheel

CSS snippet from a WP website I created featuring a rotating wheel.

## Demo

![rotating wheel](wheel/rotating_wheel.gif)

## Snippet

```
#wheel img {
	display: block;
	margin-left: auto;
    margin-right: auto;
	animation: rotation 30s infinite linear;
}

@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(359deg);
  }
}
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
