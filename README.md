
# Vite + React Setup
This is simple setup template for Vite and ReactJS

## Create Project
To kickstart the project run

    npm create vite@latest
    
  **or Create within an already existing folder/dir** 

    npm create vite@latest .

   ## Install Dependencies

	# Router
    npm install react-router 

	# State management
    npm install @reduxjs/toolkit react-redux 

	# Form state management
	npm install formik
	
	# UI components
	npm install	 @mui/material @emotion/react @emotion/styled

	# Date and Time parsing
	npm install dayjs
	
	# Styling
	npm install sass
	
	# Node types for E.g. path module
	npm install --save-dev @types/node
 
 ## Vite Config
 

    import { defineConfig } from 'vite';
	import react from '@vitejs/plugin-react-swc';
	import path from 'path';

	export default defineConfig({
	  plugins: [react()],
	  resolve: {
	  alias: {
	      '@': path.resolve(__dirname, './src'), // Set "@" to reference the "src" folder
	    },
	  },
	});

	
## Startup Project

    npm run dev

