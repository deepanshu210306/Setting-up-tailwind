## How to set up Tailwind CSS

Step 1: Run the following command in termninal
```
npm install tailwindcss @tailwindcss/cli
```

Step 2: Make a input .css and paste the below code in it.
```
@import "tailwindcss";
```

Step 3: Make a tailwind.config.js and paste the below code in it.
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Step 4: Run this command in terminal.
```
npx @tailwindcss/cli -i input.css -o output.css --watch
```
Step 5: Link output.css to html.



You can use Tailwind.css now 

CAUTION: THIS PROCESS IS NOT STATIC THIS MIGHT CHANGE IN FUTURE.
```
REFER: https://tailwindcss.com/docs/installation/tailwind-cli
```
