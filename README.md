# Gerenciador de Tarefas - Projeto Final +PraTI

---

## Início Rápido

### Clonar o Repositório

#### Usando HTTPS (com token pessoal do GitHub)
```
git clone https://github.com/vsoares99/gerenciador-tarefas.git
```

#### Usando SSH (recomendado)
```
git clone git@github.com:vsoares99/gerenciador-tarefas.git
```
#### Configurar o Git localmente
```
git config user.name "Seu Nome"
git config user.email "seuemail@exemplo.com"
```

#### Fluxo de Trabalho com Git
Branches principais
```main:``` versão de produção
```develop:``` branch de desenvolvimento
```feature/nome-da-feature:``` para desenvolvimento de funcionalidades específicas

#### Criar uma nova funcionalidade
Certifique-se de estar atualizado com a develop:
```
git checkout develop
git pull origin develop
```
Crie uma nova branch para sua funcionalidade:
```
git checkout -b feature/nome-da-feature
```
Exemplo: feature/cadastro-de-usuarios

#### Commits
```
git add .
git commit -m "[Front|Back|DB] Breve descrição da alteração"
git push origin feature/nome-da-feature
```

#### Abrir um Pull Request (PR)

Acesse o repositório no GitHub
Selecione sua branch
Clique em “Compare & Pull Request”
Envie para a branch develop
Descreva o que foi feito, qual Sprint e a tarefa

#### Organização do Projeto
O projeto é dividido por Sprints, e você pode acompanhar o progresso no board abaixo:

[Acessar o Board de Sprints](https://trello.com/b/ysGZCmQy/gerenciador-de-tarefas)


