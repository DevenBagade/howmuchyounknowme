
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deven Quiz</title>
  <style>



 @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        /* Apply the fade-in animation to an element with the class "fade-in-element" */
        .fade-in-element {
            animation: fadeIn 1s ease-in-out;
        }
div{display: block; /* Set display property to block */
            background-color: rgba(255, 255, 255, 0.5); /* Set background color */
            color: black; /* Set text color */
            padding: 20px; /* Set padding */
            margin: 20px; /* Set margin */
            border-radius: 10px; /* Add border-radius for rounded corners */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Add a box shadow */
            
}






  </style>
</head>
<body style="background-image: url('https://png.pngtree.com/thumb_back/fh260/background/20190428/pngtree-bokeh-light-in-pastel-color-gradient-background-image_104145.jpg'); background-size: cover;  background-repeat: no-repeat;">
  <center>
    <h1 class="fade-in-element">WELCOME</h1>
<div>
    <p style="font-size:20px;">Hey, It's me Deven. <br>Let's play a Quiz so that you can know how much you know me!
Click on the "Get Started" button to begin the Quiz.</p></div>
<div id="getstartedbtn">
 <button onclick="getStartedBtn()">Get Started</button>
</div>
    

<div id="quizContainer" style="display: none;">

      <p id="question">What is my Date of Birth</p>

      <form id="quizForm">
        <label>
          <input type="radio" name="options" value="a"> A. 12/11/2005
        </label>
        <br>
        <label>
          <input type="radio" name="options" value="b"> B. 11/11/2005
        </label>
        <br>
        <label>
          <input type="radio" name="options" value="c"> C. 12/12/2005
        </label>
          <br>
        <label>
          <input type="radio" name="options" value="d"> D. 11/12/2005
        </label>
        <br>
        <button type="button" onclick="checkAnswer()">Submit Answer</button>
      </form>

      <p id="result"></p>
    </div>

    <div id="quizContainer2" style="display: none;">
      <p id="question2">What is my Intrest IN</p>

      <form id="quizForm2">
        <label>
          <input type="radio" name="options2" value="a2"> A. SINGING
        </label>
        <br>
        <label>
          <input type="radio" name="options2" value="b2"> B. Drawing
        </label>
        <br>
        <label>
          <input type="radio" name="options2" value="c2"> C. Coding
        </label>
        <br>
          <label>
          <input type="radio" name="options2" value="d2"> D. Chatting
        </label>
         <br>
        <button type="button" onclick="checkAnswer2()">Submit Answer</button>
      </form>

      <p id="result2"></p>
    </div>


        <div id="quizContainer3" style="display: none;">
      <p id="question3">Which Social Media plateform I use the Most</p>

      <form id="quizForm3">
        <label>
          <input type="radio" name="options3" value="a3"> A. Facebook
        </label>
        <br>
        <label>
          <input type="radio" name="options3" value="b3"> B. Instagram
        </label>
        <br>
        <label>
          <input type="radio" name="options3" value="c3"> C. Snapchat
        </label>
        <br>
         <label>
          <input type="radio" name="options3" value="d3"> D. Whatsapp
        </label>
        <br>
        <button type="button" onclick="checkAnswer3()">Submit Answer</button>
      </form>

      <p id="result3"></p>
    </div>

    <div id="quizContainer4" style="display: none;">
      <p id="question4">With whom I like to hangout the most</p>

      <form id="quizForm4">
        <label>
          <input type="radio" name="options4" value="a4"> A. Solo
        </label>
        <br>
        <label>
          <input type="radio" name="options4" value="b4"> B. group
        </label>
        <br>
        <label>
          <input type="radio" name="options4" value="c4"> C. Gf
        </label>
        <br>
         <label>
          <input type="radio" name="options4" value="d4"> D. Family
        </label>
        <br>
        <button type="button" onclick="checkAnswer4()">Submit Answer</button>
      </form>

      <p id="result4"></p>
    </div>


    <div id="quizContainer5" style="display: none;">
      <p id="question5">AM I still Single</p>

      <form id="quizForm5">
        <label>
          <input type="radio" name="options5" value="a5"> A. Yes
        </label>
        <br>
        <label>
          <input type="radio" name="options5" value="b5"> B. No
        </label>
        <br>
        <button type="button" onclick="checkAnswer5()">Submit Answer</button>
      </form>

      <p id="result5"></p>
    </div>


    <div id="quizContainer6" style="display: none;">
      <p id="question6">Which is my Favorite song</p>

      <form id="quizForm6">
        <label>
          <input type="radio" name="options6" value="a6"> A. Daspacito
        </label>
        <br>
        <label>
          <input type="radio" name="options6" value="b6"> B. Tum se hei 
        </label>
        <br>
        <label>
          <input type="radio" name="options6" value="c6"> C. pal pal dil 
        </label>
        <br>
        <label>
          <input type="radio" name="options6" value="d6"> D. Tum hei ho
        </label>
        <br>
        <button type="button" onclick="checkAnswer6()">Submit Answer</button>
      </form>
  <p id="result6"></p>
    </div>



    <div id="quizContainer7" style="display: none;">
      <p id="question7">What do i prefer the most</p>

      <form id="quizForm7">
        <label>
          <input type="radio" name="options7" value="a7"> A. Tea
        </label>
        <br>
        <label>
          <input type="radio" name="options7" value="b7"> B. Coffee
        </label>
        <br>
        <label>
          <input type="radio" name="options7" value="c7"> C. Milk
        </label>
        <br>
        
        <button type="button" onclick="checkAnswer7()">Submit Answer</button>
      </form>

      <p id="result7"></p>
    </div>


