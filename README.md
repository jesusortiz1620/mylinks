# mylinks 
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=jesus
user.email=jesusangelortiz.567@gmail.com

M@DESKTOP-908EBUT MINGW64 ~/Desktop
$ git config --global user.name "jesus"

M@DESKTOP-908EBUT MINGW64 ~/Desktop
$ git config --global user.email "jesusangelortiz.567@gmail.com"   

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profile Card</title>
  <style>
    body {
      background: #111;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      color: #fff;
    }
    .card {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 12px;
      text-align: center;
      width: 300px;
    }
    .card img {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      margin-bottom: 10px;
    }
    .card h2 {
      margin: 5px 0;
    }
    .card p {
      font-size: 14px;
      color: #aaa;
      margin: 8px 0 16px;
    }
    .card a {
      display: block;
      background: #333;
      color: #fff;
      text-decoration: none;
      padding: 10px;
      border-radius: 6px;
      margin: 6px 0;
      transition: background 0.2s;
    }
    .card a:hover {
      background: #555;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=200" alt="Foto de perfil">
    <h2>Jessica Randall</h2>
    <p>London, United Kingdom</p>
    <p>"Front-end developer and avid reader."</p>
    <a href="#">GitHub</a>
    <a href="#">Frontend Mentor</a>
    <a href="#">LinkedIn</a>
    <a href="#">Twitter</a>
    <a href="#">Instagram</a>
  </div>
</body>
</html>
