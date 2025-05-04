# Autenticação com Google - Android (Java)

Este é um exemplo **simples** de autenticação com Google usando Java no Android Studio.

## Pré-requisitos

1. Android Studio instalado.
2. Conta Google para usar o [Google Cloud Console](https://console.cloud.google.com/).

## Como configurar

1. Vá para o [Google Cloud Console](https://console.cloud.google.com/).
2. Crie um novo projeto.
3. Ative a API "Google Sign-In" e "Google Play Services".
4. Vá em "Credenciais" → "Criar credenciais" → "ID do cliente OAuth 2.0".
5. Escolha: Tipo **Aplicativo Android**.
6. Adicione o nome do pacote: `com.example.googleauthandroid`.
7. Adicione o SHA-1 do seu projeto (veja no terminal do Android Studio com: `./gradlew signingReport`).
8. Copie o `client_id` e edite no código se necessário.

## Telas

Apenas uma tela com botão de login Google.

## Licença

Projeto educacional.