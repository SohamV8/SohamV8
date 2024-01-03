
<style>
  @keyframes lights {
	0% {
		opacity: 0;
	}
	30% {
		opacity: 0;
	}
	40% {
		opacity: 1;
	}
	90% {
		opacity: 1;
	}
	100% {
		opacity: 0;
	}
}

.lit {
	animation: 2s linear infinite lights;

	&.yellow {
		animation-delay: 0.5s;
	}

	&.blue {
		animation-delay: 1s;
	}

	&.red {
		animation-delay: 1.5s;
	}
}

.lights {
	align-items: top;
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(0, 1fr));
	position: absolute;
	inset-inline: 0;

	&.top {
		top: 0;
	}

	&.bottom {
		bottom: 0;
		rotate: 180deg;
	}

	& svg {
		display: block;
		width: 100%;
	}

	& svg:nth-child(2) ~ svg {
		display: none;

		@media (min-width: 400px) {
			display: block;
		}
	}

	& svg:nth-child(3) ~ svg {
		display: none;

		@media (min-width: 500px) {
			display: block;
		}
	}

	& svg:nth-child(4) ~ svg {
		display: none;

		@media (min-width: 600px) {
			display: block;
		}
	}
}

#lights-def {
	display: block;
	width: 0;
	height: 0;
	overflow: hidden;
}

/* other styles to make this look a bit nicer */




main {
	display: grid;
	margin-block: 2rem;
	min-height: calc(100dvh - 4rem);
	padding: 4rem 2rem;
	place-content: center;
	position: relative;
}

.content {
	margin-inline: auto;
	max-width: 40ch;
	text-align: center;
}

:root {

  line-height: 1.5;
  background-color: whitesmoke;

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}


.bouncing-blob {
  width: 32vw;
  aspect-ratio: 1;
  border-radius: 50%;
  will-change: transform;
  position: absolute;
  z-index: 1;
  top: 0;
  left: 0;
  transform-origin: left top;
}

.bouncing-blob--blue {
  background: #4783c7;
}

.bouncing-blob--white {
  background: #ffffff;
  z-index: 2;
  width: 15vw;
}

.bouncing-blob--purple {
  background: #8c8ff1;
}

.bouncing-blob--pink {
  background: #e289cd50;
}

