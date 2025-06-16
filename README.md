# Projeto React Native - Avaliação

## Como fazer um emulador no Android Studio

1. Abra o Android Studio.
2. Vá em **More Actions** > **Virtual Device Manager**.
3. Clique em **Create Virtual Device**.
4. Escolha um dispositivo (ex: Medium phone) e clique em **Next**.
5. Selecione uma imagem do sistema (API 30 ou superior recomendado).
6. Clique em **Download**, depois em **Next** e depois **Finish**.
7. Clique no botão de **play (▶)** para iniciar o emulador.

## Como habilitar o SDK

Primeiro ir no Android Studio e ir em: More Options > SDK Manager > SDK Tools e instalar o NDK e Android SDK Command
 
Depois de instalado no seu projeto dentro da pasta android crie um arquivo chamado local.properties e coloque
sdk.dir=C:\\Users\\seuusuario\\AppData\\Local\\Android\\Sdk
 
Logo após abra o powershell e copie e cole:
cd "C:\Users\seuusuario\AppData\Local\Android\Sdk\cmdline-tools\latest\bin"
.\sdkmanager.bat --licenses

 E aceite todas as solicitações que irá aparecer!

## Como configurar o ANDROID_HOME e JAVA_HOME

1. abra as variaveis de ambiente
2. crie duas novas variaveis chamada ANDROID_HOME e JAVA_HOME
3. escreva o caminho da pasta tanto para o android home e java home
4. Ainda em Variáveis de Ambiente, selecione a variável Path e clique em Editar. Depois, adicione as seguintes entradas:
 
%ANDROID_HOME%\platform-tools
%ANDROID_HOME%\emulator
%JAVA_HOME%\bin
 
Clique em OK em todas as janelas para salvar as alterações.

### Windows
