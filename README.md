# Include-HTML-CSS-Workshop

Beginning HTML

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet"
        integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css?family=Montserrat|Open+Sans&display=swap" rel="stylesheet">
    <title>Document</title>
</head>

<body>
    <h1>Bryan Wong</h1>
    <p>
        Some description about me
    </p>
    <a href="#">My Resume</a>


    <img src="https://source.unsplash.com/900x900?random">
    <h2>Project 1</h2>
    <p>Description about <strong>project 1</strong></p>

    <img src="https://source.unsplash.com/900x900?random">
    <h2>Project 2</h2>
    <p>Description about <strong>project 2</strong></p>

    <img src="https://source.unsplash.com/900x900?random">
    <h2>Project 3</h2>
    <p>Description about <strong>project 3</strong></p>

    <img src="https://source.unsplash.com/900x900?random">
    <h2>Project 4</h2>
    <p>Description about <strong>project 4</strong></p>

    <div>
      <p>I am a footer</p>
    </div>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>
</body>

</html>
```

Beginning CSS

```
body {
  background: rgb(245, 245, 245);
  color: green;
  font-size: 25px;
}

h1 {
  color: red;
  font-weight: lighter;
  font-size: 40px;
}

h2 {
  font-family: "Montserrat", sans-serif;
  color: pink;
  font-weight: lighter;
  font-size: 16px;
}

p {
  font-family: "Montserrat", sans-serif;
  font-size: 13px;
}

img {
  width: 400px;
  height: 200px;
  object-fit: cover;
}
```

```
Bootstrap css cdn. Place in header:
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
```

```
Bootstrap js cdns. Place in the near the end tag of body

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>
```