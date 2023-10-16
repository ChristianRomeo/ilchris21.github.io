<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
  <style>
    .background {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-image: url(https://demo.reactresume.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fheader-background.371f2b47.webp&w=1920&q=100);
      background-size: cover;
      background-position: center;
    }
    .overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 500px;
      height: 450px;
      background-color: rgba(0, 0, 0, 0.6);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      justify-content: space-around;
      align-items: center;
      z-index: 1;
      white-space: normal;
      padding: 30px;
      color: white;
      backdrop-filter: blur(4px);
    }
     .img-button {
      width: 60px;
      height: 60px;
      border: none;
      background: none;
      transition: transform 0.1s ease-in-out;
    }
    .img-button:active {
      transform: scale(0.95); /* Add this line */
    }
    .img-button img {
      width: 50%;
      height: auto;
      filter: invert(1);
      cursor: pointer;
    }
    .button {
      width: 50%;
      height: auto;
      border-radius: 20px;
      line-height: 50px;
      font-size: 19px;
    }
    .contact-button {
      background-color: transparent;
      border: 3px solid orange;
      text-align: center; 
      color: white;
      width: 170px;
      height: 60px;
      text-decoration: none;
    }
    .contact-button:hover {
      color: white;
      text-decoration: none;
    }
    .buttons {
      display: flex;
      gap: 20px;
    }
    @keyframes pressed {
    0% {
    transform: scale(1);
    }
    100% {
    transform: scale(0.5);
  }
  p {
  font-family: 'Khula ExtraBold', sans-serif;
  }
  </style>
</head>
<body>
  <div class="background"></div>
  <div class="overlay">
    <h1>I'm Chris.</h1>
    <p>I'm a software engineer with a passion for building innovative and user-friendly products. I have experience in a variety of programming languages and technologies, including Python, JavaScript, and React. I'm also skilled in cloud computing platforms such as AWS and Azure.<br><br>
    I'm currently looking for new opportunities to work on challenging and impactful projects. If you're interested in learning more about my work, please feel free to contact me.</p>
    <div>
      <button class="img-button" onclick="window.location.href='https://github.com/ChristianRomeo';">
        <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub">
      </button>
      <button class="img-button" onclick="window.location.href='https://www.linkedin.com/in/ilchris21/';">
        <img src="https://cdn-icons-png.flaticon.com/512/1384/1384046.png" alt="Linkedin">
      </button>
      <button class="img-button" onclick="window.location.href='https://www.instagram.com/ilchris21/';">
        <img src="https://cdn-icons-png.flaticon.com/512/717/717392.png" alt="Instagram">
      </button>
    </div>
    <div class="buttons">
      <a href="CV_ChristianRomeo.pdf" class="button">  
        <img src="https://cdn-icons-png.flaticon.com/512/6186/6186195.png" width="60" height="60">
      </a>
    </div>
  </div>
</body>
</html>
