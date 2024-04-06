<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Weather</title>
    <style>
      h1 {
        text-align: center;
        font-size: 30px;
      }
      h2{
        color: rgb(59, 94, 168) ;
        text-align: center;
        font-size: 25px ;
      }
      h3 {
        font-size: 15px;
        text-align: center;
      }
      h4 {
        font-size: 15px;
        text-align: center;
      }
      h5 {
        text-align: center;
        font-size: 15px;
      }
      h6 {
        text-align: center;
        font-size: 15px;
        font-weight: 200;
        font-family:'Courier New', Courier, monospace ;
      }
      .degrees {
        font-weight:600 ;
      }
      div {
        text-align: center;
        font-size: 20px;
      }
      .text {
        font-size: 15px;
        font-family: 'Courier New', Courier, monospace;
      }
      .numbers {
         font-weight: 600;
         font-size: 15px;
         font-family: 'Courier New', Courier, monospace;
         color: grey;
      }
   button {
        color: rgb(59, 94, 168);
        border: 1px solid  rgb(59, 94, 168);
        border-radius: 40px;
        display: block;
        margin: 0 auto;
        background: transparent;
        padding: 15px 30px;
        outline-style: auto;
        outline-color: invert;
        transition: all 200ms ease ease-in-out;
      }
      button:hover {
        color: #fff;
        background-color: rgb(59, 94, 168);
      }
    </style>
  </head>
  <body>
    <h1>&#127780 </h1>
    <h2>
        Currently 28&#176 in Kenya
    </h2>
    <div>
        <span class="temperature">16&#176</span>
            <span class="degrees">/29&#176</span>
    </div>
    <h3>
        &#127783Tomorrow
    </h3>
    <div>
        <span class="text">10&#176</span>
        <span class="numbers">/25&#176</span>
    </div>
    <h4>
        &#127781Saturday
    </h4>
    <div>
        <span class="text">15&#176</span>
        <span class="numbers">/21&#176</span>
    </div>
    <h5>
       <span style="color:orange">&#x2600</span><span>Sunday</span>
    </h5>
    <div>
        <span class="text">25&#176</span>
        <span class="numbers">29&#176</span>
    </div>

    <button>change city</button>
    <h6>
        Coded by Beatrice
    </h6>

  </body>
</html>
