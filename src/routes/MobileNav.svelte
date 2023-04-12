<script lang="ts">
	import NavItem from './NavItem.svelte';
</script>

<nav class="text-xs fixed bottom-0 w-full">
	<ul class="mx-2 my-2 flex justify-around">
		<NavItem href="/home">
			<svg
				class="NavBar_IconDefaultColor__2SEUJ"
				height="32"
				viewBox="0 0 32 32"
				xmlns="http://www.w3.org/2000/svg"
				aria-hidden="false"
				><title>Home</title><path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M16 3.078 30.436 13.39l-.872 1.22L16 4.922 2.436 14.61l-.872-1.22L16 3.078Z"
					fill="currentColor"
				/><path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M4.25 27.5V12h1.5v15.25h5.5V21a4.75 4.75 0 0 1 9.5 0v6.25h5.5V12h1.5v15.5c0 .69-.56 1.25-1.25 1.25h-7.25V21a3.25 3.25 0 0 0-6.5 0v7.75H5.5c-.69 0-1.25-.56-1.25-1.25Z"
					fill="currentColor"
				/></svg
			>
			<p>Home</p>
		</NavItem>
		<NavItem href="/feed">
			<svg
				class="NavBar_IconDefaultColor__2SEUJ"
				height="32"
				viewBox="0 0 32 32"
				xmlns="http://www.w3.org/2000/svg"
				aria-hidden="false"
				><title>Feed</title><path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M4.25 14.5c0-.69.56-1.25 1.25-1.25h21c.69 0 1.25.56 1.25 1.25v13c0 .69-.56 1.25-1.25 1.25h-21c-.69 0-1.25-.56-1.25-1.25v-13Zm1.5.25v12.5h20.5v-12.5H5.75ZM8.25 9A.75.75 0 0 1 9 8.25h14a.75.75 0 0 1 0 1.5H9A.75.75 0 0 1 8.25 9ZM11.25 4a.75.75 0 0 1 .75-.75h8a.75.75 0 0 1 0 1.5h-8a.75.75 0 0 1-.75-.75Z"
					fill="currentColor"
				/></svg
			>
			<p>Feed</p>
		</NavItem>
		<NavItem>
			<svg
				class="NavBar_IconDefaultColor__2SEUJ"
				height="32"
				viewBox="0 0 32 32"
				xmlns="http://www.w3.org/2000/svg"
				aria-hidden="false"
				><title>Search</title><path
					d="M13 3.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75a9.706 9.706 0 0 0 4.671-1.19l6.977 6.977a2.75 2.75 0 0 0 3.89-3.889l-6.978-6.977A9.706 9.706 0 0 0 22.75 13c0-5.385-4.365-9.75-9.75-9.75ZM4.75 13a8.25 8.25 0 1 1 16.5 0 8.25 8.25 0 0 1-16.5 0Zm15.972 5.954 6.755 6.755a1.25 1.25 0 1 1-1.768 1.768l-6.755-6.755a9.812 9.812 0 0 0 1.768-1.768Z"
					fill="currentColor"
				/></svg
			>
			<p>Search</p>
		</NavItem>
		<NavItem>
			<svg
				class="NavBar_IconDefaultColor__2SEUJ"
				height="32"
				viewBox="0 0 32 32"
				xmlns="http://www.w3.org/2000/svg"
				aria-hidden="false"
				><title>Library</title><path
					d="M2.25 7a2.75 2.75 0 0 1 5.5 0v18a2.75 2.75 0 1 1-5.5 0V7ZM5 5.75c-.69 0-1.25.56-1.25 1.25v18a1.25 1.25 0 1 0 2.5 0V7c0-.69-.56-1.25-1.25-1.25ZM10.25 7a2.75 2.75 0 1 1 5.5 0v18a2.75 2.75 0 1 1-5.5 0V7ZM13 5.75c-.69 0-1.25.56-1.25 1.25v18a1.25 1.25 0 1 0 2.5 0V7c0-.69-.56-1.25-1.25-1.25ZM20.683 4.25a2.63 2.63 0 0 0-2.47 3.528l6.632 18.241a2.63 2.63 0 0 0 4.943-1.797L23.155 5.98a2.63 2.63 0 0 0-2.472-1.731Zm-1.061 3.016a1.13 1.13 0 1 1 2.123-.772l6.633 18.24a1.13 1.13 0 1 1-2.123.772l-6.633-18.24Z"
					fill="currentColor"
				/></svg
			>
			<p>Library</p>
		</NavItem>
		<NavItem>
			<svg
				class="NavBar_IconDefaultColor__2SEUJ"
				height="32"
				viewBox="0 0 32 32"
				fill="none"
				xmlns="http://www.w3.org/2000/svg"
				aria-hidden="false"
				><title>Download</title><path
					d="m16 23.06-5.53-5.53 1.06-1.06 3.72 3.72V9h1.5v11.19l3.72-3.72 1.06 1.06L16 23.06Z"
					fill="currentColor"
				/><path
					d="M16 29c7.18 0 13-5.82 13-13S23.18 3 16 3 3 8.82 3 16s5.82 13 13 13Zm0-1.5C9.649 27.5 4.5 22.351 4.5 16S9.649 4.5 16 4.5 27.5 9.649 27.5 16 22.351 27.5 16 27.5Z"
					fill="currentColor"
				/></svg
			>
			<p>Download</p>
		</NavItem>
	</ul>
</nav>
