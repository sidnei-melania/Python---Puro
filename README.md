Primeiro devemos criar o ambiente virtual:

# Criar

# Linux
python3 -m venv venv

# Windows
python -m venv venv
Após a criação do venv vamos ativa-lo:

#Ativar

# Linux
source venv/bin/activate

# Windows
venv\Scripts\Activate

# Caso algum comando retorne um erro de permissão execute o código e tente novamente:
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

# Python Puro


