1.  create --> npm create vite@latest
2.  Project name -->  calc-fe (any name You want)
3.  Select a framework --> React
4.  Select a variant -->  TypeScript + SWC
5.  cd calc-fe
6.  npm install -D tailwindcss postcss autoprefixer
7.  npx tailwindcss init -p
8.  npx shadcn@latest init
9.  npm i @types/node
10. npx shadcn@latest add button
11. npm i react-router-dom
12. npm install @mantine/core @mantine/hooks
13. npm install @vitejs/plugin-react
14. npm install vite-plugin-eslint --save-dev
15. touch postcss.config.cjs


npm run dev

16. touch constants.ts
17. npm i axios

npm run dev

backend
1. mkdir calc-be
2. cd calc-be
3. python -m venv venv 
4. source venv/Scripts/activate

venv/Scripts/python -m pip install pydantic

pip install fastapi Pillow uvicorn pydantic google.generativeai python-dotenv 

or 

/d/My_ML_Projs/Math-Notes/calc-be/venv/Scripts/python -m pip install Pillow pydantic google.generativeai python-dotenv

python3 main.py