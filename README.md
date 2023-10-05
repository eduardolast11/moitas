<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Xô xô</title>
  <style>
    * {
      margin: 0;
      padding: 0;
    }

    body {
      font-family: sans-serif;
      background-color: #000;
    }

    h1 {
      color: #fff;
      text-align: center;
      font-size: 4rem;
    }

    .letra {
      font-size: 2rem;
      color: #fff;
      text-transform: uppercase;
      font-weight: bold;
      width: 100px;
      height: 100px;
      display: inline-block;
      margin: 10px;
      background-color: #000;
      border-radius: 50%;
      animation: blink 1s infinite;
    }

    @keyframes blink {
      from {
        opacity: 1;
      }
      to {
        opacity: 0;
      }
    }
