<h1 align="center">ByteBank - Orquestrador</h1>

### ✨ Sobre

<h4>Orquestrador do microfrontend do Tech Challenge da Pós Tech FIAP - Fase 2</h4>

<b>Versão:</b> 1.0.0

### 📌 Stack de Desenvolvimento

- [single-spa](https://single-spa.js.org/) para orquestrar cada parte do microfrontend;

### 🛠 Ferramentas
- IDE: [VSCode](https://code.visualstudio.com/)

### 🎲 Workspace
- [bytebank-workspace](https://github.com/beatrizsantiago/bytebank-workspace);
<br />
<b><span style="font-size: 0.75rem">OBS: é importante rodar cada parte antes para que essa aplicação funcione corretamente.</span></b>

### 🎯 Getting Started

Com o docker instalado, contrua a imagem:

  ```
    docker build -t bytebank:orchestrator .
  ```

E depois execute o container:

  ```
    docker run -p 9000:9000 bytebank:orchestrator
  ```

Para utilizar o projeto sem o docker, siga os seguintes comandos:

Instalar as dependências

```bash
npm install
```

Iniciar projeto no modo dev:

```bash
npm start
```

Abra [http://localhost:9000](http://localhost:9000) com seu navegador.
