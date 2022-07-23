# Comandos executados com a turma 1 Avanade 50 sobre docker e orquestração de containers

```shell
docker pull didox/desafio_multiplasapis_ruby_tarefas:latest

export RAILS_ENV=production
export DATABASE=api-ruby
export USER=root
export PASSWORD=root
export HOST=192.168.0.17
docker run -d -e RAILS_ENV -e DATABASE -e USER -e PASSWORD -e HOST -p 80:3000 --name api-ruby didox/desafio_multiplasapis_ruby_tarefas


docker-compose up

```