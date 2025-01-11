## Projects with html-css-js to practice

1- Background Video:

-css: @media(min/max-aspect-ratio)
-html: <video playinline></video>

2- Creative Loading Animation:

```css
.loader .loading {
  animation: load 0.8s ease infinite;
}

.loader .loading.one {
  animation-delay: 0.3s;
}

@keyframes load {
  0% {
    width: 30px;
    height: 30px;
  }
  50% {
    width: 20px;
    height: 20px;
  }
}
```

3- Custom Scrollbar

```css
/* Scrollbar */
::-webkit-scrollbar {
  background-color: transparent;
  width: 10px;
  /* border: 2px dashed white; */
}
::-webkit-scrollbar-thumb {
  background: linear-gradient(#21d4fd, #8721ff);
  border-radius: 100px;
}
```
