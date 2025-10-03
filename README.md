# Shadcn setup for vite+ react +javascript

This is the setup video ...[shadcn-setup-js](https://youtu.be/aMX_DYK5LAk?si=Vop3Y07mgYDsA2Rf)

# Steps
### 1. install tailwind :  npm install tailwindcss @tailwindcss/vite   </br>

### 2. in index.css :  @import "tailwindcss";  </br>

### 3. create jsconfig.json file in root and use this =>
from shadcn docs copy the config.json file and clear the references :

{ </br>
  &nbsp;  "files": [ ], </br>
  &nbsp;  "references": [ ], </br>
  &nbsp;  "compilerOptions": {</br>
 &nbsp;   &nbsp;  &nbsp; "baseUrl": ".",</br>
  &nbsp;   &nbsp;  &nbsp; "paths": {</br>
  &nbsp;   &nbsp;  &nbsp;  &nbsp;  "@/*": ["./src/*"]</br>
  &nbsp;  &nbsp;    }</br>
  &nbsp;  }</br>
}</br>

### 4. According to the shadcn docs skip the next file setup (tsconfig.app.json)

### 5. Run this command : npm install -D @types/node

### 6. Update vite.config.js according to shadcn

### 7. Run this cli : npx shadcn@latest init

### 8. Setup is done. Now whatever component you want to use just install it. As example to install button use this command :
npx shadcn@latest add button
this will add the button.jsx in components/ui folder
