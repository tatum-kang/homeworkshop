# Workshop - Day12

## Problem 1

- 스마트폰, 태블릿 PC, 노트북의 가로 해상도가 다음과 같을 때, 4개의 아이템이
  각각의 기기에서 아래와 같이 보이도록 Bootstrap Responsive Grid System을
  이용하여 구현하시오.

```html
<!DOCTYPE html>
<html lang="ko">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>grid</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <style>
    .square {
      background-color: lightseagreen;
      border: 1px solid darkgrey;
    }
  </style>
</head>

<body>
  <div class="container">
    <div class="row">
      <div class="col-12 col-md-6 col-xl-3">
        1
      </div>
      <div class="col-12 col-md-6 col-xl-3">
        2
      </div>
      <div class="col-12 col-md-6 col-xl-3">
        3
      </div>
      <div class="col-12 col-md-6 col-xl-3">
        4
      </div>
    </div>
  </div>
  <hr>


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




