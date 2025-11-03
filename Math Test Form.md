<!-- Start of Math Test Form -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Math Test Form</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body { font-family: Arial, sans-serif; max-width: 800px; margin: 2rem auto; padding: 0 1rem; }
    fieldset { margin-bottom: 1rem; }
    legend { font-weight: bold; }
    label { display: block; margin: 0.5rem 0; }
  </style>
</head>
<body>

<!-- Start of Test -->
<form id="math-test" action="#" method="get">
  <h1>Math Test Form</h1>

  <fieldset>
    <legend>Student Information</legend>
    <label for="student-name">Name:</label>
    <input type="text" id="student-name" name="student-name" placeholder="Enter your full name" required />
  </fieldset>

  <fieldset>
    <legend>Multiple Choice Questions</legend>

    <!-- Question 1 -->
    <p>1) What is 8 &times; 7?</p>
    <label><input type="radio" name="q1" value="48" required /> 48</label>
    <label><input type="radio" name="q1" value="54" /> 54</label>
    <label><input type="radio" name="q1" value="56" /> 56</label>

    <!-- Question 2 -->
    <p>2) Which of the following is equal to 12 &divide; 3?</p>
    <label><input type="radio" name="q2" value="2" required /> 2</label>
    <label><input type="radio" name="q2" value="4" /> 4</label>
    <label><input type="radio" name="q2" value="6" /> 6</label>

    <!-- Question 3 -->
    <p>3) What is the value of 5 + 9 &minus; 4?</p>
    <label><input type="radio" name="q3" value="8" required /> 8</label>
    <label><input type="radio" name="q3" value="10" /> 10</label>
    <label><input type="radio" name="q3" value="12" /> 12</label>

    <!-- Question 4 -->
    <p>4) Which number is a prime?</p>
    <label><input type="radio" name="q4" value="15" required /> 15</label>
    <label><input type="radio" name="q4" value="17" /> 17</label>
    <label><input type="radio" name="q4" value="21" /> 21</label>

    <!-- Question 5 -->
    <p>5) What is 3 squared (3&sup2;)?</p>
    <label><input type="radio" name="q5" value="6" required /> 6</label>
    <label><input type="radio" name="q5" value="9" /> 9</label>
    <label><input type="radio" name="q5" value="12" /> 12</label>

    <!-- Question 6 -->
    <p>6) Which of these shows 0.5 as a fraction?</p>
    <label><input type="radio" name="q6" value="1/4" required /> 1/4</label>
    <label><input type="radio" name="q6" value="1/2" /> 1/2</label>
    <label><input type="radio" name="q6" value="2/3" /> 2/3</label>

    <!-- Question 7 -->
    <p>7) Solve for x: x + 4 = 10</p>
    <label><input type="radio" name="q7" value="6" required /> x = 6</label>
    <label><input type="radio" name="q7" value="5" /> x = 5</label>
    <label><input type="radio" name="q7" value="4" /> x = 4</label>

    <!-- Question 8 -->
    <p>8) What is the next number in the sequence: 2, 4, 8, 16, ?</p>
    <label><input type="radio" name="q8" value="24" required /> 24</label>
    <label><input type="radio" name="q8" value="32" /> 32</label>
    <label><input type="radio" name="q8" value="30" /> 30</label>

    <!-- Question 9 -->
    <p>9) Which is larger: 3 &lt; 5 or 3 &gt; 5?</p>
    <label><input type="radio" name="q9" value="lt" required /> 3 &lt; 5</label>
    <label><input type="radio" name="q9" value="gt" /> 3 &gt; 5</label>
    <label><input type="radio" name="q9" value="eq" /> 3 = 5</label>

    <!-- Question 10 -->
    <p>10) Round 6.78 to the nearest whole number.</p>
    <label><input type="radio" name="q10" value="6" required /> 6</label>
    <label><input type="radio" name="q10" value="7" /> 7</label>
    <label><input type="radio" name="q10" value="6.8" /> 6.8</label>

  </fieldset>

  <fieldset>
    <legend>Word Problem</legend>
    <p>Word Problem: A young woman teaching math has 24 notebooks. She wants to divide them equally among 6 students. How many notebooks does each student get? Show your work below.</p>
    <label for="word-answer">Your answer and work:</label>
    <textarea id="word-answer" name="word-answer" rows="6" cols="60" placeholder="Show your work here..." required></textarea>
  </fieldset>

  <p>Math symbols used in this test include: &amp;times; (multiplication), &amp;divide; (division), &amp;lt; and &amp;gt; (less than / greater than), &amp;le; (less than or equal), &amp;ge; (greater than or equal), &amp;plus; (plus), &amp;minus; (minus).</p>

  <button type="submit">Submit Test</button>

</form>
<!-- End of Test -->

</body>
</html>
