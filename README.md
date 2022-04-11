<style>
  body {
    background: #0e1013;
  }

  h1 {
    max-width: 480px;
    text-align: center;
    margin: 60px auto;
    font-family: 'Courier New', Courier, monospace;
    color: #fff;
  }

  h1::after {
    content: '|';
    opacity: 1;
    margin-left: 5px;
    display: inline-block;
    animation: blink .7s infinite;
  }

  @keyframes blink {
    0%, 100% {
      opacity: 1;
    }
    50% {
      opacity: 0;
    }
  }
</style>
<h1>### Hi 👋</h1>
 I'm Almir Junior recently graduated in Analysis and Development and looking for opportunities and collaboration in projects related to data science and deep learning.
- 🔭 I'm currently working with programming (besides, I'm improving my data structures and algorithms skills regularly).
- 🌱 I am currently learning Computer Vision and Deep Learning techniques.



[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/almir-libório-batista-junior-1105b7194) 
[<img src = "https://img.shields.io/badge/facebook-%231877F2.svg?&style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/USERNAME)
<script>
  function typeWriter(elemento) {
    const textoArray = elemento.innerHTML.split('');
    elemento.innerHTML = '';
    textoArray.forEach((letra, i) => {
      setTimeout(() => elemento.innerHTML += letra, 75 * i);
    });
  }

  // Se estiver tendo problemas com performance, utilize o FOR loop como abaixo no local do forEach
  // function typeWriter(elemento) {
  //   const textoArray = elemento.innerHTML.split('');
  //   elemento.innerHTML = '';
  //   for(let i = 0; i < textoArray.length; i++) {
  //     setTimeout(() => elemento.innerHTML += textoArray[i], 75 * i);
  //   }
  // }

  const titulo = document.querySelector('h1');
  typeWriter(titulo);
</script>
