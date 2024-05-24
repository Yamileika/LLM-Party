# LLM-Party
Terminal ollama
    1. Instalar ollama
        curl -fsSL https://ollama.com/install.sh | sh

    2. Ejecutar el Servidor
        ollama server

Terminal bash
    3. Instalar un modelo
        ollama pull tinyllama

    4. Hacer una consulta
        Modo generativa: ollama run tinyllama ?

        Modo chat: ollama run tinyllama
        Salir de chat: Ctrl+d


        curl http://localhost:11434/api/generate -d '{
  "model": "llama3",
  "prompt": "Why is the sky blue?",
  "stream": false
}'

git add. 
git commit -m "UPDATE README"   Poner un titulo a los cambios que hicimos 