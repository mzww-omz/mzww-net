<script>
    const { lang, langImg, percentage } = $props()
</script>

<div class="flex flex-col items-center gap-1 w-20">
    <img
        alt={lang}
        class="w-20 h-20"
        src={langImg}
    />
    <span class="text-md text-gray-500">{percentage}</span>
</div>