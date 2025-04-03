<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Registry</title>
    <meta name="description" content="Lovable Generated Project" />
    <meta name="author" content="Lovable" />

    <meta property="og:title" content="Contact Registry" />
    <meta property="og:description" content="A simple contact registry application" />
    <meta property="og:type" content="website" />
    <meta property="og:image" content="https://lovable.dev/opengraph-image-p98pqg.png" />

    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:site" content="@lovable_dev" />
    <meta name="twitter:image" content="https://lovable.dev/opengraph-image-p98pqg.png" />
    
    <style>
      body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.6;
        color: #333;
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
      }
      
      h1, h2, h3 {
        color: #2c3e50;
      }
      
      .container {
        display: flex;
        flex-direction: column;
        gap: 30px;
      }
      
      img {
        max-width: 100%;
        height: auto;
        border-radius: 8px;
        margin: 20px 0;
      }
      
      ol.roman {
        list-style-type: upper-roman;
        padding-left: 30px;
      }
      
      table {
        width: 100%;
        border-collapse: collapse;
        margin: 20px 0;
      }
      
      th, td {
        padding: 12px 15px;
        text-align: left;
        border-bottom: 1px solid #ddd;
      }
      
      th {
        background-color: #f8f9fa;
        font-weight: bold;
      }
      
      tr:hover {
        background-color: #f5f5f5;
      }
      
      form {
        background: #f9f9f9;
        padding: 25px;
        border-radius: 8px;
        max-width: 600px;
      }
      
      .form-group {
        margin-bottom: 15px;
      }
      
      label {
        display: block;
        margin-bottom: 5px;
        font-weight: 500;
      }
      
      input, select, textarea {
        width: 100%;
        padding: 10px;
        border: 1px solid #ddd;
        border-radius: 4px;
        font-size: 16px;
      }
      
      .radio-group, .checkbox-group {
        display: flex;
        gap: 15px;
      }
      
      .radio-group label, .checkbox-group label {
        display: flex;
        align-items: center;
        font-weight: normal;
        cursor: pointer;
      }
      
      .radio-group input, .checkbox-group input {
        width: auto;
        margin-right: 5px;
      }
      
      button {
        background: #3498db;
        color: white;
        border: none;
        padding: 12px 20px;
        border-radius: 4px;
        cursor: pointer;
        font-size: 16px;
        margin-top: 10px;
      }
      
      button:hover {
        background: #2980b9;
      }
      
      /* Responsive adjustments */
      @media (max-width: 768px) {
        .radio-group, .checkbox-group {
          flex-direction: column;
          gap: 5px;
        }
        
        table {
          display: block;
          overflow-x: auto;
        }
      }
    </style>
  </head>

  <body>
    <div class="container">
      <header>
        <h1>Contact Registry</h1>
      </header>
      
      <!-- Section 1: Ordered List with Roman Numerals -->
      <section id="steps">
        <h2>Registration Steps</h2>
        <ol class="roman">
          <li>Fill out the registration form below</li>
          <li>Verify your email address</li>
          <li>Set up your profile information</li>
          <li>Add contacts to your address book</li>
          <li>Start managing your connections</li>
        </ol>
      </section>
      
      <!-- Section 2: External Image -->
      <section id="image">
        <h2>Team Collaboration</h2>
        <img src="https://images.pexels.com/photos/3184338/pexels-photo-3184338.jpeg" 
             alt="Team members collaborating on a project at a wooden table with laptops and papers" 
             title="Team Collaboration">
      </section>
      
      <!-- Section 3: Table of Contacts -->
      <section id="contacts">
        <h2>Contact Examples</h2>
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
              <td>John Doe</td>
              <td>123 Main St, New York, NY</td>
              <td>(555) 123-4567</td>
              <td>john.doe@example.com</td>
            </tr>
            <tr>
              <td>Jane Smith</td>
              <td>456 Park Ave, Boston, MA</td>
              <td>(555) 987-6543</td>
              <td>jane.smith@example.com</td>
            </tr>
            <tr>
              <td>Robert Johnson</td>
              <td>789 Oak Dr, San Francisco, CA</td>
              <td>(555) 456-7890</td>
              <td>robert.j@example.com</td>
            </tr>
            <tr>
              <td>Emily Davis</td>
              <td>321 Pine St, Seattle, WA</td>
              <td>(555) 321-7654</td>
              <td>emily.d@example.com</td>
            </tr>
            <tr>
              <td>Michael Wilson</td>
              <td>654 Cedar Rd, Austin, TX</td>
              <td>(555) 654-3210</td>
              <td>michael.w@example.com</td>
            </tr>
          </tbody>
        </table>
      </section>
      
      <!-- Section 4: Registration Form -->
      <section id="registration">
        <h2>Register Now</h2>
        <form action="#" method="POST">
          <!-- Basic Information -->
          <div class="form-group">
            <label for="fullname">Full Name <span style="color: red;">*</span></label>
            <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required>
          </div>
          
          <div class="form-group">
            <label for="email">Email Address <span style="color: red;">*</span></label>
            <input type="email" id="email" name="email" placeholder="you@example.com" required>
          </div>
          
          <div class="form-group">
            <label for="password">Password <span style="color: red;">*</span></label>
            <input type="password" id="password" name="password" placeholder="Choose a strong password" minlength="8" required>
            <small>Minimum 8 characters</small>
          </div>
          
          <div class="form-group">
            <label for="birthdate">Date of Birth</label>
            <input type="date" id="birthdate" name="birthdate">
          </div>
          
          <!-- Dropdown Menu -->
          <div class="form-group">
            <label for="occupation">Occupation</label>
            <select id="occupation" name="occupation">
              <option value="">-- Select your occupation --</option>
              <option value="student">Student</option>
              <option value="employed">Employed</option>
              <option value="self-employed">Self-Employed</option>
              <option value="unemployed">Unemployed</option>
              <option value="retired">Retired</option>
            </select>
          </div>
          
          <!-- Radio Buttons -->
          <div class="form-group">
            <label>Communication Preference <span style="color: red;">*</span></label>
            <div class="radio-group">
              <label>
                <input type="radio" name="communication" value="email" required checked> Email
              </label>
              <label>
                <input type="radio" name="communication" value="phone" required> Phone
              </label>
              <label>
                <input type="radio" name="communication" value="both" required> Both
              </label>
            </div>
          </div>
          
          <!-- Checkboxes -->
          <div class="form-group">
            <label>Interests (Select all that apply)</label>
            <div class="checkbox-group">
              <label>
                <input type="checkbox" name="interests" value="technology"> Technology
              </label>
              <label>
                <input type="checkbox" name="interests" value="business"> Business
              </label>
              <label>
                <input type="checkbox" name="interests" value="health"> Health & Wellness
              </label>
              <label>
                <input type="checkbox" name="interests" value="education"> Education
              </label>
            </div>
          </div>
          
          <!-- Submit Button -->
          <button type="submit">Register</button>
        </form>
      </section>
    </div>
    
    <!-- IMPORTANT: DO NOT REMOVE THIS SCRIPT TAG OR THIS VERY COMMENT! -->
    <script src="https://cdn.gpteng.co/gptengineer.js" type="module"></script>
    <script type="module" src="/src/main.tsx"></script>
  </body>
</html>

