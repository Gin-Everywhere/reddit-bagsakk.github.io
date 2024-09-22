# reddit-bagsakk
Website Replication Assessment
<!--Button Symbols are made by ChatGPT-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reddit Vibe - Filipino Edition</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #dae0e6;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 60%;
            margin: 30px auto;
            background-color: #ffffff;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .header {
            margin-bottom: 20px;
            background-color: #ff4500;
            padding: 20px;
            color: #fff;
            border-radius: 5px;
            text-align: center;
        }
        h1 {
            font-size: 24px;
            margin: 0;
        }
        .nav {
            font-size: 14px;
            margin-top: 10px;
        }
        .nav a {
            color: #fff;
            margin-right: 10px;
            text-decoration: none;
        }
        .nav a:hover {
            text-decoration: underline;
        }
        .posts {
            list-style-type: none;
            padding: 0;
        }
        .post {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .votes {
            text-align: center;
            margin-right: 10px;
            font-size: 16px;
            color: #777;
        }
        .vote-button {
            display: block;
            width: 20px;
            height: 20px;
            background-color: transparent;
            border: none;
            cursor: pointer;
        }
        .vote-button svg {
            width: 100%;
            fill: #777;
        }
        .post a {
            color: #0079d3;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
        }
        .post a:hover {
            text-decoration: underline;
        }
        .post span {
            color: #777;
            font-size: 12px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Reddit: Filipino Edition</h1>
            <div class="nav">
                <a href="#">Hot</a> |
                <a href="#">New</a> |
                <a href="#">Top all-time</a> |
                <a href="#">Controversial</a>
            </div>
        </div>
        
        <ul class="posts">
            <li class="post">
                <div class="votes">
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l6 8H6z"/></svg>
                    </button>
                    52
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 20l-6-8h12z"/></svg>
                    </button>
                </div>
                <div>
                    <a href="#">Ninong Ry's Best Cooking Tips for Beginners</a> 
                    <span>(youtube.com)</span>
                </div>
            </li>
            <li class="post">
                <div class="votes">
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l6 8H6z"/></svg>
                    </button>
                    35
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 20l-6-8h12z"/></svg>
                    </button>
                </div>
                <div>
                    <a href="#">Chef JP Anglo on Modernizing Filipino Cuisine</a> 
                    <span>(pep.ph)</span>
                </div>
            </li>
            <li class="post">
                <div class="votes">
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l6 8H6z"/></svg>
                    </button>
                    44
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 20l-6-8h12z"/></svg>
                    </button>
                </div>
                <div>
                    <a href="#">Angat Buhay Projects: Building Better Communities</a> 
                    <span>(rappler.com)</span>
                </div>
            </li>
            <li class="post">
                <div class="votes">
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l6 8H6z"/></svg>
                    </button>
                    65
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 20l-6-8h12z"/></svg>
                    </button>
                </div>
                <div>
                    <a href="#">Martial Law in the Philippines: What You Should Know</a> 
                    <span>(philstar.com)</span>
                </div>
            </li>
            <li class="post">
                <div class="votes">
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l6 8H6z"/></svg>
                    </button>
                    27
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 20l-6-8h12z"/></svg>
                    </button>
                </div>
                <div>
                    <a href="#">Beginner’s Guide to Python Programming</a> 
                    <span>(tutorialspoint.com)</span>
                </div>
            </li>
            <li class="post">
                <div class="votes">
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l6 8H6z"/></svg>
                    </button>
                    38
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 20l-6-8h12z"/></svg>
                    </button>
                </div>
                <div>
                    <a href="#">5 Habits That Will Change Your Life This 2024</a> 
                    <span>(motivationspeak.com)</span>
                </div>
            </li>
            <li class="post">
                <div class="votes">
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l6 8H6z"/></svg>
                    </button>
                    22
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 20l-6-8h12z"/></svg>
                    </button>
                </div>
                <div>
                    <a href="#">Structural Engineering Principles Every Student Should Know</a> 
                    <span>(theconstructor.org)</span>
                </div>
            </li>
            <li class="post">
                <div class="votes">
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4l6 8H6z"/></svg>
                    </button>
                    36
                    <button class="vote-button">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 20l-6-8h12z"/></svg>
                    </button>
                </div>
                <div>
                    <a href="#">Software Engineering Vloggers in the Philippines</a> 
                    <span>(techvlogph.com)</span>
                </div>
            </li>
        </ul>
    </div>
</body>
</html>
