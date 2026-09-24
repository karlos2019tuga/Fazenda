# Fazenda BlackStone — Android

App Android criada a partir do site Fazenda BlackStone + Supabase.

## Incluído
- Nome: **Fazenda BlackStone**
- Modo ecrã inteiro
- Login/Supabase
- Produtos, encomendas, estados e faturas
- Copiar mensagem do cliente através da área de transferência nativa
- Partilhar fatura através do menu de partilha do Android
- Notificação nativa quando entra nova encomenda
- Notificação nativa quando muda o estado da encomenda
- Ícone próprio da Fazenda BlackStone

## Importante sobre notificações
As notificações desta versão vêm do Supabase Realtime carregado na app.
Funcionam em tempo real enquanto a app/processo continua ativo.

Para receber notificações **garantidas com a app totalmente fechada**, é necessário
adicionar Firebase Cloud Messaging (FCM). Isso precisa de um ficheiro
`google-services.json` criado num projeto Firebase para o package:

`pt.fazendablackstone.app`

Depois pode ser adicionada a segunda fase de push notifications.

## Abrir no Android Studio
Abra esta pasta como projeto Android.

Configuração:
- compileSdk 35
- targetSdk 35
- minSdk 26
- Java 17 recomendado

## APK
Android Studio:
Build > Build APK(s)

O APK debug ficará em:
`app/build/outputs/apk/debug/app-debug.apk`
