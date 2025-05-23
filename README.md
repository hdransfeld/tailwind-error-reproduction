This is a reproduction of a bug I'm seeing in my project.

https://github.com/tailwindlabs/tailwindcss/issues/18119

Use `npm run dev` to start the project.
You should see the error in the console.

```
[vite] Internal server error: [postcss] /Users/username/.../tailwind-error-reproducer/src/App.css:1:1: `@layer base` is used but no matching `@tailwind base` directive is present.
  Plugin: vite:css
  File: /Users/username/.../tailwind-error-reproducer/src/App.css:1:0
  1  |  @layer base {
     |  ^
  2  |    h1 {
  3  |      color: red;

```
