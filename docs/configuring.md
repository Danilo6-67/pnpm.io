# mit npm
npm create vite@latest lernapp -- --template react
cd lernapp
npm install






import React from 'react'
import ReactDOM from 'react-dom/client'
import LernApp from './LernApp'
import './index.css'   // falls Tailwind nicht genutzt wird, kannst du eigene CSS laden

ReactDOM.createRoot(document.getElementById('root')).render(<LernApp />)






npm run dev
