<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>My Profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="card">
    <img src="foto.jpg" alt="Foto Profil" class="avatar">

    <h1>Nama Kamu</h1>
    <p class="subtitle">Web Developer | Student | Freelancer</p>

    <p class="bio">
        Halo! Saya adalah seseorang yang tertarik dengan dunia teknologi,
        pemrograman, dan desain web.
    </p>

    <div class="links">
        <a href="https://github.com/username" target="_blank">GitHub</a>
        <a href="https://instagram.com/username" target="_blank">Instagram</a>
        <a href="mailto:emailkamu@gmail.com">Email</a>
    </div>
</div>
body {
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: linear-gradient(135deg, #667eea, #764ba2);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.card {
    background: white;
    width: 320px;
    padding: 25px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
}

.avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 15px;
}

h1 {
    margin: 10px 0 5px;
}

.subtitle {
    color: #777;
    font-size: 14px;
}

.bio {
    font-size: 14px;
    margin: 15px 0;
    color: #444;
}

.links a {
    display: block;
    text-decoration: none;
    background: #667eea;
    color: white;
    padding: 10px;
    margin: 8px 0;
    border-radius: 8px;
    transition: 0.3s;
}

.links a:hover {
    background: #764ba2;
}

</body>
</html>
