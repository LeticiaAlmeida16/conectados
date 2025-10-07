# conectados
repositório destinado aos projetos dos conectados

## Letmeask

Este projeto é uma aplicação web de **Perguntas e Respostas em tempo real**, onde criadores de conteúdo podem organizar salas virtuais para interagir com sua audiência.

### Funcionalidades

**Autenticação**: Login de usuário via Google (Firebase Auth).

**Criação de Salas**: Usuários logados podem criar novas salas de Q&A.

**Entrada em Salas**: Participantes podem entrar em salas existentes usando um código.

**Envio de Perguntas**: Participantes podem enviar perguntas para o criador.

**Curtir Perguntas**: Os participantes podem curtir as perguntas, indicando relevância.

**Modo Administrador**: O criador da sala (administrador) pode:
    * Encerrar a sala.
    * Marcar perguntas como respondidas.
    * Dar destaque a perguntas.
    * Remover perguntas.

### Tecnologias

**ReactJS**

**TypeScript**

**Firebase Realtime Database** (para backend e banco de dados em tempo real)

**Firebase Authentication** (para autenticação via Google)

**SCSS** (para estilização)

### Como rodar o projeto

1.  Clone o repositório.
2.  Instale as dependências.
3.  Configure suas credenciais do Firebase no arquivo de serviços.
4.  Inicie a aplicação: 'yarn start.
