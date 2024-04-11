<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tax Calculator</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h2>Tax Calculator</h2>
    <form id="taxForm">
        <br>
      <label for="Enter cross annual income">Enter cross annual income (in Lakhs):</label>
      <input type="number" id="Enter cross annual income" name="Enter cross annual income" min="0">
      <br>
      <label for="age">Age:</label>
      <select id="age" name="age">
        <option value="<40">&lt;40</option>
        <option value=">=40&<60">&ge;40 &lt;60</option>
        <option value=">=60">&ge;60</option>
      </select>
      <br>
      <label for="income">Income (in Lakhs):</label>
      <input type="number" id="income" name="income" min="0">
      <br>
      <label for="deductions">Deductions (in Lakhs):</label>
      <input type="number" id="deductions" name="deductions" min="0">
      <br>

      <button type="submit">Submit</button>
    </form>
    
  </div>
  <div id="modal" class="modal hidden">
    <div class="modal-content">
      <span class="close">&times;</span>
      <div id="modalText"></div>
    </div>
  </div>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script src="script.js"></script>
</body>
</html>
