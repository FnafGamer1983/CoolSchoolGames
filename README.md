<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>CoolSchoolGames</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');

  body {
    margin: 0;
    background-color: #1e1e1e; /* dark grey background */
    color: #2fa8ff; /* cool blue text */
    font-family: 'Montserrat', sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100vh;
    user-select: none;
  }
  h1 {
    margin-top: 40px;
    font-size: 3.5rem;
    text-shadow:
      0 0 10px #2fa8ff,
      0 0 20px #ff4500,
      0 0 30px #ff4500;
  }
  p {
    font-size: 1.2rem;
    margin: 5px 0 30px 0;
    color: #ccc;
  }
  nav {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    max-width: 900px;
  }
  a.button {
    background: linear-gradient(45deg, #2fa8ff, #ff4500);