.bouncing-blobs-container {
  position: fixed;
  z-index: -1;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.bouncing-blobs-glass {
  position: absolute;
  z-index: 2;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  backdrop-filter: blur(140px);
  -webkit-backdrop-filter: blur(140px);
  pointer-events: none;
}

.bouncing-blobs {
  position: absolute;
  z-index: 1;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

@media (max-width: 1200px) {
  .bouncing-blobs-glass {
    backdrop-filter: blur(120px);
    -webkit-backdrop-filter: blur(120px);
  }
}

@media (max-width: 500px) {
  .bouncing-blob {
    width: 60vw;
  }
  .bouncing-blob--white {
    width: 30vw;
  }
  .bouncing-blobs-glass {
    backdrop-filter: blur(90px);
    -webkit-backdrop-filter: blur(90px);
  }

  
  
</style>
<main>
	<div class="lights top">
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
	</div>
	<div class="lights bottom">
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
		<svg viewBox="0 0 161 54">
			<use xlink:href="#holiday-lights" />
		</svg>
	</div>

<h1 align="center">Hi 👋, I'm Soham Vashist</h1>
<h3 align="center">A passionate frontend developer from India</h3>
<img align="right" alt="coding" width="300px" style ="border-radius:8px;" src="https://camo.githubusercontent.com/c1dcb74cc1c1835b1d716f5051499a2814c683c806b15f04b0eba492863703e9/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f3733303730332f73637265656e73686f74732f363538313234332f6176656e746f2e676966">

<p align="left"> <a href="https://twitter.com/sohamv8_code" target="blank"><img src="https://img.shields.io/twitter/follow/sohamv8_code?logo=twitter&style=for-the-badge" alt="sohamv8_code" /></a> </p>

- 🔭 I’m currently working on **Professional 3D-Animated website and A.I based Astrology App**

- 🌱 I’m currently learning **React, Backend Development, App Development.**

- 👨‍💻 All of my projects are available at [sohamv8.github.io](sohamv8.github.io)

- 💬 Ask me about **Graphic design, Frontend development, SEO, etc.**

- 📫 How to reach me **sohamvashists8@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://codepen.io/https://codepen.io/sohamv8" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codepen.svg" alt="https://codepen.io/sohamv8" height="30" width="40" /></a>
<a href="https://twitter.com/sohamv8_code" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="sohamv8_code" height="30" width="40" /></a>
<a href="https://linkedin.com/in/https://www.linkedin.com/in/soham-vashist-34a3b8259/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/soham-vashist-34a3b8259/" height="30" width="40" /></a>
<a href="https://dribbble.com/https://dribbble.com/sohamv8" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/dribbble.svg" alt="https://dribbble.com/sohamv8" height="30" width="40" /></a>
<a href="https://www.behance.net/https://www.behance.net/sohamvashist" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/behance.svg" alt="https://www.behance.net/sohamvashist" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://www.framer.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/framer/framer-icon.svg" alt="framer" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> </p>
</main>

<svg id="lights-def" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="none" viewBox="0 0 161 54">
	<defs>
		<path id="glow-red" fill="color(display-p3 .9216 .3412 .3412)" d="m137.32 16.43 2.03-1.58a4 4 0 0 1 2.95-.82l1.68.2a4 4 0 0 1 2.66 1.51l1.59 2.04a10 10 0 0 1 1.03 10.7l-5.4 10.59a4 4 0 0 1-7.47-.92l-2.66-11.6a10 10 0 0 1 3.59-10.12Z" />
		<path id="glow-blue" fill="color(display-p3 .1765 .6118 .8588)" d="m93.23 18.08 1.5-2.1a4 4 0 0 1 2.6-1.61l1.67-.28a4 4 0 0 1 2.98.7l2.1 1.5a10 10 0 0 1 3.99 9.98l-2.2 11.69a4 4 0 0 1-7.42 1.22L92.63 28.8a10 10 0 0 1 .6-10.72Z" />
		<path id="glow-yellow" fill="color(display-p3 .949 .7882 .298)" d="m56.6 16.63 1.96-1.69a4 4 0 0 1 2.91-.95l1.68.12a4 4 0 0 1 2.74 1.38l1.68 1.96a10 10 0 0 1 1.53 10.63l-4.89 10.84a4 4 0 0 1-7.5-.56L53.5 26.91a10 10 0 0 1 3.1-10.28Z" />
		<path id="glow-green" fill="color(display-p3 .1529 .6824 .3765)" d="m13.12 18.14 1.49-2.1a4 4 0 0 1 2.58-1.64l1.67-.29a4 4 0 0 1 2.98.68l2.11 1.48a10 10 0 0 1 4.08 9.94l-2.1 11.7a4 4 0 0 1-7.42 1.29l-5.9-10.33a10 10 0 0 1 .5-10.73Z" />
		<path id="lit-red" fill="#fff" d="m137.32 16.43 2.03-1.58a4 4 0 0 1 2.95-.82l1.68.2a4 4 0 0 1 2.66 1.51l1.59 2.04a10 10 0 0 1 1.03 10.7l-5.4 10.59a4 4 0 0 1-7.47-.92l-2.66-11.6a10 10 0 0 1 3.59-10.12Z" />
		<path id="lit-blue" fill="#fff" d="m93.23 18.08 1.5-2.1a4 4 0 0 1 2.6-1.61l1.67-.28a4 4 0 0 1 2.98.7l2.1 1.5a10 10 0 0 1 3.99 9.98l-2.2 11.69a4 4 0 0 1-7.42 1.22L92.63 28.8a10 10 0 0 1 .6-10.72Z" />
		<path id="lit-yellow" fill="#fff" d="m56.6 16.63 1.96-1.69a4 4 0 0 1 2.91-.95l1.68.12a4 4 0 0 1 2.74 1.38l1.68 1.96a10 10 0 0 1 1.53 10.63l-4.89 10.84a4 4 0 0 1-7.5-.56L53.5 26.91a10 10 0 0 1 3.1-10.28Z" />
		<path id="lit-green" fill="#fff" d="m13.12 18.14 1.49-2.1a4 4 0 0 1 2.58-1.64l1.67-.29a4 4 0 0 1 2.98.68l2.11 1.48a10 10 0 0 1 4.08 9.94l-2.1 11.7a4 4 0 0 1-7.42 1.29l-5.9-10.33a10 10 0 0 1 .5-10.73Z" />
		<g id="holiday-lights" clip-path="url(#a)">
			<path id="cord" fill="color(display-p3 .0471 .1961 .1137)" d="M0 4h6.31a6 6 0 0 1 3.13.88l6.6 4.04c.6.36 1.34.4 1.96.08l6.13-3.68a6 6 0 0 1 2.97-.85l21.7-.45a6 6 0 0 1 2.31.42l9.77 3.82a5.3 5.3 0 0 0 3.88 0l7.09-2.8a6 6 0 0 1 2.39-.42l13.33.42a6 6 0 0 1 2.69.73l3.82 2.08a6 6 0 0 0 3.3.72l.56-.04a6 6 0 0 0 1.22-.21l10.61-3.03a6 6 0 0 1 1.49-.23l21.77-.6a6 6 0 0 1 2.8.61l6.84 3.35a3.47 3.47 0 0 0 3.66-.39l4.04-3.17a6 6 0 0 1 3.7-1.28H161v2h-6.3a6 6 0 0 0-3.88 1.42l-2.81 2.38a6 6 0 0 1-4.62 1.37l-.32-.04a6 6 0 0 1-2.02-.62l-5.67-2.95a6 6 0 0 0-2.93-.67l-20.7.59c-.5.01-1 .09-1.48.23l-10.55 3.03a6 6 0 0 1-1.21.21l-.7.06a6 6 0 0 1-2.98-.55l-5.22-2.44a6 6 0 0 0-2.34-.56l-12.53-.42a6 6 0 0 0-2.4.42l-7.04 2.78a6 6 0 0 1-2.7.4l-.73-.07a6 6 0 0 1-1.69-.39l-9.56-3.74a6 6 0 0 0-2.32-.41l-20.7.44a6 6 0 0 0-2.97.85l-5.67 3.4a3.63 3.63 0 0 1-3.76-.02L8.94 6.89A6 6 0 0 0 5.81 6H0V4Z" />
			<g class="bulb-glow red" filter="url(#b)" style="mix-blend-mode:plus-lighter">
				<use xlink:href="#glow-red" />
			</g>
			<g id="plug-red">
				<path fill="color(display-p3 .0486 .196 .1119)" d="M140 10.89c.02-.11.06-.22.16-.27.25-.12 1.03-.26 3.4.04 2.38.29 3.1.61 3.32.8.09.06.1.18.1.29l-.05 4.36s-.57-1.58-3.8-1.98c-3.22-.4-4.14 1-4.14 1l1-4.24Z" />
				<g filter="url(#d)" style="mix-blend-mode:color-dodge">
					<path fill="color(display-p3 .0578 .3504 .1908)" d="m139.85 14.23.9-3.16 3.47.42-2.6.69-1.77 2.05Z" />
				</g>
			</g>
			<g id="bulb-red">
				<path fill="color(display-p3 .9216 .3412 .3412)" stroke="color(display-p3 .8784 .8784 .8784)" stroke-width=".25" d="m137.32 16.43 2.03-1.58a4 4 0 0 1 2.95-.82l1.68.2a4 4 0 0 1 2.66 1.51l1.59 2.04a10 10 0 0 1 1.03 10.7l-5.4 10.59a4 4 0 0 1-7.47-.92l-2.66-11.6a10 10 0 0 1 3.59-10.12Z" />
				<g filter="url(#e)" style="mix-blend-mode:overlay">
					<path fill="#fff" d="M135.92 19.54c1.98-2.78 3.37-2.78 4.4-2.98l-1.37 1.46a10 10 0 0 0-2.7 6.43l-.16 3.93c-.49-2.16-2.15-6.06-.17-8.84Z" />
				</g>
				<g filter="url(#f)" opacity=".6" style="mix-blend-mode:plus-lighter">
					<path fill="#fff" d="m140.59 26.66 2.59-8.75 3.35 3.44.5 4.1-6.2 11.57-.24-10.36Z" />
				</g>
			</g>
			<g class="bulb-glow blue" filter="url(#g)" style="mix-blend-mode:plus-lighter">
				<use xlink:href="#glow-blue" />
			</g>
			<g id="plug-blue">
				<path fill="color(display-p3 .0486 .196 .1119)" d="M94.24 12c-.01-.1 0-.22.08-.3.2-.18.92-.54 3.28-.92 2.36-.4 3.15-.28 3.4-.17.1.04.15.15.18.25l1.18 4.2s-.99-1.36-4.2-.83c-3.2.53-3.7 2.13-3.7 2.13L94.24 12Z" />
				<g filter="url(#i)" style="mix-blend-mode:color-dodge">
					<path fill="color(display-p3 .0578 .3504 .1908)" d="m95.04 15.25-.03-3.29 3.45-.56-2.3 1.39-1.12 2.46Z" />
				</g>
			</g>
			<g id="bulb-blue">
				<path fill="color(display-p3 .1765 .6118 .8588)" stroke="color(display-p3 .8784 .8784 .8784)" stroke-width=".25" d="m93.23 18.08 1.5-2.1a4 4 0 0 1 2.6-1.61l1.67-.28a4 4 0 0 1 2.98.7l2.1 1.5a10 10 0 0 1 3.99 9.98l-2.2 11.69a4 4 0 0 1-7.42 1.22L92.63 28.8a10 10 0 0 1 .6-10.72Z" />
				<g filter="url(#j)" style="mix-blend-mode:overlay">
					<path fill="#fff" d="M92.76 21.45c1.12-3.22 2.45-3.61 3.39-4.1l-.9 1.79a10 10 0 0 0-.79 6.93l.95 3.81c-1.07-1.93-3.76-5.2-2.65-8.43Z" />
				</g>
				<g filter="url(#k)" opacity=".6" style="mix-blend-mode:plus-lighter">
					<path fill="#fff" d="m99.24 26.97.03-9.12 4.18 2.35 1.65 3.8-2.7 12.86-3.15-9.88Z" />
				</g>
			</g>
			<g class="bulb-glow yellow" filter="url(#l)" style="mix-blend-mode:plus-lighter">
				<use xlink:href="#glow-yellow" />
			</g>
			<g id="plug-yellow">
				<path fill="color(display-p3 .0486 .196 .1119)" d="M59.02 10.96c.02-.11.05-.22.15-.27.25-.13 1.02-.31 3.4-.13 2.4.18 3.13.47 3.36.63.09.07.1.19.1.3l.16 4.36s-.64-1.56-3.88-1.8c-3.24-.24-4.1 1.2-4.1 1.2l.8-4.3Z" />
				<g filter="url(#n)" style="mix-blend-mode:color-dodge">
					<path fill="color(display-p3 .0578 .3504 .1908)" d="m59.03 14.3.75-3.2 3.49.26-2.57.81-1.67 2.13Z" />
				</g>
			</g>
			<g id="bulb-yellow">
				<path fill="color(display-p3 .949 .7882 .298)" stroke="color(display-p3 .8784 .8784 .8784)" stroke-width=".25" d="m56.6 16.63 1.96-1.69a4 4 0 0 1 2.91-.95l1.68.12a4 4 0 0 1 2.74 1.38l1.68 1.96a10 10 0 0 1 1.53 10.63l-4.89 10.84a4 4 0 0 1-7.5-.56L53.5 26.91a10 10 0 0 1 3.1-10.28Z" />
				<g filter="url(#o)" style="mix-blend-mode:overlay">
					<path fill="#fff" d="M55.36 19.8c1.85-2.88 3.23-2.94 4.25-3.2l-1.3 1.53a10 10 0 0 0-2.38 6.55l.02 3.93c-.59-2.13-2.43-5.95-.59-8.82Z" />
				</g>
				<g filter="url(#p)" opacity=".6" style="mix-blend-mode:plus-lighter">
					<path fill="#fff" d="m60.36 26.69 2.17-8.86 3.51 3.27.7 4.06-5.65 11.86-.73-10.33Z" />
				</g>
			</g>
			<g class="bulb-glow green" filter="url(#q)" style="mix-blend-mode:plus-lighter">
				<use xlink:href="#glow-green" />
			</g>
			<g id="plug-green">
				<path fill="color(display-p3 .0486 .196 .1119)" d="M14.08 12.06c-.01-.11 0-.23.07-.3.21-.19.92-.55 3.28-.95 2.36-.41 3.14-.3 3.4-.2.1.04.15.15.18.25l1.21 4.2s-1-1.36-4.2-.8c-3.2.55-3.68 2.15-3.68 2.15l-.26-4.35Z" />
				<g filter="url(#s)" style="mix-blend-mode:color-dodge">
					<path fill="color(display-p3 .0578 .3504 .1908)" d="m14.9 15.3-.05-3.29 3.45-.6-2.3 1.42-1.1 2.47Z" />
				</g>
			</g>
			<g id="bulb-green">
				<path fill="color(display-p3 .1529 .6824 .3765)" stroke="color(display-p3 .8784 .8784 .8784)" stroke-width=".25" d="m13.12 18.14 1.49-2.1a4 4 0 0 1 2.58-1.64l1.67-.29a4 4 0 0 1 2.98.68l2.11 1.48a10 10 0 0 1 4.08 9.94l-2.1 11.7a4 4 0 0 1-7.42 1.29l-5.9-10.33a10 10 0 0 1 .5-10.73Z" />
				<g filter="url(#t)" style="mix-blend-mode:overlay">
					<path fill="#fff" d="M12.68 21.52c1.1-3.23 2.42-3.63 3.35-4.13l-.9 1.8a10 10 0 0 0-.71 6.93l.98 3.8c-1.1-1.92-3.8-5.17-2.72-8.4Z" />
				</g>
				<g filter="url(#u)" opacity=".6" style="mix-blend-mode:plus-lighter">
					<path fill="#fff" d="m19.2 26.99-.04-9.12 4.2 2.31 1.67 3.78-2.6 12.87L19.2 27Z" />
				</g>
			</g>
			<g class="lit red" style="mix-blend-mode:overlay">
				<g filter="url(#v)">
					<use xlink:href="#glow-red" />
				</g>
				<g filter="url(#w)">
					<use xlink:href="#lit-red" />
				</g>
				<g filter="url(#y)">
					<use xlink:href="#lit-red" />
				</g>
			</g>
			<g class="lit blue" style="mix-blend-mode:overlay">
				<g filter="url(#z)">
					<use xlink:href="#glow-blue" />
				</g>
				<g filter="url(#A)">
					<use xlink:href="#lit-blue" />
				</g>
				<g filter="url(#C)">
					<use xlink:href="#lit-blue" />
				</g>
			</g>
			<g class="lit yellow" style="mix-blend-mode:overlay">
				<g filter="url(#D)">
					<use xlink:href="#glow-yellow" />
				</g>
				<g filter="url(#E)">
					<use xlink:href="#lit-yellow" />
				</g>
				<g filter="url(#G)">
					<use xlink:href="#lit-yellow" />
				</g>
			</g>
			<g class="lit green" style="mix-blend-mode:overlay">
				<g filter="url(#H)">
					<use xlink:href="#glow-green" />
				</g>
				<g filter="url(#I)">
					<use xlink:href="#lit-green" />
				</g>
				<g filter="url(#K)">
					<use xlink:href="#lit-green" />
				</g>
			</g>
		</g>
		<filter id="b" width="40.88" height="51.25" x="121.47" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="6" />
		</filter>
		<filter id="d" width="6.37" height="5.16" x="138.85" y="10.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation=".5" />
		</filter>
		<filter id="e" width="8.34" height="14.82" x="133.48" y="15.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation=".75" />
		</filter>
		<filter id="f" width="14.45" height="27.11" x="136.59" y="13.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="2" />
		</filter>
		<filter id="g" width="40.89" height="51.18" x="79.35" y="2.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="6" />
		</filter>
		<filter id="i" width="5.45" height="5.85" x="94.01" y="10.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation=".5" />
		</filter>
		<filter id="j" width="6.65" height="15.53" x="91" y="15.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation=".75" />
		</filter>
		<filter id="k" width="13.84" height="27" x="95.24" y="13.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="2" />
		</filter>
		<filter id="l" width="40.86" height="51.3" x="41.13" y="1.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="6" />
		</filter>
		<filter id="n" width="6.23" height="5.2" x="58.03" y="10.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation=".5" />
		</filter>
		<filter id="o" width="8.05" height="15.01" x="53.06" y="15.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation=".75" />
		</filter>
		<filter id="p" width="14.38" height="27.2" x="56.36" y="13.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="2" />
		</filter>
		<filter id="q" width="40.9" height="51.16" x="-.71" y="2.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="6" />
		</filter>
		<filter id="s" width="5.45" height="5.88" x="13.85" y="10.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation=".5" />
		</filter>
		<filter id="t" width="6.6" height="15.54" x="10.93" y="15.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation=".75" />
		</filter>
		<filter id="u" width="13.87" height="26.97" x="15.15" y="13.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="2" />
		</filter>
		<filter id="v" width="40.88" height="51.25" x="121.47" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="6" />
		</filter>
		<filter id="w" width="30.88" height="41.25" x="126.47" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="3.5" />
		</filter>
		<filter id="y" width="20.88" height="31.25" x="131.47" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="1" />
		</filter>
		<filter id="z" width="40.89" height="51.18" x="79.35" y="2.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="6" />
		</filter>
		<filter id="A" width="30.89" height="41.18" x="84.35" y="7.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="3.5" />
		</filter>
		<filter id="C" width="20.89" height="31.18" x="89.35" y="12.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="1" />
		</filter>
		<filter id="D" width="40.86" height="51.3" x="41.13" y="1.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="6" />
		</filter>
		<filter id="E" width="30.86" height="41.3" x="46.13" y="6.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="3.5" />
		</filter>
		<filter id="G" width="20.86" height="31.3" x="51.13" y="11.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="1" />
		</filter>
		<filter id="H" width="40.9" height="51.16" x="-.71" y="2.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="6" />
		</filter>
		<filter id="I" width="30.9" height="41.16" x="4.29" y="7.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="3.5" />
		</filter>
		<filter id="K" width="20.9" height="31.16" x="9.29" y="12.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse">
			<feFlood flood-opacity="0" result="BackgroundImageFix" />
			<feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
			<feGaussianBlur result="effect1_foregroundBlur_1_2" stdDeviation="1" />
		</filter>
		<clipPath id="a">
			<path fill="#fff" d="M0 0h161v54H0z" />
		</clipPath>
	</defs>
</svg>

<script>
  const MIN_SPEED = 1.5
const MAX_SPEED = 2.5

function randomNumber(min, max) {
  return Math.random() * (max - min) + min
}

class Blob {
  constructor(el) {
    this.el = el
    const boundingRect = this.el.getBoundingClientRect()
    this.size = boundingRect.width
    this.initialX = randomNumber(0, window.innerWidth - this.size)
    this.initialY = randomNumber(0, window.innerHeight - this.size)
    this.el.style.top = `${this.initialY}px`
    this.el.style.left = `${this.initialX}px`
    this.vx =
      randomNumber(MIN_SPEED, MAX_SPEED) * (Math.random() > 0.5 ? 1 : -1)
    this.vy =
      randomNumber(MIN_SPEED, MAX_SPEED) * (Math.random() > 0.5 ? 1 : -1)
    this.x = this.initialX
    this.y = this.initialY
  }

  update() {
    this.x += this.vx
    this.y += this.vy
    if (this.x >= window.innerWidth - this.size) {
      this.x = window.innerWidth - this.size
      this.vx *= -1
    }
    if (this.y >= window.innerHeight - this.size) {
      this.y = window.innerHeight - this.size
      this.vy *= -1
    }
    if (this.x <= 0) {
      this.x = 0
      this.vx *= -1
    }
    if (this.y <= 0) {
      this.y = 0
      this.vy *= -1
    }
  }

  move() {
    this.el.style.transform = `translate(${this.x - this.initialX}px, ${
      this.y - this.initialY
    }px)`
  }
}

function initBlobs() {
  const blobEls = document.querySelectorAll('.bouncing-blob')
  const blobs = Array.from(blobEls).map((blobEl) => new Blob(blobEl))

  function update() {
    requestAnimationFrame(update)
    blobs.forEach((blob) => {
      blob.update()
      blob.move()
    })
  }

  requestAnimationFrame(update)
}

initBlobs()
  </script>
