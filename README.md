# Gifter - CRUD Flutter N2
Projeto avaliativo 4º Semestre de Engenharia de Software, na matéria de Desenvolvimento Mobile.

## Integrantes do Grupo
- Victor José Brigeiro da Rocha
- André Gustavo Specht
- Arthur Vinicius Hassuma

## Proposta de Desenvolvimento
App com Autenticação em Provedor do Firebase

- Objetivo: Fazer um login em app com login social do firebase.

## Versão Mínima do SDK
- minSdkVersion: 23

## Atualmente, projeto:

1. Páginas de interação com a entrada social google:

| <img src="https://imgur.com/AGWgS5l.png" />  | <img src="https://imgur.com/brIcwsw.png" />  |
| ----- | ----- |
| <p align="center">Entrada</p> | <p align="center">Home</p> |

## Funcionalidades por Tela

### Tela de Login
- Botão para autenticação com Google

### Tela Home
- Exibir informações do usuário autenticado (nome, e-mail, foto de perfil)
- Botão de Logout

## Tipos de Erros do Provedor Escolhido (Google)
- `sign_in_canceled`: O usuário cancelou o login.
- `network_error`: Erro de rede durante o login.
- `account_exists_with_different_credential`: A conta já existe com uma credencial diferente.
- `invalid_credential`: A credencial fornecida é inválida.
- `user_disabled`: A conta do usuário foi desativada.
- `operation_not_allowed`: A operação não é permitida.
- `invalid_verification_code`: O código de verificação é inválido.
- `invalid_verification_id`: O ID de verificação é inválido.

## Dependências Utilizadas
- `flutter`: ^3.0.0
- `firebase_core`: ^3.8.0
- `firebase_auth`: ^5.3.3
- `google_sign_in`: ^6.2.2
- `flutter_signin_button`: ^2.0.0

## Instruções para Configuração/Importação do Projeto

### Pré-requisitos
- Flutter SDK: ^3.0.0
- Dart SDK: ^2.17.0
- Android Studio ou Visual Studio Code
- Android SDK: ^23

### Passos para Configuração
1. Clone o repositório:
 ```
   git clone https://github.com/seu-usuario/seu-repositorio.git
 ```
2. Navegue até o diretório do projeto:
 ```
  cd seu-repositorio
 ```
3. Instale as dependências:
 ```
  flutter pub get
 ```
4. Configure o Firebase:
 - Adicione o arquivo google-services.json na pasta android/app.
 - Adicione o arquivo GoogleService-Info.plist na pasta ios/Runner.
5. Execute o projeto:
 ```
 flutter run
 ```

## Projeto rodando

[Assista ao vídeo aqui](https://drive.google.com/file/d/1--qNLjsO53p23pAxjZkTe0CDZTph_LWm/view?usp=sharing)



## Contas Pessoais

[<img src="https://avatars.githubusercontent.com/u/97479966" width="60"/>![span](https://placehold.co/10x60/FFA500/FFA500.png)![span](https://placehold.co/220x60/000000/FFFFFF/png?text=Victor%20Rocha)](https://victorrochar.github.io)

[<img src="https://avatars.githubusercontent.com/u/128716535" width="60"/>![span](https://placehold.co/10x60/800080/800080.png)![span](https://placehold.co/220x60/000000/FFFFFF/png?text=André%20Specht)](https://andreespecht.github.io)

[<img src="https://avatars.githubusercontent.com/u/61090154" width="60"/>![span](https://placehold.co/10x60/FF0000/FF0000.png)![span](https://placehold.co/220x60/000000/FFFFFF/png?text=Arthur%20Hassuma)](https://arthurhassuma.github.io)