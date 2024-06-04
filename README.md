

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thank You for My Birthday</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #FF70A6, #FF9770);
            color: #fff;
        }
        header {
            background-color: rgba(255, 255, 255, 0.8);
            color: #333;
            text-align: center;
            padding: 5px 0;
        }
        .container {
            max-width: 300px;
            margin: 5px auto;
            padding: 5px;
            background-color: rgba(1, 103,149, 0.8);
            border-radius: 4px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
        }
        h1, h2 {
            text-align: center;
            color: #333;
        }
        p {
            line-height: 1;
            margin-bottom: 10px;
        }
        .thanks-img {
            display: block;
            margin: 0 auto;
            max-width: 75%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: rgba(255, 255, 255, 0.8);
            color: #333;
            text-align: center;
            padding: 5px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        #emoticons {
            font-size: 12px;
            margin-top: 2px;
            text-align: center;
        }
        .animated {
            animation-duration: 2s;
            animation-fill-mode: both;
        }
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(-20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .fadeIn {
            animation-name: fadeIn;
        }
    </style>
</head>
<body>
    <header>
        <h1>Thank You for Making My Birthday Special!😍</h1>
    </header>

    <div class="container animated fadeIn">
        <form id="nameForm">
<p style="color: black;">
            <label for="name">Enter Your Name:</label><br></p>
            <input type="text" id="name" name="name" required><br><br>
            <button type="submit">Submit</button>
        </form>

        <div id="thankYouMessage" style="display:none;">
            <h2>Dear <span id="friendName"></span>,</h2>
            <p style="color: black;">Thank you for your warm wishes and for making my birthday so special! 🎉 Your friendship means the world to me, and I'm grateful to have you in my life. 🥳</p>
            <p style="color: black;">With love and gratitude, 😊</p>
            <p style="color:black;">VIJETH BK</p>
        </div>
    </div>
    <footer>
        <p>Thank you once again! 🙏</p>
<p>your response will be noted</p>
 <p>Created by MR_VLEGEND</p>
<a href="https://youtube.com/@thezaxoff?si=tuJKT5oCIFxXjwuU">MY    YOUTUBE CHANNEL</a>
    </footer>

    <script>
        document.getElementById('nameForm').addEventListener('submit', function(e) {
            e.preventDefault();
            var friendName = document.getElementById('name').value;
            document.getElementById('friendName').innerText = friendName;
            document.getElementById('nameForm').style.display = 'none';
            document.getElementById('thankYouMessage').style.display = 'block';
        });
    </script>
<p style="color: black;">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>User Response Storage</title>

<body>
<form id="responseForm">
  <label for="userResponse">Your Response:</label><br>
  <input type="text" id="userResponse" name="userResponse"><br><br>
  <button type="submit">Submit</button>
</form>

<script>
document.getElementById("responseForm").addEventListener("submit", function(event){
  event.preventDefault();
  var userResponse = document.getElementById("userResponse").value;
  localStorage.setItem("userResponse", userResponse);
  alert("Response stored successfully!");
});
</script>
</p>

</body>

</body>

</html>
