<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AMCI Scholarship Application 2026</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f3f5f7;
      color: #222;
      line-height: 1.5;
    }

    .header {
      background: #006233;
      color: white;
      padding: 28px 20px;
      text-align: center;
    }

    .header h1 {
      font-size: 28px;
      margin-bottom: 8px;
    }

    .header p {
      font-size: 15px;
    }

    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 18px;
    }

    .card {
      background: white;
      border-radius: 10px;
      padding: 28px;
      margin-bottom: 20px;
      box-shadow: 0 3px 12px rgba(0,0,0,0.08);
    }

    .deadline {
      background: #f7f1df;
      border-left: 5px solid #c9a227;
      padding: 15px;
      margin-bottom: 25px;
      font-weight: bold;
    }

    h2 {
      color: #006233;
      margin-bottom: 20px;
      font-size: 21px;
    }

    .section-title {
      border-bottom: 2px solid #e5e5e5;
      padding-bottom: 8px;
      margin-bottom: 20px;
    }

    .row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 18px;
    }

    .field {
      margin-bottom: 17px;
    }

    label {
      display: block;
      font-weight: bold;
      margin-bottom: 7px;
      font-size: 14px;
    }

    input,
    select,
    textarea {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 15px;
      background: white;
    }

    textarea {
      min-height: 110px;
      resize: vertical;
    }

    input:focus,
    select:focus,
    textarea:focus {
      outline: none;
      border-color: #006233;
    }

    .submit-area {
      text-align: center;
      padding-top: 10px;
    }

    button {
      background: #006233;
      color: white;
      border: none;
      padding: 14px 35px;
      border-radius: 6px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background: #004d28;
    }

    .footer {
      text-align: center;
      color: #666;
      font-size: 13px;
      padding: 25px 15px 40px;
    }

    @media (max-width: 650px) {
      .row {
        grid-template-columns: 1fr;
        gap: 0;
      }

      .card {
        padding: 20px;
      }

      .header h1 {
        font-size: 23px;
      }
    }
  </style>
</head>

<body>

  <header class="header">
    <h1>AMCI Scholarship Application</h1>
    <p>Academic Year 2026/2027</p>
  </header>

  <main class="container">

    <div class="card">
      <div class="deadline">
        Application Deadline: October 20, 2026
      </div>

      <h2>Scholarship Application Form</h2>
      <p>
        Please complete all required sections carefully and provide accurate
        information before submitting your application.
      </p>
    </div>

    <form action="#" method="post" enctype="multipart/form-data">

      <div class="card">
        <h2 class="section-title">1. Personal Information</h2>

        <div class="row">
          <div class="field">
            <label for="firstName">First Name *</label>
            <input type="text" id="firstName" name="firstName" required>
          </div>

          <div class="field">
            <label for="lastName">Last Name *</label>
            <input type="text" id="lastName" name="lastName" required>
          </div>
        </div>

        <div class="row">
          <div class="field">
            <label for="dob">Date of Birth *</label>
            <input type="date" id="dob" name="dob" required>
          </div>

          <div class="field">
            <label for="gender">Gender *</label>
            <select id="gender" name="gender" required>
              <option value="">Select</option>
              <option>Male</option>
              <option>Female</option>
              <option>Other</option>
            </select>
          </div>
        </div>

        <div class="field">
          <label for="nationality">Nationality *</label>
          <input type="text" id="nationality" name="nationality" required>
        </div>

        <div class="field">
          <label for="address">Residential Address *</label>
          <textarea id="address" name="address" required></textarea>
        </div>
      </div>

      <div class="card">
        <h2 class="section-title">2. Contact Information</h2>

        <div class="row">
          <div class="field">
            <label for="email">Email Address *</label>
            <input type="email" id="email" name="email" required>
          </div>

          <div class="field">
            <label for="phone">Phone Number *</label>
            <input type="tel" id="phone" name="phone" required>
          </div>
        </div>
      </div>

      <div class="card">
        <h2 class="section-title">3. Academic Information</h2>

        <div class="field">
          <label for="institution">Current/Previous Institution *</label>
          <input type="text" id="institution" name="institution" required>
        </div>

        <div class="row">
          <div class="field">
            <label for="qualification">Highest Qualification *</label>
            <input type="text" id="qualification" name="qualification" required>
          </div>

          <div class="field">
            <label for="graduation">Year of Graduation</label>
            <input type="number" id="graduation" name="graduation"
                   min="1950" max="2030">
          </div>
        </div>

        <div class="field">
          <label for="program">Intended Program of Study *</label>
          <input type="text" id="program" name="program" required>
        </div>

        <div class="field">
          <label for="studyLevel">Study Level *</label>
          <select id="studyLevel" name="studyLevel" required>
            <option value="">Select</option>
            <option>Bachelor's Degree</option>
            <option>Master's Degree</option>
            <option>Doctorate / PhD</option>
            <option>Other</option>
          </select>
        </div>
      </div>

      <div class="card">
        <h2 class="section-title">4. Supporting Documents</h2>

        <div class="field">
          <label for="passport">Passport / Identification Document *</label>
          <input type="file" id="passport" name="passport"
                 accept=".pdf,.jpg,.jpeg,.png" required>
        </div>

        <div class="field">
          <label for="certificate">Academic Certificate</label>
          <input type="file" id="certificate" name="certificate"
                 accept=".pdf,.jpg,.jpeg,.png">
        </div>

        <div class="field">
          <label for="transcript">Academic Transcript</label>
          <input type="file" id="transcript" name="transcript"
                 accept=".pdf,.jpg,.jpeg,.png">
        </div>

        <div class="field">
          <label for="cv">Curriculum Vitae (CV)</label>
          <input type="file" id="cv" name="cv"
                 accept=".pdf,.doc,.docx">
        </div>
      </div>

      <div class="card">
        <h2 class="section-title">5. Motivation</h2>

        <div class="field">
          <label for="motivation">
            Why are you applying for this scholarship? *
          </label>
          <textarea id="motivation" name="motivation" required></textarea>
        </div>
      </div>

      <div class="card">
        <div class="submit-area">
          <button type="submit">Submit Application</button>
        </div>
      </div>

    </form>

  </main>

  <footer class="footer">
    © 2026 Scholarship Application Portal
  </footer>

</body>
</html>
