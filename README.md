# Mini Crud✏️
__Este é um aplicativo simples que contém um exemplo simples de uma mini aplicação CRUD (Create, Read, Update, Delete) desenvolvida em Java usando o framework Spring Boot.__

## ⚙️Funcionalidades

### _👨‍💼Classe Admin:_
`onCreate()`
- Este é um método de ciclo de vida da atividade que é chamado quando a atividade é iniciada pela primeira vez. Neste método, as referências aos elementos de interface do usuário (EditText, TextView e Button) são inicializadas. O botão btnAdmin é inicialmente definido como invisível.

`buscar(View view)`

- Este método é chamado quando o usuário clica no botão "BUSCAR". Ele percorre a lista listinha de usuários procurando pelo login inserido na caixa de busca. Se o login for encontrado, o texto "Login [login] encontrado!" é exibido na TextView resultado, o usuário encontrado é armazenado em encontrado, e o botão btnAdmin é definido como visível. O texto do botão é definido como "TORNAR COMUM" ou "TORNAR ADMIN", dependendo do status do usuário encontrado.

`statusAdmin(View v)`
- Este método é chamado quando o usuário clica no botão btnAdmin. Ele altera o status de admin/comum do usuário encontrado em encontrado e atualiza o texto do botão btnAdmin para refletir o novo status.

### _📂Classe Cadastro:_
- Ao preencher os campos de login, senha e confirmação de senha e clicar no botão "Cadastrar", o código verifica se as senhas digitadas são iguais. Se forem iguais, o código cria um novo objeto de usuário com os dados fornecidos e adiciona-o a uma lista estática de usuários chamada "listinha". Caso contrário, uma mensagem de erro é exibida informando que as senhas não coincidem.

### _👥Classe Usuario:_
- A classe `Usuario` possui três variáveis de instância: `login`, `senha` e `admin`. As duas primeiras armazenam o nome de usuário e senha do usuário, enquanto a terceira indica se o usuário tem permissão de administrador ou não.
- O construtor da classe recebe os valores de login, senha e admin como parâmetros e inicializa as variáveis de instância correspondentes.
- Os métodos `get` e `set` são utilizados para acessar e modificar as variáveis de instância de forma segura e encapsulada.

## 🛠️Como executar o aplicativo:
__Para executar o aplicativo em uma máquina local, siga as seguintes etapas:__

- Baixe e instale o Android Studio.
- Clone este repositório em seu computador.
- Abra o Android Studio e escolha a opção "Open an existing Android Studio project".
- Navegue até o diretório em que você clonou o repositório e selecione-o.
- Execute o aplicativo em um dispositivo Android ou em um emulador.

                 

## ✍️Autores

__- [@cemeterydriiver](https://www.github.com/cemeterydriiver)__
