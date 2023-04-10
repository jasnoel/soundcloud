<script lang="ts">
    export let href: string= '#';
</script>

<li>
    <a {href} class="flex flex-wrap justify-center">
        <slot />
    </a>
</li>