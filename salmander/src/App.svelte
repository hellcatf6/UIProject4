<body>
<main id="background">
  <p id="displayPop">
    Hello!
  </p>
  <div>
    <button type="button" id="my">Start</button>
  </div>
</main>

<script>

  document.getElementById("my").addEventListener("click", displayPop);
  function displayPop()
  {
    document.getElementById("displayPop").innerHTML = "Nice job!";
  }
</script>
</body>