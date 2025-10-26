# Jogo da Velha React + Vite 🎮

Um jogo da velha (tic-tac-toe) moderno feito com **React** + **Vite**.
Permite jogar “X” e “O”, acompanhar o histórico de jogadas, reiniciar o jogo e conferir o vencedor. Estilizado com tema escuro e efeitos interativos.

## Estrutura do Projeto

```
jogo-da-velha-vite/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── App.jsx
    ├── Game.jsx
    ├── App.css
    └── main.jsx
```

## Como Rodar Localmente

1. Clone ou baixe o repositório.
2. Navegue até a pasta do projeto:
   ```bash
   cd jogo-da-velha-vite
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```
5. Abra o navegador no endereço exibido (geralmente http://localhost:5173).

## Scripts Disponíveis

| Script | Comando | Descrição |
|--------|---------|-----------|
| dev    | vite    | Inicia o servidor de desenvolvimento |
| build  | vite build | Gera a versão de produção / build |
| preview | vite preview | Testa a versão de produção localmente |

## Funcionalidades

- Jogar “X” e “O” alternadamente
- Impedir jogadas inválidas (célula já ocupada ou jogo finalizado)
- Mostrar vencedor automaticamente
- Histórico de jogadas: voltar a movimentos anteriores
- Reinício do jogo a qualquer momento
- Estilo moderno com tema escuro e efeitos de hover nos quadrados e botões

## Possíveis Melhorias Futuras

- Mostrar linha de vitória sobre as três células vencedoras
- Placar de vitórias acumuladas (X vs O)
- Animações ao marcar quadrados
- Tema claro / modo escuro alternável
- Interface responsiva para dispositivos móveis
- Feedback visual extra, como destaque no quadrado vencedor

## Licença

Este projeto é livre para uso e modificação.

## Autor

**Poliana Vitoria** - Projeto educativo para prática de React e Vite.
