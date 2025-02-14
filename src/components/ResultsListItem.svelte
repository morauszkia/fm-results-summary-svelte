<script>
  const { className, iconPath, category, score } = $props();
  const iconUrl = new URL(`../assets/images/${iconPath}`, import.meta.url).href;
</script>

<li class={className}>
  <span class="category">
    <img src={iconUrl} alt={`${category} icon`} />
    {category}
  </span>
  <span class="score"><strong>{score}</strong> / 100 </span>
</li>
