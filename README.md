HOW TO INSTALL TAILWIND CSS 4.1
1. npm init -y
2. npm install tailwindcss @tailwindcss/cli
3. mkdir src
4. touch src/input.css
5. touch src/output.css
6. add in src/input.css "@import "tailwindcss";"
7. npx @tailwindcss/cli -i src/input.css -o src/output.css --watch
8. add output.css in html

HOW TO NOT ADD node_modules
1. echo node_modules/ > .gitignore

CDN NO AUTO COMPLETE??
1. add script cdn
2. add file tailwind.config.js