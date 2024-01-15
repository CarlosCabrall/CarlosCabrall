<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Adicione estilos de animação aqui */
    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Aplica a animação à classe animate-element */
    .animate-element {
      animation: fadeIn 1s ease-in-out;
    }
  </style>
</head>
<body>

<div class="animate-element">
  <strong>Carlos Cabral</strong>
  Analista de Suporte Pleno | Desenvolvedor de Sistemas

  <p class="animate-element">
    Habilidades Técnicas:
    Front-end: HTML, CSS, JavaScript, React, Angular
    Sistemas Operacionais: Linux
    Banco de Dados: MySQL
    QA: Testes de Software
  </p>

  <p class="animate-element">
    Habilidades:
    - ![HTML](https://img.shields.io/badge/-HTML-orange)
    - ![CSS](https://img.shields.io/badge/-CSS-blue)
    - ![JavaScript](https://img.shields.io/badge/-JavaScript-yellow)
    - ![React](https://img.shields.io/badge/-React-blueviolet)
    - ![Angular](https://img.shields.io/badge/-Angular-red)
    - ![Linux](https://img.shields.io/badge/-Linux-lightgrey)
    - ![MySQL](https://img.shields.io/badge/-MySQL-blue)
  </p>

  <p class="animate-element">
    Experiência Profissional:
    Analista de Suporte Pleno na Empresa XYZ
    Período: 01/11/2023 - Atual
  </p>
</div>

<script>
  // Adicione a classe animate-element aos elementos após um atraso
  document.addEventListener("DOMContentLoaded", function() {
    setTimeout(function() {
      document.querySelectorAll('.animate-element').forEach(function(element) {
        element.classList.add('animate-element');
      });
    }, 1000);
  });
</script>

</body>
</html>
