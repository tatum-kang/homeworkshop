# Workshop - Day11

## Problem 1

- 아래의 코드를 작성하여 몇 번째 단락이 빨간색으로 변하는지 확인해보자.

```html
<!DOCTYPE html>
<html lang="ko">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>workshop</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark ">
    <a class="navbar-brand text-white" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-item nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
        <a class="nav-item nav-link " href="#">Git</a>
        <!-- <a class="nav-item nav-link" href="#">Python</a> -->
        <a class="nav-item nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Python</a>
      </div>
    </div>
  </nav>
  <br>

  <form class="container">
    <div class="form-group">
      <label for="exampleInputEmail1">Email address</label>
      <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
        placeholder="Enter email">
      <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
    </div>
    <div class="form-group">
      <label for="exampleInputPassword1">Password</label>
      <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
    </div>
    <div class="form-group">
      <label for="exampleInputPassword1">Password Confirmation</label>
      <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password Confirmation">
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
  <br>
  <div class="container">
    <div class="row">
      <div class="card squre col-4" style="width: 18rem;">
        <img src="zzzz.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title"><strong>고양이</strong></h5>
          <p class="card-text">이건 고양이다..</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card squre col-4" style="width: 18rem;">
        <img src="zzzz.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title"><strong>고양이</strong></h5>
          <p class="card-text">이건 고양이다..</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card squre col-4" style="width: 18rem;">
        <img src="zzzz.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title"><strong>고양이</strong></h5>
          <p class="card-text">이건 고양이다..</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
    </div>
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




