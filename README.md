<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADEWOLE'S PORTFOLIO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .project-list {
            list-style-type: none;
            padding: 0;
        }
        .project-list li {
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            background-color: #e9e9e9;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        .project-list li img {
            width: 200px;
            height: 200px;
            margin-bottom: 20px;
            border-radius: 8px;
        }
        .project-list li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .project-list li a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>ADEWOLE BENJAMIN OYEDIRAN</h1>
    <ul class="project-list">
        <!-- Example project item -->
        <li>
            <a href="adewole_oyediran_portfolio/image">
                Project One: Investigating Netflix Movies
            </a>
            <p>
                This project is part of the DataCamp course and involves conducting an exploratory data analysis on Netflix movies to gain insights into their distribution, duration, and trends over the years. The analysis involved:
            </p>
            <ul>
                <li>Data loading</li>
                <li>Filtering</li>
                <li>Visualization</li>
                <li>Interpretation using Python and its libraries</li>
            </ul>
            <img src="adewole_oyediran_portfolio/image" alt="Project One Image">
        </li>
        <!-- Additional project -->
        <li>
            <a href="https://github.com/AdewoleBenjaminOyediran/project-two">
                Project Two: Stock Market Analysis
            </a>
            <p>
                This project involves analyzing historical stock market data to identify trends and make predictions. The project includes:
            </p>
            <ul>
                <li>Data collection from various sources</li>
                <li>Data preprocessing</li>
                <li>Statistical analysis</li>
                <li>Machine learning models using Python</li>
            </ul>
            <img src="https://via.placeholder.com/200" alt="Project Two Image">
        </li>
    </ul>
</div>

</body>
</html>
