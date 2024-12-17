Step 1: open project directory

Step 2: Install Tailwind CSS (without adding it to product dependencies)
npm install -D tailwindcss --no-save;

Step 3: Run Tailwind CSS to Automatically Generate the CSS File
npx tailwindcss -i ./styles/input.css -o ./styles.css --watch
