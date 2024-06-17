<div>
<h1>EMAIL VALIDATOR</h1>
   <p>
      This repository contains the code for a GUI that validates email addresses from an uploaded Excel file and
      sorts them into two separate downloadable Excel files: <code>ValidEmails.xlsx</code> and <code>DisposableEmails.xlsx</code>.
   </p>

<h3>Features</h3>
<p>
   1. Validates email addresses against common email formatting rules.<br>
   2. Identifies disposable email addresses from a public blacklist.<br>
   3. Sorts validated emails into two downloadable Excel files:<br>
      a. <code>ValidEmails.xlsx</code> - Contains email addresses classified as valid.<br>
      b. <code>DisposableEmails.xlsx</code> - Contains email addresses classified as disposable.
</p>

<h3>Dependencies</h3>
<p>
   This application may require additional libraries depending on the chosen programming language. Please refer to
   the <code>requirements.txt</code> (Python) file for specific dependencies.
</p>

<h3>Contributing</h3>
<p>
   We welcome contributions to this project! Please refer to the CONTRIBUTING.md file for guidelines on submitting
   pull requests.
</p>

<h3>Usage</h3>
<p>
   Clone this repository:<br>
   <code>git clone https://github.com/your-username/email-validator.git</code>
   
   Install dependencies (if applicable):
   <code>pip install -r requirements.txt</code> <br>

   The application will prompt you to upload an Excel file containing email addresses.

   The application will process the file and generate two downloadable Excel files: <br>
   - <code>ValidEmails.xlsx</code>  <br>and<br>
   - <code>DisposableEmails.xlsx</code>
</p>

</div>

<div>
   <h4>Update:</h4>
   <p>
      <code>main.py</code> - Contains the updated version of <code>script.py</code> and saves the separated files into root directory(C: drive in case of Windows).
   </p>
</div>

