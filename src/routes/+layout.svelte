<script lang="ts">
    import "../app.css";
    import MobileNav from './MobileNav.svelte';
    import Nav from './Nav.svelte';
</script>

<Nav />
<slot></slot>
<MobileNav />