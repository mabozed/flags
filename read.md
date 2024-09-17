```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Flags Task</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
      integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="assets/css/style.css" />
  </head>
  <body>
    <div class="container">
      <div class="flag-container">
        <div class="flag-row">
          <div class="red"></div>
          <div class="white"></div>
          <div class="blue"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-row">
          <div class="black"></div>
          <div class="yellow"></div>
          <div class="red"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-col">
          <div class="red"></div>
          <div class="white two-icons">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
          </div>
          <div class="black"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-row">
          <div class="green"></div>
          <div class="white"></div>
          <div class="red"></div>
        </div>
      </div>
      <!-- row 2 -->
      <div class="flag-container">
        <div class="flag-row">
          <div class="white"></div>
          <div class="white japan"><p class="japan-sun"></p></div>
          <div class="white"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-row">
          <div class="green"></div>
          <div class="red one-icon">
            <i
              class="fa-solid fa-star"
              style="font-size: 24px; color: #f9d10d"
            ></i>
          </div>
          <div class="yellow2"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-col">
          <div class="red"></div>
          <div class="white one-icon">
            <img src="./assets/img/egy.png" alt="" width="15px" />
          </div>
          <div class="black"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-col">
          <div class="lightskyblue"></div>
          <div class="white one-icon">
            <img src="./assets/img/arg.png" alt="" width="25px" />
          </div>
          <div class="lightskyblue"></div>
        </div>
      </div>
      <!-- row 3 -->
      <div class="flag-container">
        <div class="flag-col">
          <div class="black"></div>
          <div class="red"></div>
          <div class="yellow2"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-col palestine">
          <div class="black"></div>
          <div class="t-red"></div>
          <div class="white"></div>
          <div class="green"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-col">
          <div class="red"></div>
          <div class="white one-icon">
            <img src="./assets/img/leb.png" alt="" width="25px" />
          </div>
          <div class="red"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-col UAE">
          <div class="green"></div>
          <div class="s-red"></div>
          <div class="white"></div>
          <div class="black"></div>
        </div>
      </div>
      <!-- row 4 -->
      <div class="flag-container">
        <div class="flag-col flag-relative">
          <div
            class="blue"
            style="border-bottom: 4px solid #e9a92e; height: 20%"
          ></div>
          <div class="white" style="height: 60%"></div>
          <div class="flag-absolute">
            <img src="./assets/img/real.png" alt="" width="50px" />
          </div>
          <div
            class="blue"
            style="border-top: 4px solid #e9a92e; height: 20%"
          ></div>
        </div>
      </div>

      <div class="flag-container">
        <div class="flag-col flag-relative">
          <div style="height: 50%; background-color: #dc052d"></div>
          <div class="flag-absolute">
            <img src="./assets/img/bayren.png" alt="" width="60px" />
          </div>
          <div class="white" style="height: 50%"></div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-row flag-relative">
          <div style="display: flex; width: 33.3333%">
            <div class="black" style="width: 50%; height: 100%"></div>
            <div
              style="width: 50%; height: 100%; background-color: #fb090b"
            ></div>
          </div>
          <div style="display: flex; width: 33.3333%">
            <div class="black" style="width: 50%; height: 100%"></div>
            <div class="black" style="width: 50%; height: 100%"></div>
          </div>
          <div style="display: flex; width: 33.3333%">
            <div
              style="width: 50%; height: 100%; background-color: #fb090b"
            ></div>
            <div class="black" style="width: 50%; height: 100%"></div>
          </div>
          <div class="flag-absolute">
            <img src="./assets/img/milan.png" alt="" width="45px" />
          </div>
        </div>
      </div>
      <div class="flag-container">
        <div class="flag-col flag-relative">
          <div style="height: 50%; background-color: #c5030a"></div>
          <div class="flag-absolute">
            <img src="./assets/img/manchester.png" alt="" width="60px" />
          </div>
          <div class="white"></div>
          <div class="black" style="height: 50%"></div>
        </div>
      </div>
    </div>
  </body>
</html>
```

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-wrap: wrap;
  background-color: #f7d2d2;
}
.flag-container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 25%;
  height: 25%;
  border-bottom: 1px solid palevioletred;
  border-left: 1px solid palevioletred;
}
.flag-row {
  width: 50%;
  height: 50%;
  display: flex;
}
.flag-col {
  width: 50%;
  height: 50%;
  display: flex;
  flex-direction: column;
}
.flag-row div {
  width: 33.3333%;
}
.flag-col div {
  height: 33.3333%;
}

.red {
  background-color: #fb090b;
}
.white {
  background-color: white;
}
.black {
  background-color: black;
}
.yellow {
  background-color: yellow;
}
.green {
  background-color: green;
}
.lightskyblue {
  background-color: lightskyblue;
}
.blue {
  background-color: #2e3092;
}
.yellow2 {
  background-color: #f9d10d;
}

.two-icons {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.two-icons i {
  font-size: 22px;
  color: green;
}
.one-icon {
  display: flex;
  justify-content: center;
  align-items: center;
}

.japan {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.japan-sun {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background-color: #fb090b;
}

.palestine,
.UAE {
  position: relative;
}
.palestine .t-red {
  position: absolute;
  border-right: 40px solid transparent;
  border-left: 40px solid #fb090b;
  border-top: 40px solid transparent;
  border-bottom: 40px solid transparent;
}
.UAE .s-red {
  position: absolute;
  height: 100%;
  width: 25%;
  background-color: #fb090b;
}

.flag-relative {
  position: relative;
}
.flag-relative .flag-absolute {
  position: absolute;
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* .parent{
  position: relative;
}
.child{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
} */
```
