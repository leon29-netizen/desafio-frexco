Este é o projeto da primeira etapa do processo seletivo para vaga de Estágio em Tecnologia(DevOps).
A seguir estão instruções de cada aspecto dos escopos:

Instalação do Docker Desktop, versão mais recente(Docker compose incluído).
Instalação de uma WLS, nesse projeto foi utilizado Ubuntu, versão mais recente.

Visual code studio foi a ferramente utilizada e recomendada. Versão recente.

Todo o deploy foi seguido de acordo com as instruções utilizando-se Api em Django + PostgreSQL, foi feita a utilização de containers com as ferramentas Docker e Docker compose.

Caso necessário, fazer ativação do ambiente e instação do Django via CMD:
py -m venv venv
".\venv\Scripts\activate"
"pip install django"
------- Esses comandos são utilizados caso necessário, pois todos os arquivos estão presentes no documento.-------

"py .\manage.py runserver"
fazer checagem de funcionamento do servidor
docker-compose up (rodar o db e o servidor Django)
docker-compose down (parar o funcionamento de ambos)
docker-compose up -d  (garantir a possibilidade de digitar no terminal com o servidor rodando)