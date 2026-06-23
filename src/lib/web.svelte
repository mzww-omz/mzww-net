<script>
    let { linkUrl, linkColor, darkModeColor, linkText } = $props()
    let actualColor = $derived(
        darkModeColor ?? linkColor
    );
</script>

<a href={linkUrl} class="text-2xl md:text-2xl relative after:absolute after:left-0 after:bottom-[2px] after:h-[2px] after:w-0 after:rounded-full after:bg-current after:transition-all after:duration-200 hover:after:w-full" style={`color: ${actualColor}`} aria-label={linkText}>&#62; {linkText}</a><br>