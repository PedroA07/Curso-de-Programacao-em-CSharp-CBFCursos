# INSTALANDO PROGRAMAS E RECURSOS

## Primeira mente abra o seu Prompt de Comando:
Use o atalho **"Win + R"** e digite **"cmd"** e pressione **"Enter"**:

<img height="150" alt="win+r" src="../Instalacao/img/win+r.jpg"/>

Agora com o Prompt de Comando aberto pesquise pelo executavel para ver se já encontrasse instalado:
````
>>> csc
````
<img height="200" alt="cmd" src="../Instalacao/img/cmd.png"/>

Se não estiver intalado o executavel, como na imagem a cima. Faça os seguintes passos:

## Instalar o DotNet
- Instalar o <a href="https://dotnet.microsoft.com/pt-br/download" targer="_blanc">DotNet</a>;

<img align="center" height="180" alt="dotnet" src="../Instalacao/img/dotnet.png"/>

## Instalar o Visual Studio Code
- Instalar o <a href="https://code.visualstudio.com/download" targer="_blanc">Visual Studio Code</a>;

<img align="center" height="200" alt="vscode" src="../Instalacao/img/vscode.png"/>

#
- Já dentro do **Visual Studio Code** na aba de **extensões** pesquise por **C#** e instale;

<img align="center" heigt="200" alt="extensao.vscode" src="../Instalacao/img/extensao.vscode.jpg"/>

## Instalar o Visual Studio Community
- Instalar o <a href="https://visualstudio.microsoft.com/pt-br/downloads/" targer="_blanc">Visual Studio Community</a>

<img align="center" height="200" alt="vscommunity" src="../Instalacao/img/vscommunity.png"/>

## Intalação do Path CSC no Windows
Após concluir todas as instalações de progrmas e recursos, vamos para a instalação do Path CSC no Windows:

- Pesquise na busca do windows por **"variáveis"** e selecione a opção **"Editar as variáveis de ambiente do sistema"** como segue na imagem a seguir:

<img align="center" height="250" alt="pesq.win" src="../Instalacao/img/pesq_win.jpg"/>

##

- Irá abrir uma janela de **"Propriedade do Sistema"**, vá para a aba **"Avançado"** e clique na opção **"Variáveis de Ambiete"**:

<img align="center" height="300" alt="prop_sistema" src="../Instalacao/img/prop_sistema.jpg"/>

##

- Uma nova janela se abrirá. Na área de **"Varáveis do Sistema"**, procure por **"Path"** e clique duas vezes:

<img align="center" height="300" alt="variaveis_sistema" src="../Instalacao/img/variaveis_sistema.jpg"/>

##

- Agora abra seu **"Explorador de Arquivos"** para ir até a pasta em que se encontra nosso compilador **"csc.exe"**, e copie o caminho, que geralmente é padrão como vem a seguir:
````
>>> C:\Windows\Microsoft.NET\Framework64\v4.0.30319
````

<img align="center" height="200" alt="variaveis_sistemacaminho_arqv" src="../Instalacao/img/caminho_arqv.jpg"/>

##

- Volte para a janela que foi aberta quando clicamos na opção **"Path"**, clique em **"Novo"**, e cole o **"caminho da pasta"**:

<img align="center" height="300" alt="cola_caminho" src="../Instalacao/img/cola_caminho.jpg"/>

##

- **"Reinicie o computador"** e pronto para começar.