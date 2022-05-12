# Hello 👋 I’m Polygon

<img align="right" width="425" src="https://aspectos.github.io/images/PixelBookGo.png"/>

```js
fetch('https://polygon')
  .then(res => res.json())
  .then(data => {
    if (data.error) {
      alert("Polygon is not available right now");
    }
      document.getElementById("user").innerText = "Polygon";
      document.getElementById("country").innerText = "Australia";
      document.getElementById("description").innerText = "I am a person that likes to make lots of small projects";
      document.getElementById("languages").innerText = "html" + "css" + "js";
    });
```
