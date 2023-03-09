src = source (ou codigo fonte) 
fora da src - arquivos de config


server que sustenta uma aplicacao

Conceito de arquitetura N-layers

camadas:
- Controllers: controlar quem acessa e controlar as respostas de devolução (request e responses)

- Rotas: quem vai o apontamento de endereços para os nossos controllers

- Model: é a forma e entrada/saida de dados no seu servidor

- Config: server para colocar configurações de outras aplicações (aplicações de terceiros) e dados nao sensiveis

- Configurações não embarcadas (.env):
server para isolar dados sensiveis