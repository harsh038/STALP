React :

folder : frontend 

`npm create vite@latest ./`

npm install tailwindcss @tailwindcss/vite

npm install yup

In vite.config.ts file :

import tailwindcss from '@tailwindcss/vite'

tailwindcss(),

Index.css

`@import "tailwindcss";`

index.html

In head tag : <link href="/src/styles.css" rel="stylesheet"> 

---

main.jsx

```jsx
<BrowserRouter>
    <App />
  </BrowserRouter>
```
