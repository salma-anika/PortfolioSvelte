
<script>
 import "../app.css";

	import { onMount } from 'svelte';

	onMount(() => {
		let text = document.getElementById('text');
		let btn = document.getElementById('btn');
		let header = document.getElementById('header');
		let section = document.getElementById('section');

		window.addEventListener('scroll', function () {
			let value = window.scrollY;
			// @ts-ignore
			text.style.bottom = 50 + value * -0.5 + '%';
			// @ts-ignore
			btn.style.bottom = value * 1.5 + 'px';
			// @ts-ignore
			header.style.bottom = value * +0.5 + 'px';
			// @ts-ignore
			section.style.bottom = value * -5 + 'px';
		});
	});
</script>

<header id="header">
  <a href="" class="logo">Ava</a>
  <ul class="menu">
    <li class="menulist "><a href="/" class="">Home</a></li>
    <li class="menulist"><a href="about" class="">About</a></li>
    <li class="menulist"><a href="project" class="">Project</a></li>
    <li class="menulist"><a href="skill" class="">Skill</a></li>
    <li class="menulist"><a href="copy" class="">copy</a></li>
    <li class="menulist"><a href="contact" class="">Contact</a></li>
    <li class="menulist"><a href="signup" class="">Signup</a></li>
  </ul>
</header>




<slot></slot>