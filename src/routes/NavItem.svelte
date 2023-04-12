<script lang="ts">
    export let href: string= '#';
</script>

<li>
    <a {href} class="flex flex-col items-center">
        <slot />
    </a>
</li>