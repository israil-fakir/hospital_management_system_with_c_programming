<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Hospital Management System - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 2em;
            background-color: #f4f4f9;
            color: #333;
        }
        h1, h2 {
            color: #2c3e50;
        }
        pre {
            background: #ecf0f1;
            padding: 1em;
            border-radius: 5px;
            overflow-x: auto;
        }
        code {
            color: #c0392b;
        }
        ul {
            margin-top: 0.5em;
        }
        footer {
            margin-top: 3em;
            font-size: 0.9em;
            color: #777;
        }
    </style>
</head>
<body>
    <h1>Hospital Management System</h1>
    <p>This is a simple console-based Hospital Management System written in C. It allows the user to manage patients and doctors with basic file operations using binary files.</p>

    <h2>Features</h2>
    <ul>
        <li>Admit new patients</li>
        <li>View patient list</li>
        <li>Discharge patients</li>
        <li>Add doctor information</li>
        <li>View doctor list</li>
    </ul>

    <h2>Files Used</h2>
    <ul>
        <li><code>patient.txt</code> – Stores patient records</li>
        <li><code>doctor.txt</code> – Stores doctor records</li>
    </ul>

    <h2>How to Compile and Run</h2>
    <pre><code>gcc hospital.c -o hospital
./hospital</code></pre>

    <h2>Dependencies</h2>
    <ul>
        <li>Standard C libraries: <code>stdio.h</code>, <code>stdlib.h</code>, <code>time.h</code></li>
        <li>Works on any standard C compiler</li>
    </ul>

    <h2>Notes</h2>
    <ul>
        <li>Make sure to have write permissions in the directory to create and modify <code>.txt</code> files.</li>
        <li>Use arrow keys or enter to navigate the menu (platform-dependent behavior).</li>
    </ul>

    <footer>
        &copy; 2025 Hospital Management System | Built in C for educational purposes.
    </footer>
</body>
</html>
