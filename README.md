# Excersize-Assignment.1
web technology assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Tiffin:wght@300&display=swap">
    <title>Typography Exercise</title>
</head>
<body>

<div class="container">
    <div class="column example">
        <p>This Is My Assignment On Web Typography And Or Web Technology.</p>
    </div>
</div>

</body>
</html>
/* Reset some default margin and padding */
body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

/* Apply a basic style to the body */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; /* Local fallback fonts */
}

/* Style the container */
.container {
    display: flex;
}

/* Style the column */
.column {
    flex: 1;
    margin: 10px;
    padding: 20px;
    border: 1px solid #ccc;
}

/* Font styles for the example class */
.example {
    font-family: "Tiffin", sans-serif;
    font-size: 18px;
    font-weight: 300;
    color: #333;
}
