## O Processo

1. Clonar o Repositório

2. Instalar Dependências
Instale todas as bibliotecas necessárias listadas no requirements.txt:

pip install -r requirements.txt

3. Configurar Variáveis de Ambiente (.env)
Crie um arquivo chamado .env na raiz do projeto e preencha com a sua chave de conexão do MongoDB Atlas.

-- Importante: A chave deve conter seu usuário e senha do banco de dados e estar entre aspas duplas.


## Como Rodar o Projeto

4. Iniciar o Servidor
Execute o seguinte comando no terminal. O flag --reload permite que o servidor reinicie automaticamente ao detectar mudanças no código.

comando: uvicorn app.main:app --reload

2. Acessar o Chat
Com o servidor rodando, acesse a interface do chat pelo navegador:

http://127.0.0.1:8000


