# embute-study-app-2024-2-main
 
# Study App

O repositório do **Study App**, uma aplicação para gerenciamento de cartões de estudo e tarefas. Desenvolvido com **React Native** e **Expo**, o aplicativo utiliza **Firebase** para autenticação e armazenamento de dados.

## Estrutura do Projeto

### Diretórios e Arquivos

#### **`assets/`**
Contém recursos visuais do aplicativo, como ícones e imagens:
- **`adaptive-icon.png`**: Ícone adaptativo para diferentes dispositivos.
- **`favicon.png`**: Ícone para uso em navegadores.
- **`icon.png`**: Ícone principal da aplicação.
- **`logo.png`**: Logotipo do aplicativo.
- **`splash.png`**: Tela de carregamento exibida ao iniciar o app.

#### **`src/`**
Pasta principal com o código-fonte do aplicativo.

##### **`config/`**
- **`firebaseConfig.js`**: Configurações do Firebase, como chaves de API e detalhes do projeto.

##### **`contexts/`**
Gerencia os contextos globais utilizados no aplicativo:
- **`AuthContext.js`**: Contexto de autenticação, responsável por gerenciar o login e logout.
- **`CartoesEstudoContext.js`**: Contexto para gerenciamento de cartões de estudo, incluindo criação, edição e exclusão.

##### **`screens/`**
Contém as telas principais da aplicação:
- **`EdicaoCartaoScreen.js`**: Tela para edição de cartões de estudo.
- **`ListaCartaoScreen.js`**: Tela que exibe a lista de cartões de estudo.
- **`LoginScreen.js`**: Tela de login de usuário.
- **`RegistroScreen.js`**: Tela para registro de novos usuários.
- **`TarefasVencimentoProximoScreen.js`**: Tela que exibe tarefas com vencimento próximo.

#### Arquivos na Raiz
- **`.gitignore`**: Lista de arquivos e diretórios que devem ser ignorados pelo Git.
- **`App.js`**: Arquivo de principal do aplicativo, responsável por inicializar os contextos e a navegação.
- **`app.json`**: Configurações do projeto para o Expo.
- **`babel.config.js`**: Configurações do Babel para transpilar o código.
- **`package.json`**: Lista de dependências e scripts do projeto.
- **`package-lock.json`**: Arquivo gerado automaticamente para garantir a consistência de dependências.

---

## Bibliotecas Utilizadas

### Dependências Principais
- **`expo`**: Framework para desenvolvimento de aplicativos React Native.
- **`firebase`**: Plataforma para autenticação e banco de dados.
- **`@react-navigation/native`**: Biblioteca para navegação entre telas.
- **`@react-navigation/native-stack`** e **`@react-navigation/stack`**: Implementação de pilhas de navegação.
- **`@react-native-async-storage/async-storage`**: Armazenamento de dados local no dispositivo.
- **`react-native-modal-datetime-picker`**: Seleção de data e hora.

### DevDependencies
- **`@babel/core`**: Ferramenta para transpilar o código JavaScript.

---

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/study-app.git
   cd study-app

2. Instale as dependências:

npm install


3. Configure o Firebase:

Adicione as chaves do seu projeto Firebase em src/config/firebaseConfig.js.



4. Inicie o aplicativo:

npm start




---

Funcionalidades

Autenticação de usuários (login e registro).

Gerenciamento de cartões de estudo: Criar, editar, listar e excluir.

Visualização de tarefas com vencimento próximo.

Design responsivo e intuitivo.



---

Contribuição

Contribuições são bem-vindas! Para colaborar:

1. Faça um fork do repositório.


2. Crie uma branch para a funcionalidade ou correção: git checkout -b minha-feature.


3. Envie seu PR para análise.




---

Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

Adapte conforme necessário para incluir informações específicas ou customizações do seu projeto.

