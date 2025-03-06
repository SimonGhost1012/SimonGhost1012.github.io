<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Docs Button</title>
    <style>
        .github-button {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 10px 5px; /* Adjusted padding */
            background-color: #0d1117;
            color: white;
            font-size: 15px;
            font-weight: bold;
            border-radius: 7px;
            text-decoration: none;
            transition: background-color 0.3s ease;
            max-width: 120px; /* Set a max width to avoid stretching */
            white-space: nowrap; /* Prevent text from wrapping */
            overflow: hidden; /* Hide any overflow if text exceeds width */
        }

        .github-button:hover {
            background-color: #ff0000;
        }

        .github-button img {
            width: 50px;
            margin-right: 15px;
        }
    </style>
</head>
<body>
    <a href="https://github.com/your-repository/docs" class="github-button">
        <img src="https://xy.vault.inc/static/media/gitBook.bb1fc946.png" alt="GitBook Logo">
        Docs
    </a>
</body>
</html>