<div id="quizContainer8" style="display: none;">
      <p id="question8">Which is my favorite colour</p>

      <form id="quizForm8">
        <label>
          <input type="radio" name="options8" value="a8"> A. The colour which my best friend like
        </label>
        <br>
        <label>
          <input type="radio" name="options8" value="b8"> B. The colour which my Mom like
        </label>
        <br>
        <label>
          <input type="radio" name="options8" value="c8"> C. Red
        </label>
        <br>
        <label>
          <input type="radio" name="options8" value="d8"> D. Fav colour depends on tht specific object
        </label>
        <br>
        <button type="button" onclick="checkAnswer8()">Submit Answer</button>
      </form>

      <p id="result8"></p>
    </div>

<div id="quizContainer9" style="display: none;">
      <p id="question9">Whom do I care for the most</p>

      <form id="quizForm9">
        <label>
          <input type="radio" name="options9" value="a9"> A. My all Friends
        </label>
        <br>
        <label>
          <input type="radio" name="options9" value="b9"> B. ony those whom I love
        </label>
        <br>
        <label>
          <input type="radio" name="options9" value="c9"> C. No one
        </label>
        <br>
        <label>
          <input type="radio" name="options9" value="d9"> D. Only those who Loves me
        </label>
        <br>
        <button type="button" onclick="checkAnswer9()">Submit Answer</button>
      </form>

      <p id="result9"></p>
    </div>


<div id="quizContainer11" style="display: none;">
      <p id="question11">What will be my best birthday gift</p>

      <form id="quizForm11">
        <label>
          <input type="radio" name="options11" value="a11"> A. Handwritten letter
        </label>
        <br>
        <label>
          <input type="radio" name="options11" value="b11"> B. My favorite chocolate
        </label>
        <br>
        <label>
          <input type="radio" name="options11" value="c11"> C. My favourite food
        </label>
        <br>
        <label>
          <input type="radio" name="options11" value="d11"> D. Netflix Premium
        </label>
        <br>
        <button type="button" onclick="checkAnswer11(); checkAnswer12();">Submit Answer</button>

      </form>

      <p id="result11"></p>
    </div>

