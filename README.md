# INF360-FSW-IA

## Tutorial para Correr IA Local:

1. Descargar Ollama desde la web oficial: https://ollama.com/download

![Texto alternativo](Images/Ollama.png)

2. Desde una terminal (PowerShell o CMD si tienes Windows) correr el modelo: ollama run deepseek-r1:1.5b

![Texto alternativo](Images/Terminal.png)

## Tutorial para Hostear IA:

1. Descargar ZeroTier desde la web oficial: https://www.zerotier.com/download/

![Texto alternativo](Images/ZeroTier.png)

2. Decirle al Alessandro que te Integre a la Red de ZeroTier con tu direccion

![Texto alternativo](Images/ZeroTier2.png)

3. Desde una terminal (PowerShell o CMD si tienes Windows) correr el modelo: ollama run deepseek-r1:1.5b

![Texto alternativo](Images/Terminal.png)

4. Crear una Regla en el Firewall que permita acceder al Puerto donde correra la IA (11434)

![Texto alternativo](Images/Regla1.png)
![Texto alternativo](Images/Regla2.png)

5. Desde una terminal diferente con la Ollama, ZeroTier y la IA corriendo ejecutar: 

 - PowerShell: set OLLAMA_HOST="0.0.0.0"; ollama serve