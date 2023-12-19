<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>I 들의 동물원</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Gowun+Dodum&display=swap');
/*mytitle */
.mytitle {
            width: 700px;
            height: 100px;
            margin:auto;
            color: white;
            text-align: center;

            padding-top: 30px;
            border-radius: 8px;

            background-image: url('https://www.ancient-origins.net/sites/default/files/field/image/Agesilaus-II-cover.jpg');
            background-position: center;
            background-size: cover;
             

        }
        .mycards {
             width : 1000px;
             margin : 30px auto 0px auto;

        }

        .mycards > img {
            width : 500px;
            height: 500px;
        }

        .title {
            /* 최상단 라벨 */
            background-color: green;
            width: 80%;
            height: 50px;
            border: 3px solid blue;
            border-radius: 10px;

            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;

            margin: 0px auto 0px auto;
            /* 위에서 조금 떨어트리려다 컨테이너가 같이 움직여서 실패 */
        }

        .title>h1 {
            background-color: red;
            width: 80%;
            height: 45px;
            color: black;

            font-weight: bold;

            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;

            margin: auto;
            letter-spacing: 5px;
        }

        * {
            font-family: 'Gowun Dodum', sans-serif;
        }

        body {
            background-size: cover;
        }

        .mycards {
            width: 80%;
            margin: 1% auto 1% auto;
            background-color: none;
            text-align:  center;
        }

        .container {
            background-color: wheat;
            width: 80%;
            margin: auto;
           
        }

        .mymain {
            background-color: green;
            height: 350px;
            width: 500px;
            margin: 20px auto 20px auto;

            border: 1px solid white;
            padding: 20px;
            border-radius: 5px;
        }

        .mymain>div>button {
            margin: auto auto auto 360px;
        }

        .footer {
            background-color: black;
            width: 100%;
            height: 200px;
        }

        .footer>div {
            height: 50px;
        }

        .footer>div>a>img {
            float: left;
            width: 50px;
            height: 50px
        }
    </style>
    <script>
        // functions


    </script>
</head>

<body>
    <div class="container">
        <div class="title">
            <h1>I들의 동물원</h1>
        </div>
        <!--헤더-->
        <header class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 mb-4">
            <div class="col-md-3 mb-2 mb-md-0">
                <a href="/" class="d-inline-flex link-body-emphasis text-decoration-none">
                    <svg class="bi" width="40" height="32" role="img" aria-label="Bootstrap">
                        <use xlink:href="#bootstrap"></use>
                    </svg>
                </a>
            </div>
            <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
                <li><a href="index.html" class="nav-link px-2 ">홈</a></li>
                <li><a href="#" class="nav-link px-2">고양이</a></li>
                <li><a href="template.html" class="nav-link px-2">판다</a></li>
                <li><a href="#" class="nav-link px-2">볼파이톤</a></li>
                <li><a href="#" class="nav-link px-2">수리부엉이</a></li>
            </ul>
        </header>
        <!--인트로-->
        <div class="mytitle">
          <h1>이 동물의 이름은 무엇일까요?</h1> 
      </div>
        <!--이미지들-->
        <div class="mycards">
          <div class="row row-cols-1 row-cols-md-4 g-4">
              <div class="col">
                  <div class="card h-100">
                      <img src="C:\Users\dhsto\OneDrive\바탕 화면\프로젝트\동물원/수리부엉이.jpg" class="card-img-top" alt="..." style = "height: 200px;">
                      <div class="card-body">
                        수리부엉이
                      </div>
                  </div>
              </div>
              <div class="col">
                  <div class="card h-100">
                      <img src="C:\Users\dhsto\OneDrive\바탕 화면\프로젝트\동물원/볼파이톤.jpeg" class="card-img-top" alt="..." style = "height: 200px;">
                      <div class="card-body">
                        볼파이톤
                      </div>
  
                  </div>
              </div>
              <div class="col">
                  <div class="card h-100">
                      <img src="C:\Users\dhsto\OneDrive\바탕 화면\프로젝트\동물원/고양이.jpg" class="card-img-top" alt="..." style = "height: 200px;">
                      <div class="card-body">
                        고양이
                      </div>
                  </div>
              </div>
              <div class="col">
                  <div class="card h-100">
                      <img src="C:\Users\dhsto\OneDrive\바탕 화면\프로젝트\동물원/펜더.jpg" class="card-img-top" alt="..." style = "height: 200px;">
                      <div class="card-body">
                        펜더
                      </div>
                  </div>
              </div>
          </div>
      </div>
        <!--질문넣기 form-->
        <div class="mymain">
            <div>
              <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email address</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
              </div>
              <div class="mb-3">
                <label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
                <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
              </div>
              <button type="button" class="btn btn-secondary">Secondary</button>
            </div>
          </div>
    <!--footer-->
    <div class="footer">
        <div>
            <a href="https://naver.com">
                <img src="/image/완희님.png" class="img-fluid" alt="...">
            </a>
            <h4 style="color: white;">공완희 :INTJ(수리부엉이) </h4>

        </div>
        <div>
            <a href="https://naver.com">
                <img src="/image/세훈님.png" class="img-fluid" alt="...">
            </a>
            <h4 style="color: white;">방세훈 :INTJ(고양이) </h4>
        </div>
        <div>
            <a href="https://naver.com">
                <img src="image/효일.png" class="img-fluid" alt="...">
            </a>
            <h4 style="color: white;">이효일 :INFP(펜더) </h4>
        </div>
        <div>
            <a href="https://naver.com">
                <img src="image/정섭님.png" class="img-fluid" alt="...">
            </a>
            <h4 style="color: white;">박정섭 :INTP(볼파이톤) </h4>
        </div>
    </div>
</div>
</body>

</html>
