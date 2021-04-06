<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Ali quiz</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
</head>
<body>

  <!-- top section -->
  <div class="intro py-3 bg-white text-center">
    <div class="container">
      <h2 class="text-primary display-3 my-4">Ali Quiz</h2>
    </div>
  </div>

  <!-- quiz section -->
  <div class="quiz py-4 bg-primary" style="direction:rtl ;text-align:right">
    <div class="container">
      <h2 class="my-5 text-white">چه قدر علی رو میشناسی ؟</h2>

      <form class="quiz-form text-light">
        <div class="my-5">
          <p class="lead font-weight-normal">1- علی کدام نوع از مدل ماشین را می پسندد؟</p>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q1" value="A" checked>
            <label class="form-check-label">کراس اور</label>
          </div>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q1" value="B">
            <label class="form-check-label">سدان</label>
          </div>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q1" value="C">
            <label class="form-check-label">SUV</label>
          </div>
        </div>
        <div class="my-5">
          <p class="lead font-weight-normal">2-علی کدام نوع از نوشیدنی های زیر را ترجیح می دهد ؟ </p>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q2" value="A" checked>
            <label class="form-check-label">چای</label>
          </div>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q2" value="B">
            <label class="form-check-label">قهوه</label>
          </div>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q2" value="C">
            <label class="form-check-label">آبمیوه</label>
          </div>
        </div>
        <div class="my-5">
          <p class="lead font-weight-normal">3- علی کدام مقصد را برای مسافرت ترجیح می دهد؟</p>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q3" value="A" checked>
            <label class="form-check-label">شهرکرد</label>
          </div>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q3" value="B">
            <label class="form-check-label">شمال</label>
          </div>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q3" value="C">
            <label class="form-check-label">اصفهان</label>
          </div>
        </div>
        <div class="my-5">
          <p class="lead font-weight-normal">4- علی سفر با کدام وسیله را ترجیح مد دهد ؟</p>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q4" value="A" checked>
            <label class="form-check-label">قطار</label>
          </div>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q4" value="B">
            <label class="form-check-label">ماشین</label>
          </div>
          <div class="form-check my-2 text-white-50">
            <input type="radio" name="q4" value="C">
            <label class="form-check-label">هواپیما</label>
          </div>
        </div>
        <div class="text-center">
          <input type="submit"class="btn btn-light"> 
        </div>
      </form>

    </div>
  </div>
  
  <script src="quiz.js"></script>
</body>
</html>
