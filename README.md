<body>

  <h1>README: Save and Delete Functionality</h1>

  <div class="section">
    <h2>1. Save Functionality</h2>

    <p class="subheading">Fields and Form:</p>
    <ul>
      <li>Create a form with fields for <strong>Name</strong>, <strong>Age</strong>, <strong>Gender</strong>, <strong>Mobile Number</strong>, <strong>Qualification</strong>, and <strong>Address</strong>.</li>
      <li>Add a <strong>Save</strong> button to submit the form.</li>
      <li>Perform this task on the <strong>client side</strong> (do <u>not</u> use LocalStorage, SessionStorage, or a Database).</li>
    </ul>

    <p class="subheading">Validation:</p>
    <p>Use <strong>jQuery</strong> to ensure that all fields are filled out correctly before saving the data:</p>
    <ul>
      <li><strong>Name:</strong> Should not be empty.</li>
      <li><strong>Age:</strong> Input field with dropdown of <code>Y</code>, <code>M</code>, and <code>D</code>.</li>
      <li><strong>Gender:</strong> Ensure a valid selection (e.g., Male, Female, Other).</li>
      <li><strong>Mobile Number:</strong> Should be a valid phone number format.</li>
      <li><strong>Qualification:</strong> Should not be empty.</li>
      <li><strong>Address:</strong> Should not be empty.</li>
    </ul>

    <p class="subheading">Saving Data:</p>
    <ul>
      <li>On clicking the <strong>Save</strong> button, the data from the form should be captured.</li>
      <li>Use <strong>jQuery</strong> to append this data to a <strong>table below the form</strong>, displaying the user details.</li>
    </ul>
  </div>

  <div class="section">
    <h2>2. Deletion Functionality</h2>

    <p class="subheading">Delete Button:</p>
    <ul>
      <li>Each row in the table should have a <strong>Delete</strong> button.</li>
      <li>The Delete button should be added dynamically when a new row is created.</li>
    </ul>

    <p class="subheading">Row Removal:</p>
    <ul>
      <li>When the Delete button is clicked, use <strong>jQuery</strong> to remove the corresponding row from the table.</li>
    </ul>
  </div>

  <div class="section">
    <h2>3. Combining the Features</h2>

    <p class="subheading">Binding Data to Table:</p>
    <ul>
      <li>When the <strong>Save</strong> button is clicked and the form is validated, the data should be added as a new row in the table.</li>
      <li>Each row should include all the details entered in the form along with the <strong>Delete</strong> button.</li>
      <li>Ensure that the table is updated dynamically with each new entry.</li>
    </ul>
  </div>

</body>
