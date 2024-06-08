# SHARED PREFERENCES
👨‍🏫PROJETO CRIADO PARA O CURSO DE ANDROID STUDIO EM KOTLIN.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
- Este aplicativo Android demonstra o uso de SharedPreferences para armazenar e recuperar valores simples de uma aplicação.

- O aplicativo permite que o usuário insira um valor em um EditText e, em seguida, salve esse valor utilizando SharedPreferences. Ele também pode editar o valor a qualquer momento e salvá-lo novamente.

- Este aplicativo é útil para demonstrar o uso básico de SharedPreferences para armazenar e recuperar dados simples em um aplicativo Android. Pode ser expandido para incluir mais funcionalidades, como a manipulação de vários valores de SharedPreferences, a utilização de diferentes modos de acesso e a implementação de controles adicionais de interface do usuário.

## FUNCIONALIDADES:
1. **Armazenamento de Valor:**
   - O valor inserido pelo usuário no EditText é armazenado usando SharedPreferences quando o botão "Editar" é clicado.
  
2. **Recuperação de Valor:**
   - O valor armazenado é recuperado do SharedPreferences e exibido no EditText sempre que a atividade é criada.

3. **Edição de Valor:**
   - O usuário pode editar o valor no EditText.
   - Ao clicar no botão "Editar", o valor editado é salvo novamente usando SharedPreferences.

## EXECUTANDO O PROJETO
### INSTALANDO O APK:
   - **Download do APK**: Acesse a pasta `./APK/` e encontre o arquivo `NomeDoApp.apk`.
   - **Transferência para o dispositivo**: Transfira o arquivo APK para o seu dispositivo Android. Isso pode ser feito via cabo USB, Google Drive, email ou qualquer outro método de transferência de arquivos.
   - **Instalação**:
     1. No dispositivo Android, vá para `Configurações` > `Segurança` e habilite a opção `Fontes desconhecidas` (Isso permite a instalação de aplicativos fora da Google Play Store).
     2. Navegue até o local onde o APK foi salvo (usando um gerenciador de arquivos).
     3. Toque no arquivo `NomeDoApp.apk` para iniciar a instalação.
     4. Siga as instruções na tela para concluir a instalação.
   - **Execução**: Após a instalação, você pode abrir o aplicativo diretamente da tela de instalação ou encontrá-lo na gaveta de aplicativos do seu dispositivo.

### ANDROID STUDIO:
#### ABRINDO O PROJETO:
   - **Preparação do ambiente**:
     1. Certifique-se de que você tenha o [Android Studio](https://developer.android.com/studio) instalado em sua máquina.
     2. Instale as dependências necessárias (SDKs, emuladores, etc.) conforme indicado pela documentação do Android Studio.

   - **Abrindo o projeto no Android Studio**:
     1. Abra o Android Studio.
     2. Na tela de boas-vindas, selecione `Open an existing project`.
     3. Navegue até o diretório `./CODIGO` onde o projeto foi clonado e selecione-o.
     4. Aguarde enquanto o Android Studio indexa o projeto e baixa as dependências necessárias.

   - **Executando o projeto**:
     1. Conecte um dispositivo Android via USB ou configure um emulador de dispositivo Android no Android Studio.
     2. Certifique-se de que o dispositivo/emulador está selecionado na barra de dispositivos do Android Studio.
     3. Clique no botão `Run` (ícone de play) para compilar e executar o aplicativo.

   - **Depuração**:
     - Para iniciar a depuração, clique no botão `Debug` (ícone de inseto) e siga as instruções do Android Studio para definir pontos de interrupção e inspecionar variáveis.

#### GERANDO O APK:
   Depois de melhorar o projeto, você pode gerar o APK novamente. Siga os passos abaixo para gerar o APK usando o Android Studio:

   1. **Abrir o Projeto**:
      - Abra o Android Studio.
      - Vá para `File` > `Open...` e selecione o diretório `./CODIGO` do seu projeto.

   2. **Construir o Projeto**:
      - Certifique-se de que todas as dependências estejam atualizadas e que o projeto esteja compilando corretamente.
      - Vá para `Build` > `Clean Project` para limpar o projeto.
      - Depois, vá para `Build` > `Rebuild Project` para reconstruir o projeto.

   3. **Gerar o APK**:
      - Vá para `Build` > `Build Bundle(s) / APK(s)` > `Build APK(s)`.
      - O Android Studio começará a compilar o projeto e a gerar o APK.
      - Após a conclusão, uma notificação aparecerá no canto inferior direito da tela com a mensagem `APK(s) generated successfully.`
      - Clique na notificação ou vá para `locate` para encontrar o APK gerado, que geralmente está localizado em `./app/build/outputs/apk/release/`.

   4. **Testar o APK**:
      - Transfira o APK gerado para o seu dispositivo Android e instale-o conforme as instruções na seção **EXECUTANDO O PROJETO** > **APK** acima.

## CREDITOS:
- [PROJETO FEITO PELO VILHALVA](https://github.com/VILHALVA)
- [PROJETO CRIADO PARA O CURSO DE ANDROID STUDIO EM KOTLIN](https://github.com/VILHALVA/CURSO-DE-ANDROID-STUDIO-EM-KOTLIN)



