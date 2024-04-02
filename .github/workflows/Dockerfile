# Use a imagem base do Python, por exemplo
FROM python:3.9

# Instale as dependências necessárias
RUN pip install boto3 awscli

# Copie os scripts ou arquivos necessários para dentro do contêiner
COPY seu_script.py /app/seu_script.py

# Defina o comando padrão a ser executado quando o contêiner for iniciado
CMD ["python", "/app/seu_script.py"]
