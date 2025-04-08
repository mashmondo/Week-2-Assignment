<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Week 2 Assignment - Advanced HTML5 Elements & Forms</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="icon" type="image/png" href="favicon.png">
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      line-height: 1.6;
    }

  img {
    max-width: 100%;
    height: auto;
  }

  table {
    border-collapse: collapse;
    width: 100%;
    margin-top: 10px;
  }

  th, td {
    border: 1px solid #444;
    padding: 8px;
    text-align: left;
  }

  fieldset {
    margin-top: 20px;
    padding: 15px;
    border: 1px solid #ccc;
  }

  legend {
      font-weight: bold;
    }

  label {
    display: block;
    margin-top: 10px;
  }

  input[type="text"],
  input[type="email"],
  input[type="password"],
  input[type="date"],
  select {
    width: 100%;
    padding: 8px;
    margin-top: 4px;
  }
  </style>
</head>
<body>

 <!-- Page Title -->
  <h1>📄 Advanced HTML5 Elements & Forms</h1>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>📝 Topics Covered</h2>
    <ol type="I">
      <li>Images</li>
      <li>Lists</li>
      <li>Tables</li>
      <li>Forms</li>
      <li>Multimedia</li>
    </ol>
  </section>

  <!-- External Image -->
  <section>
    <h2>🌄 Featured Image</h2>
    <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" alt="Scenic View from Pexels">
  </section>

  <!-- Table of Contacts -->
  <section>
    <h2>📇 Contacts Table</h2>
    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Alice Johnson</td>
          <td>123 Apple St, NY</td>
          <td>+1-555-1234</td>
          <td>alice@example.com</td>
        </tr>
        <tr>
          <td>Bob Smith</td>
          <td>456 Berry Ave, LA</td>
          <td>+1-555-5678</td>
          <td>bob@example.com</td>
        </tr>
        <tr>
          <td>Carol White</td>
          <td>789 Cherry Rd, TX</td>
          <td>+1-555-9012</td>
          <td>carol@example.com</td>
        </tr>
        <tr>
          <td>David Lee</td>
          <td>321 Grape Blvd, IL</td>
          <td>+1-555-3456</td>
          <td>david@example.com</td>
        </tr>
        <tr>
          <td>Emma Stone</td>
          <td>654 Orange Dr, FL</td>
          <td>+1-555-7890</td>
          <td>emma@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>📝 Registration Form</h2>
    <form action="/submit" method="POST">
      <fieldset>
        <legend>Personal Information</legend>

  <label for="fullname">Full Name:</label>
  <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="Enter a valid email" required>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" minlength="8" placeholder="Min. 8 characters" required>

  <label for="dob">Date of Birth:</label>
  <input type="date" id="dob" name="dob" required>
</fieldset>

<fieldset>
  <legend>Preferences</legend> 
  
  <!-- Dropdown -->
  <label for="country">Select Country:</label>
  <select id="country" name="country" required>
    <option value="">--Choose--</option>
    <option value="us">Kenya</option>
    <option value="uk">Tanzania</option>
    <option value="ca">Canada</option>
  </select>

  <!-- Radio Buttons -->
  <label>Gender:</label>
  <input type="radio" id="male" name="gender" value="male" required>
  <label for="male">Male</label>

  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label>

  <input type="radio" id="other" name="gender" value="other">
  <label for="other">Other</label>

  <!-- Checkboxes -->
  <label>Interests:</label>
  <input type="checkbox" id="music" name="interests" value="music">
  <label for="music">Music</label>

  <input type="checkbox" id="sports" name="interests" value="sports">
  <label for="sports">Sports</label>

  <input type="checkbox" id="coding" name="interests" value="coding">
  <label for="coding">Coding</label>
</fieldset>

  <br>
  <button type="submit">Submit</button>
  <button type="reset">Reset</button>
</form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 HTML5 Project - Week 2 Assignment</p>
  </footer>

</body>
</html>
