1. npm init -y
2. npm install tailwindcss @tailwindcss/cli
3. mkdir src
4. touch src/input.css
5. touch src/output.css
6. add in src/input.css "@import "tailwindcss";"
7. npx @tailwindcss/cli -i src/input.css -o src/output.css --watch
8. add output.css in html
