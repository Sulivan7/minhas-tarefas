# 📝 Minhas Tarefas

Uma aplicação web para gerenciamento de tarefas pessoais, desenvolvida com React, TypeScript e Redux Toolkit.

## 🚀 Funcionalidades

- ✅ **Criar tarefas** com título, descrição e prioridade
- 📝 **Editar tarefas** existentes
- ✅ **Marcar como concluída** ou pendente
- 🗑️ **Remover tarefas**
- 🔍 **Buscar tarefas** por título
- 🏷️ **Filtrar por status** (pendente/concluída)
- 🎯 **Filtrar por prioridade** (urgente/importante/normal)
- 📱 **Interface responsiva**

## 🛠️ Tecnologias Utilizadas

- **React**
- **TypeScript**
- **Redux Toolkit**
- **React Router DOM**
- **Styled Components**
- **ESLint + Prettier**

## 📦 Estrutura do Projeto

```
src/
├── components/
│   ├── BotaoAdicionar/
│   ├── FiltroCard/
│   └── Tarefa/
├── containers/
│   ├── BarraLateral/
│   ├── Formulario/
│   └── ListaDeTarefas/
├── models/
│   └── Tarefa.ts
├── pages/
│   ├── Cadastro/
│   └── Home/
├── store/
│   ├── index.ts
│   └── reducers/
├── styles/
└── utils/
    └── enums/
```

## 🏃‍♂️ Como Executar

### Pré-requisitos

- Node.js
- npm ou yarn

### Instalação

1. **Clone o repositório**
   ```bash
   git clone [url-do-repositorio]
   cd minhas-tarefas
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Execute a aplicação**
   ```bash
   npm start
   ```

4. **Abra no navegador**
   ```
   http://localhost:3000
   ```

## 📋 Scripts Disponíveis

- `npm start` - Executa a aplicação em modo de desenvolvimento
- `npm test` - Executa os testes
- `npm run build` - Constrói a aplicação para produção
- `npm run eject` - Ejeta a configuração do Create React App