<div  id="yourresult"  style="display: none;"><p></p> </div>
  </center>

  <script>
    var totalanswer = 0;

  function getStartedBtn() {
  // Show the quiz container after "Get Started" button is clicked
  document.getElementById("quizContainer").style.display = "block";
  document.getElementById("getstartedbtn").style.display = "none";
}



    function checkAnswer() {
      var selectedOption = document.querySelector('input[name="options"]:checked');

      if (selectedOption) {
        if (selectedOption.value === "a") {
          totalanswer++;
        }
      } else {
        document.getElementById("result").innerHTML = "Please select an option.";
      }

      // Show the second quiz container
      document.getElementById("quizContainer2").style.display = "block";
       document.getElementById("quizContainer").style.display = "none";
    }

    function checkAnswer2() {
      var selectedOption2 = document.querySelector('input[name="options2"]:checked');

      if (selectedOption2) {
        if (selectedOption2.value === "c2") {
          totalanswer++;
        }
      } else {
        document.getElementById("result2").innerHTML = "Please select an option.";        
      }
document.getElementById("quizContainer3").style.display = "block";
  document.getElementById("quizContainer2").style.display = "none";
    }

 function checkAnswer3() {
      var selectedOption3 = document.querySelector('input[name="options3"]:checked');

      if (selectedOption3) {
        if (selectedOption3.value === "b3") {
          totalanswer++;
        }
      } else {
        document.getElementById("result3").innerHTML = "Please select an option.";        
      }
document.getElementById("quizContainer4").style.display = "block";
  document.getElementById("quizContainer3").style.display = "none";
    }

 function checkAnswer4() {
      var selectedOption4 = document.querySelector('input[name="options4"]:checked');

      if (selectedOption4) {
        if (selectedOption4.value === "d4") {
          totalanswer++;
        }
      } else {
        document.getElementById("result4").innerHTML = "Please select an option.";        
      }
document.getElementById("quizContainer5").style.display = "block";
  document.getElementById("quizContainer4").style.display = "none";
    }

 function checkAnswer5() {
      var selectedOption5 = document.querySelector('input[name="options5"]:checked');

      if (selectedOption5) {
        if (selectedOption5.value === "a5") {
          totalanswer++;
        }
      } else {
        document.getElementById("result5").innerHTML = "Please select an option.";        
      }

document.getElementById("quizContainer6").style.display = "block";
  document.getElementById("quizContainer5").style.display = "none";     
    }


 function checkAnswer6() {
      var selectedOption6 = document.querySelector('input[name="options6"]:checked');

      if (selectedOption6) {
        if (selectedOption6.value === "c6") {
          totalanswer++;
        }
      } else {
        document.getElementById("result6").innerHTML = "Please select an option.";        
      }

document.getElementById("quizContainer7").style.display = "block";
  document.getElementById("quizContainer6").style.display = "none";     
    }

function checkAnswer7() {
      var selectedOption7 = document.querySelector('input[name="options7"]:checked');

      if (selectedOption7) {
        if (selectedOption7.value === "b7") {
          totalanswer++;
        }
      } else {
        document.getElementById("result7").innerHTML = "Please select an option.";        
      }

document.getElementById("quizContainer8").style.display = "block";
  document.getElementById("quizContainer7").style.display = "none";     
    }


function checkAnswer8() {
      var selectedOption8 = document.querySelector('input[name="options8"]:checked');

      if (selectedOption8) {
        if (selectedOption8.value === "d8") {
          totalanswer++;
        }
      } else {
        document.getElementById("result8").innerHTML = "Please select an option.";        
      }

document.getElementById("quizContainer9").style.display = "block";
  document.getElementById("quizContainer8").style.display = "none";     
    }

function checkAnswer9() {
    var selectedOption9 = document.querySelector('input[name="options9"]:checked');

    if (selectedOption9) {
        if (selectedOption9.value === "d9") {
            totalanswer++;
        }
    } 
    document.getElementById("quizContainer11").style.display = "block";
    document.getElementById("quizContainer9").style.display = "none";
}


function checkAnswer11() {
      var selectedOption11 = document.querySelector('input[name="options11"]:checked');

      if (selectedOption11) {
        if (selectedOption11.value === "a11") {
          totalanswer++;
        }      
    }
  document.getElementById("yourresult").style.display = "block";
    document.getElementById("quizContainer11").style.display = "none";

}

 function checkAnswer12() {
      if (totalanswer === 0) {
        document.getElementById("yourresult").innerHTML = "Your score is : " + totalanswer + "/10" + " Sorry, you don't know anything about me, maybe you met me just a few days ago";
      } else if (totalanswer > 0 && totalanswer <= 4) {
        document.getElementById("yourresult").innerHTML = "Your score is : " + totalanswer + "/10" + " Hmm, this is good, but you need to know more about me";
      } else if (totalanswer > 4 && totalanswer <= 7) {
        document.getElementById("yourresult").innerHTML = "Your score is : " + totalanswer + "/10" + " Great work, happy to see that you know me well";
      } else if (totalanswer > 7 && totalanswer <= 9) {
        document.getElementById("yourresult").innerHTML = "Your score is : " + totalanswer + "/10" + " Great work, this is fantastic, happy to see that you know me so well";
      } else if (totalanswer === 10) {
        document.getElementById("yourresult").innerHTML = "Your score is : " + totalanswer + "/10" + " You are the best, you have great observation skills, JUST BE MINE FOREVER";
      }

}

  </script>
</body>
</html>

