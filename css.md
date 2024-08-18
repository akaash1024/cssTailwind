CSS

tailwindcss
https://tailwindcss.com/docs/installation

> open folder and run in vsCode
npm install -D tailwindcss
npx tailwindcss init


> vscode left upper > tailwind.congig.js > content : ["./src/**/*.{html,js}"]	
		//bring from the site
> vscode left upper > folder "src" > in src input.css
		// copy from site and paste in input.css
		looks like,
		@tailwind base;
		@tailwind components;
		@tailwind utilities;

run in terminal
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch


src > folder testCSS > index.html > boiler plater
add before title : <link href="../output.css" rel="stylesheet">
in body

<h1 class="underline">Lorem ipsum dolor sit.</h1>






