## Units: px, %, vh, vw, em, max/min-height/width

<img width="1521" alt="Screenshot 2024-03-10 at 11 51 50 AM" src="https://github.com/sum1t-here/Frontend_Domination/assets/126807055/49d190ec-e2b3-4ba3-b367-371812977134">

<img width="1521" alt="Screenshot 2024-03-10 at 11 55 22 AM" src="https://github.com/sum1t-here/Frontend_Domination/assets/126807055/9d62fa59-3753-4e3c-b38b-ee92fda03e86">

````<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./styles.css" />
    <title>Document</title>
  </head>
  <body>
    <div class="test">
      <h1>Grandparent</h1>
      Using px
      <div class="child">
        <h1>Parent</h1>
        using % Blue is taking its parent height and width
        <div class="child1">
          <h1>child</h1>
          Am using vh/vw so taking entire screen My parent used <br />
          overflow so my extended side is gone
        </div>
      </div>
    </div>
  </body>
</html>```

.test {
  width: 800px;
  height: 800px;
  background-color: red;
}

.child {
  width: 50%;
  height: 80%;
  background-color: blue;
  color: yellow;
  overflow: hidden;
}

.child1 {
  width: 80vw;
  height: 80vh;
  background-color: green;
}




```<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="./em.css" />
  </head>
  <body>
    <div class="test">
      em depends on font size, if given to parents depends on children also
    </div>
    <div class="test1">rem depends on root font size</div>
  </body>
</html>```

.test {
  font-size: 20px;
  width: 20em;
  height: 20em;
  background-color: red;
}

html {
  font-size: 10px;
}
.test1 {
  font-size: 50px;
  width: 2rem;
  height: 2rem;
  background-color: green;
}

````

# css properties

display

- inline
- inline-block
- block

<img width="1521" alt="Screenshot 2024-03-10 at 12 20 03 PM" src="https://github.com/sum1t-here/Frontend_Domination/assets/126807055/1c32f651-277f-40bf-ad27-1a2921b29745">

position
