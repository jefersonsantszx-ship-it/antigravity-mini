# Atualizar o ambiente do Termux
pkg update
pkg install git python -y

# Baixar o projeto
git clone https://github.com/Santszx/code-agent.git

# Entrar na pasta
cd code-agent

# Rodar o Antigravity Mini
python antigravitymini.py
