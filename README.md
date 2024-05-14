<link rel="stylesheet" href="style.css">
<div class="title">
MR RUBW
</div>
<script>
    const titleEle = document.querySelector('.title');

document.addEventListener(
  'mousemove',
  (event) => {
    const { pageX, pageY } = event;
    const x = ((10 * pageX) / 570) + 40;
    const y = ((10 * pageY) / 570) + 40;

    titleEle.style.backgroundPosition = `${x}% ${y}%`;
  },
);
</script>
