# React_Prueba_Junior

-- Inicializado proyecto mediante npm create vite@latest -- seleccionando vanilla para simular prueba tecnica

-- $ npm install @vitejs/plugin-react -E

-- $ npm install react react-dom -E


## Crear archivo vite.config.js

import { defineConfig } from "vite";
import React from '@vitejs/plugin-react'

export default defineConfig(
    {
        plugins:[react()]
    }
)