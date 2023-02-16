<script>
    import {onMount} from 'svelte';
    export let text = '';
    export let delay = 100;
    let animatedText = "";
    
    function animateText() {
      const letters = text.split("");
      let i = 0;
      
      const intervalId = setInterval(() => {
        if (i >= letters.length) {
          clearInterval(intervalId);
        } else {
          animatedText += letters[i];
          i++;
        }
      }, delay);
    }
    
    // Run the animation when the component is mounted
    onMount(() => {
    animateText();
    setInterval(() => {
      animatedText = "";
      animateText();
    }, 10000);
  });
  </script>
  
  <h2 style="">{animatedText}</h2>

  <style>
    h2 {
      justify-content: center;
      margin: 0 auto;
      color: white;
      font-weight:bolder;
      text-align:center;
      align-items:center;
      font-size: larger;
    }
  </style>