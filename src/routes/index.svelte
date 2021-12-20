<script>
import front from "./front.css?inline"
if (import.meta.hot) {
        
        import.meta.hot.on("vite:beforeUpdate", (data2) => {
            console.log("vite before update");
            alert(JSON.stringify(data2))
        })
    }
</script>
{front}
<div class="front">This should have black color (css is inlined)</div>
<h1>Welcome to SvelteKit</h1>

<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
