<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>College Details Form</title>
</head>
<body>

  <header>
    <h1>🏫 College Registration Form</h1>
    <p><em>Please provide accurate details for college records.</em></p>
  </header>

  <hr>

  <!-- Expanded College Form -->
  <form>
    <!-- Personal Information -->
    <h2>👤 Personal Information</h2>

    <p><b>Full Name:</b><br>
      <input type="text" name="fullname" placeholder="Enter your full name" required>
    </p>

    <p><b>Roll Number:</b><br>
      <input type="text" name="rollno" placeholder="Enter your roll number" required>
    </p>

    <p><b>Email:</b><br>
      <input type="email" name="email" placeholder="yourname@example.com" required>
    </p>

    <p><b>Phone Number:</b><br>
      <input type="tel" name="phone" placeholder="+91-XXXXXXXXXX" required>
    </p>

    <!-- Academic Details -->
    <h2>📚 Academic Details</h2>

    <p><b>Department:</b><br>
      <select name="department" required>
        <option value="">--Select Department--</option>
        <option value="cse">Computer Science</option>
        <option value="it">Information Technology</option>
        <option value="ece">Electronics & Communication</option>
        <option value="eee">Electrical</option>
        <option value="mech">Mechanical</option>
        <option value="civil">Civil</option>
        <option value="bio">Biotechnology</option>
      </select>
    </p>

    <p><b>Year of Study:</b><br>
      <label><input type="radio" name="year" value="1"> 1st Year</label><br>
      <label><input type="radio" name="year" value="2"> 2nd Year</label><br>
      <label><input type="radio" name="year" value="3"> 3rd Year</label><br>
      <label><input type="radio" name="year" value="4"> 4th Year</label>
    </p>

    <p><b>Section:</b><br>
      <label><input type="radio" name="section" value="A"> A</label>
      <label><input type="radio" name="section" value="B"> B</label>
      <label><input type="radio" name="section" value="C"> C</label>
    </p>

    <p><b>Admission Type:</b><br>
      <label><input type="radio" name="admission" value="regular"> Regular</label>
      <label><input type="radio" name="admission" value="lateral"> Lateral Entry</label>
    </p>

    <!-- Preferences -->
    <h2>🎯 Preferences</h2>

    <p><b>Hobbies / Interests:</b><br>
      <label><input type="checkbox" name="hobby" value="sports"> Sports</label><br>
      <label><input type="checkbox" name="hobby" value="music"> Music</label><br>
      <label><input type="checkbox" name="hobby" value="reading"> Reading</label><br>
      <label><input type="checkbox" name="hobby" value="coding"> Coding</label><br>
      <label><input type="checkbox" name="hobby" value="other"> Other</label>
    </p>

    <p><b>Preferred Mode of Communication:</b><br>
      <label><input type="radio" name="comm" value="email"> Email</label>
      <label><input type="radio" name="comm" value="phone"> Phone</label>
      <label><input type="radio" name="comm" value="sms"> SMS</label>
    </p>

    <!-- Address -->
    <h2>🏠 Address</h2>

    <p><b>Permanent Address:</b><br>
      <textarea name="address" rows="3" cols="40" placeholder="Enter your address"></textarea>
    </p>

    <p><b>City:</b><br>
      <input type="text" name="city">
    </p>

    <p><b>State:</b><br>
      <input type="text" name="state">
    </p>

    <p><b>Pincode:</b><br>
      <input type="number" name="pincode">
    </p>

    <!-- File Upload -->
    <h2>📎 Upload Documents</h2>
    <p><b>Upload Photo:</b><br>
      <input type="file" name="photo" accept="image/*">
    </p>
    <p><b>Upload ID Proof:</b><br>
      <input type="file" name="idproof" accept="image/*,.pdf">
    </p>

    <!-- Extra Comments -->
    <h2>📝 Additional Information</h2>
    <p><b>Comments:</b><br>
      <textarea name="comments" rows="4" cols="50" placeholder="Write if you have any additional requests or info..."></textarea>
    </p>

    <p>
      <mark>Note:</mark> Please verify all details before submitting.<br>
      <small>(Your information will remain confidential and used only for college records.)</small>
    </p>

    <!-- Buttons -->
    <p>
      <button type="submit">✅ Submit</button>
      <button type="reset">❌ Reset</button>
    </p>
  </form>

  <footer>
    <p><a href="#top">⬆ Back to Top</a></p>
  </footer>

</body>
</html>
