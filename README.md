<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Profile Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #3b82f6, #22c55e);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            flex-direction: column;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 600px;
            text-align: center;
        }
        .profile {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }
        .profile img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        .info-box {
            background: #f8f8f8;
            padding: 10px;
            border-radius: 5px;
            margin-top: 10px;
            text-align: left;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        td {
            padding: 8px;
            border-bottom: 1px solid #ddd;
        }
        .social-icons {
            margin-top: 15px;
        }
        .social-icons a {
            margin: 0 10px;
            text-decoration: none;
            font-size: 24px;
            color: #333;
        }
    </style>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
    <h2 style="color: white;">Student Profile Page </h2>
    <div class="container">
        <div class="profile">
            <img src="https://scontent.fhan17-1.fna.fbcdn.net/v/t39.30808-6/473581934_1369664894033804_3150353931184964676_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=UyOE7U0TbQMQ7kNvgGBwf_U&_nc_oc=Adicj_MbXUpNoSTOkyRy_p6jQxNDPiDfiwe1YmrWRQq_EUTcl8i1qMUOEIVLOcx3nMY&_nc_zt=23&_nc_ht=scontent.fhan17-1.fna&_nc_gid=AWzQDQ6Kpp1jawvnT499tLl&oh=00_AYD3og5jF9LI4KbnPUlHhuToBeBUFaViHglGAX5xDC0HFw&oe=67AA7E42" alt="Student Profile Picture">
            <h3>Nguyễn Hoàng Phương Thảo</h3>
            <p><strong>Student ID:</strong> 19052007 </p>
            <p><strong>Class:</strong> 12A1.2</p>
        </div>
        <div class="info-box">
            <h4>General Information</h4>
            <table>
                <tr><td><strong>Gender</strong></td><td>Female</td></tr>
                <tr><td><strong>Birthday</strong></td><td>19/05/2007</td></tr>
                <tr><td><strong>Blood</strong></td><td>B</td></tr>
            </table>
        </div>
        <div class="info-box">
            <h4>My Social Network</h4>
        </div>
        <div class="social-icons">
      <a href="https://www.facebook.com/thao.nguyen.72043/" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
        <path d="M8.277 1.067c-3.15 0-5.21 1.803-5.21 5.114v2.652H.89v2.788h2.178v5.065h2.875V11.62h2.11l.335-2.787H5.943V6.18c0-.797.223-1.34 1.377-1.34h1.47V2.292c-.256-.034-1.139-.132-2.152-.132z"/>
    </svg>
</a>


 <a href="https://www.instagram.com/_phuongthaoo._/" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
  <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"/>
</svg>
</a>

 <a href="https://www.threads.net/@_phuongthaoo._" target="_blank">
   <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-threads" viewBox="0 0 16 16">
  <path d="M6.321 6.016c-.27-.18-1.166-.802-1.166-.802.756-1.081 1.753-1.502 3.132-1.502.975 0 1.803.327 2.394.948s.928 1.509 1.005 2.644q.492.207.905.484c1.109.745 1.719 1.86 1.719 3.137 0 2.716-2.226 5.075-6.256 5.075C4.594 16 1 13.987 1 7.994 1 2.034 4.482 0 8.044 0 9.69 0 13.55.243 15 5.036l-1.36.353C12.516 1.974 10.163 1.43 8.006 1.43c-3.565 0-5.582 2.171-5.582 6.79 0 4.143 2.254 6.343 5.63 6.343 2.777 0 4.847-1.443 4.847-3.556 0-1.438-1.208-2.127-1.27-2.127-.236 1.234-.868 3.31-3.644 3.31-1.618 0-3.013-1.118-3.013-2.582 0-2.09 1.984-2.847 3.55-2.847.586 0 1.294.04 1.663.114 0-.637-.54-1.728-1.9-1.728-1.25 0-1.566.405-1.967.868ZM8.716 8.19c-2.04 0-2.304.87-2.304 1.416 0 .878 1.043 1.168 1.6 1.168 1.02 0 2.067-.282 2.232-2.423a6.2 6.2 0 0 0-1.528-.161"/>
</svg>
</a>



        </div>
         <section>
     <h4>Send a message for me</h4>
      <form action="submit_form.php" method="post">
        <input type="text" id="name" name="name" placeholder="Send me a message" required>
        
        <button type="submit">Send!</button>
      </form>
   </section>
   
  <section>
  <h3> my favourite pet=)) </h3>
   <video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
  </section>
   

    </div>
   
       
</body>
</html>
