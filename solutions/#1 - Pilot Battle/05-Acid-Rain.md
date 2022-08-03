# Battle #1 - Pilot Battle

## #5 - Acid Rain

[Link to the problem](https://cssbattle.dev/play/5)

![result](./images/05-Acid-Rain.png)

```html
<div class="green-leaf"></div>
<style>
  body {
    margin: 0;
    padding: 0;
    background: #0b2429;
    display: flex;
  }
  .green-leaf {
    background: #998235;
    width: 120px;
    height: 120px;
    margin: auto;
    border-radius: 100% 0 100% 100%;
  }
  .green-leaf::before {
    content: "";
    display: block;
    background: #f3ac3c;
    width: 120px;
    height: 120px;
    margin: 60px -60px;
    border-radius: 100% 0 100% 100%;
  }
  .green-leaf::after {
    content: "";
    display: inline-block;
    background: #f3ac3c;
    width: 120px;
    height: 120px;
    border-radius: 100%;
    position: absolute;
    top: 30px;
    right: 80px;
    z-index: -12;
  }
</style>
```
