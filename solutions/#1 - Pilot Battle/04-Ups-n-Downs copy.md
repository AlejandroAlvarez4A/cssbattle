# Battle #1 - Pilot Battle

## #4 - Ups n Downs

[Link to the problem](https://cssbattle.dev/play/4)

![result](./images/04-Ups-n-Downs.png)

```html
<div class="container">
  <div class="half-circle-b pos-2"></div>
  <div class="half-circle-t pos-1"></div>
  <div class="half-circle-b pos-3"></div>
</div>

<style>
  body {
    padding: 0;
    margin: 0;
    background: #62306d;
  }

  .container {
    display: flex;
    width: 100%;
    height: 100%;
    align-items: center;
    justify-content: center;
  }

  .half-circle-t {
    width: 100px;
    height: 100px;
    border-radius: 100% 100% 0 0;
    background-color: #f7ec7d;
  }

  .half-circle-b {
    width: 100px;
    height: 100px;
    border-radius: 0 0 100% 100%;
    background-color: #f7ec7d;
  }

  .pos-1 {
    position: absolute;
    top: 50px;
  }

  .pos-2 {
    position: absolute;
    top: 150px;
    left: 50px;
    background: #f7ec7d;
  }

  .pos-3 {
    position: absolute;
    top: 150px;
    right: 50px;
    background: #f7ec7d;
  }
</style>
```
