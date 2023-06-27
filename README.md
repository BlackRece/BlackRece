### Hi there 👋
I make games.

## Experiment
<canvas id="animationCanvas" width="400" height="200"></canvas>

<script>
const canvas = document.getElementById('animationCanvas');
const context = canvas.getContext('2d');
let x = 0;

function animate() {
  context.clearRect(0, 0, canvas.width, canvas.height);
  context.fillRect(x, 80, 50, 50);
  x += 1;
  if (x > canvas.width) {
    x = 0;
  }
  requestAnimationFrame(animate);
}

animate();
</script>
<!--
**BlackRece/BlackRece** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
