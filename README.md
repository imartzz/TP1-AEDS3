# Ajuda Aí 1.0 — TP1 AEDS III

Sistema de perguntas e respostas inspirado no StackOverflow.  
Disciplina: Algoritmos e Estruturas de Dados III — PUC Minas.

## Grupo

| Nome                       | GitHub  |
|----------------------------|---------|
| Arthur De Pinho De Almeida | imartzz |
| Rafael Cardoso Machado     | icm3333 |
| (Membro 3)                 |         |
| (Membro 4)                 |         |

---

## Como compilar e executar

```bash
# Compilar
javac -encoding UTF-8 aed3/*.java entidades/*.java controle/*.java visao/*.java Principal.java

# Executar
java Principal
```

---

## Estrutura do projeto

```
TP1-AEDS3/
├── aed3/              → código base do professor (não modificar)
├── entidades/         → entidades e CRUDs
├── controle/          → lógica de negócio
├── visao/             → telas do terminal
└── Principal.java     → ponto de entrada
```

---

## O que está pronto

- Cadastro de novo usuário
- Login com email e senha
- Índice Hash Extensível por email (busca direta sem varredura)
- Estrutura de menus completa (login, menu principal, minha área)
- Criar nova pergunta vinculada ao usuário logado
- Listar perguntas do usuário via Árvore B+

---

## O que ainda precisa ser implementado

- Alterar nome, email, senha e pergunta de recuperação do usuário
- Recuperação de senha via pergunta secreta
- Alterar texto e palavras-chave de uma pergunta
- Arquivar pergunta (exclusão lógica definitiva)
- Exclusão em cascata das perguntas ao deletar um usuário

---

## Checklist do enunciado

- [ ] CRUD de usuários com Hash Extensível por email
- [ ] CRUD de perguntas com Árvore B+
- [ ] Perguntas vinculadas ao usuário via `idUsuario`
- [ ] Árvore B+ com par `(idUsuario, idPergunta)`
- [ ] Compila sem erros
- [ ] Funciona sem erros de execução
- [ ] Trabalho original
