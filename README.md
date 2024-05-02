<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zoro Gallery</title>
    <link rel="stylesheet" href="zorogalstyles.css">
    <styles>
    * {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: sans-serif;
  background-image:url('zorobg.jpg');
  background-repeat: repeat;
  background-attachment: fixed;
  background-size:50% 50%;
}

.header {
  text-align: center;
  text-transform: uppercase;
  padding: 32px;
  color: #a0e7bb;
  font-family: Helvetica;
  font-size: 150%;
}

.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  align-content: center;
  gap: 50px;
  max-width: 1400px;
  margin: 0 auto;
  padding: 20px 10px;
}

.gallery img {
  width: 90%;
  max-width: 350px;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
}

.gallery::after {
  content: "";
  width: 350px;
}
</styles>
  </head>
  <body>
    <header class="header">
      <h1>Zoro Gallery</h1>
    </header>
    <div class="gallery">
      <img src="zoro1.jpg">
      <img src="zoro2.jpg">
      <img src="zoro3.jpg">
      <img src="zoro4.jpg">
      <img src="zoro5.jpg">
      <img src="zoro6.jpg">
    </div>
  </body>
</html>
