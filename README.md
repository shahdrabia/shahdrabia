<h3 align="center">
  <span style="font-family:monospace;">
    <span id="typewriter"></span>
  </span>
</h3>

<script>
  const text = "hi there , im shahd";
  let i = 0;
  function typing() {
    if (i < text.length) {
      document.getElementById("typewriter").innerHTML += text.charAt(i);
      i++;
      setTimeout(typing, 150);
    }
  }
  typing();
</script>
