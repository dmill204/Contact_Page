<section id="Contact">
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
    <button id="themeToggle">Toggle Theme</button>

  <script>
    const body = document.body;
    const themeToggle = document.getElementById('themeToggle');

    themeToggle.addEventListener('click', () => {
      body.classList.toggle('dark-mode');
    });
  </script>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="https://dmill204.github.io/Web_Page/">Home</a></li>
                <li><a href="https://dmill204.github.io/About_Page/">About</a></li>
                <li><a href="https://dmill204.github.io/Contact_Page/">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="input_name"> 
            <input type="text" name="name" id="input_name" placeholder="Enter your name here" required>
        </div>
        <div class="input_email">
            <input type="email" name="email" id="input_email" placeholder="Enter your email here" required>
        </div>
        <p>Enter any questions or remarks you have for me below:</p>
        <div class="text_area">
            <textarea name="message" id="message_by_user" cols="25" rows="10" placeholder="Message" required>
            </textarea>
        </div>
        <div class="submit_the_form">
            <button type="submit" name="submit_btn" id="submit_the_form">Submit
            </button>
        </div>
    </main>
    <footer>
        <p></p>
        <p>For any other information or questions that you may have please contact me directly at:</p>
        <p>dmill204@student.kennesaw.edu</p>
        <p>    </p> 
        <p>You call also submit a form by clicking below:</p>
        <li><a href="http://localhost:3000">Form</a></li>
    </footer>
</body>
</html>
</section>
