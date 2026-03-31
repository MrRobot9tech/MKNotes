<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Department of Computer Application - GOVT. Degree College Udhampur</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* Basic reset */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        header {
            background: #2c3e50;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        .logo {
            font-size: 2.5rem;
            margin: 0;
        }

        .logo span {
            color: #f39c12;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 15px 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav ul li {
            margin: 0 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        .search-bar {
            text-align: right;
            margin-top: 10px;
            margin-right: 30px;
        }

        .search-bar input {
            padding: 8px;
            width: 200px;
        }

        .search-bar button {
            padding: 8px 12px;
            background: #f39c12;
            border: none;
            color: #fff;
            cursor: pointer;
        }

        .container {
            width: 90%;
            margin: auto;
        }

        .notes-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
            justify-content: center;
        }

        .notes-card {
            background: #ecf0f1;
            border-radius: 8px;
            overflow: hidden;
            width: 200px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .notes-card img {
            width: 100%;
            height: auto;
        }

        .notes-info {
            padding: 10px;
        }

        .notes-info h3 {
            margin: 10px 0;
            font-size: 1.1rem;
        }

        .notes-info a {
            text-decoration: none;
            color: #2980b9;
            font-weight: bold;
        }

        footer {
            background: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1 class="logo">Computer<span>Notes</span></h1>
            <div class="search-bar">
                <input type="text" placeholder="Search notes...">
                <button>Search</button>
            </div>
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contribute Upload</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .contribute-btn {
      background-color: #007BFF; /* Blue color */
      color: white;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      margin: 10px;
      float: left; /* Align to left */
    }
    .dropdown {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 160px;
      border: 1px solid #ccc;
      z-index: 1;
    }
    .dropdown a {
      display: block;
      padding: 8px 12px;
      text-decoration: none;
      color: black;
    }
    .dropdown a:hover {
      background-color: #ddd;
    }
    #fileUpload {
      display: none; /* Hidden until triggered */
    }
  </style>
</head>
<body>

  <!-- Contribute Button -->
  <button class="contribute-btn" onclick="toggleDropdown()">Contribute</button>

  <!-- Dropdown Menu -->
  <div id="dropdownMenu" class="dropdown">
    <a href="#" onclick="triggerUpload('sem1')">sem1</a>
    <a href="#" onclick="triggerUpload('sem2')">sem2</a>
    <a href="#" onclick="triggerUpload('sem3')">sem3</a>
    <a href="#" onclick="triggerUpload('sem4')">sem4</a>
    <a href="#" onclick="triggerUpload('sem5')">sem5</a>
    <a href="#" onclick="triggerUpload('sem6')">sem6</a>
    <a href="#" onclick="triggerUpload('sem7')">sem7</a>
    <a href="#" onclick="triggerUpload('sem8')">sem8</a>
  </div>

  <!-- Hidden File Upload -->
  <input type="file" id="fileUpload" />

  <script>
    function toggleDropdown() {
      const menu = document.getElementById("dropdownMenu");
      menu.style.display = menu.style.display === "block" ? "none" : "block";
    }

    function triggerUpload(semester) {
      // Close dropdown
      document.getElementById("dropdownMenu").style.display = "none";
      // Trigger file input click
      const fileInput = document.getElementById("fileUpload");
      fileInput.click();

      // Optional: handle file selection
      fileInput.onchange = () => {
        if (fileInput.files.length > 0) {
          alert("You selected a file for " + semester + ": " + fileInput.files[0].name);
        }
      };
    }
  </script>

</body>
</html>


  <script>
    function toggleDropdown() {
      const menu = document.getElementById("dropdownMenu");
      menu.style.display = menu.style.display === "block" ? "none" : "block";
    }
  </script>


            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Semester First</a></li>
                    <li><a href="#">Semester Second</a></li>
                    <li><a href="#">Semester Third</a></li>
                    <li><a href="#">Semester Fourth</a></li>
                    <li><a href="#">Semester Fifth</a></li>
                    <li><a href="#">Semester Sixth</a></li>
                    <li><a href="#">Semester Seventh</a></li>
                    <li><a href="#">Semester Eighth</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <section class="notes-grid">
            <!-- Notes Card 1 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>Computer fundamentals and office tools.1</h3>
                    <p><a href="notes/intro_programming.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
            <!-- Notes Card 2 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>Fundamentals of Internet.1</h3>
                    <p><a href="notes/dbms.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
            <!-- Notes Card 3 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>C Programming.1</h3>
                    <p><a href="notes/os_concepts.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
<!-- Notes Card 4 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>PC Assembly and Installation.1</h3>
                    <p><a href="notes/intro_programming.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
<!-- Notes Card 5 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>Data Structures using C.1</h3>
                    <p><a href="notes/intro_programming.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
<!-- Notes Card 6 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>Operating System.1</h3>
                    <p><a href="notes/intro_programming.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
<!-- Notes Card 7 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>Computer Networks.1</h3>
                    <p><a href="notes/intro_programming.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
<!-- Notes Card 8 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>Mathematical foundation of Computer Science.1</h3>
                    <p><a href="notes/intro_programming.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
<!-- Notes Card 9 -->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>OOPs using C++.1</h3>
                    <p><a href="notes/intro_programming.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>
<!-- Notes Card 10-->
            <div class="notes-card">
                <img src="https://via.placeholder.com/200x300" alt="Notes Thumbnail">
                <div class="notes-info">
                    <h3>Web Technologies.1</h3>
                    <p><a href="notes/intro_programming.pdf" target="_blank">Download PDF</a></p>
                </div>
            </div>


 
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Mk. For educational purposes only.</p>
    </footer>
</body>
</html>


