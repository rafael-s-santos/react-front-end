# Disciplina Front-End II - IFES
## Atividade (Semana 16 - 2 a 8 de junho)
## Criando Funcionalidade com Props (5 pontos)

Este projeto React implementa uma funcionalidade simples que exibe informações utilizando **props**, conforme solicitado na atividade da disciplina.

## ✨ Funcionalidade

O componente `Mensagem` recebe um nome via props e exibe uma saudação personalizada na tela.

### Exemplo de uso:
```
<Mensagem nome="Rafael" />
```
Renderiza:
```
Olá, Rafael!
```
## 📁 Estrutura do Projeto
```
src/
├── App.jsx
├── Mensagem.jsx
├── index.js
├── index.css
public/
└── index.html
```

- App.jsx: Componente principal que renderiza a mensagem.
- Mensagem.jsx: Componente que recebe a prop nome e exibe a saudação.

▶️ Como rodar o projeto
Instale as dependências:
```
npm install
```
Inicie a aplicação:

```
npm start
```

Acesse http://localhost:3000 no navegador.
