# Aplicativo Android - CARTÃO DE VISITA

![](foto1.jpg) ![](foto2.jpg) ![](foto3.jpg)

Aplicativo Android para cadastro de cartões de visita

## Funcionalidades

Cadastro , seleção de cores para os cartões e compartilhamento

## Primeiros Passos

Siga estas instruções para ter uma cópia do projeto funcionando em seu computador.

> Caso não esteja interessado no desenvolvimento, vá para a página [Releases](https://github.com/thibbatista/Cartao-de-Visitas/releases) e baixe o compilado para executar.

### Pré-requisitos

O que você precisará:

```
IDE Android Studio
Android SDK
JDK
Gradle
```

### Instalando

Siga os passos a seguir para rodar esta aplicação em seu computador.

#### Variáveis de ambiente

Informe ao Android Studio o caminho da sua SDK

```
No Windows, vá em Painel de Controle → Sistema e Segurança → Sistema → Configurações avançadas do sistema → Variáveis de Ambiente → Novo
```

Insira a variável de ambiente abaixo:

```
ANDROID_HOME = <<diretório_do_android_sdk>>
```

> Você pode ignorar esta etapa se preferir criar um arquivo local.properties dentro do diretório do projeto para especificar o valor de 'sdk.dir'

#### Obtendo uma cópia

Faça o download, use uma ferramente Git ou a própria IDE Android Studio para clonar este repositório:

```
Na tela de boas vintas do Android Studio, vá em Check out project from Version Control → Git
Informe a URI e clique em Clone, na pergunta sobre criar um projeto do Android Studio, clique em Yes
Marque Create project from existing sources e clique em Next/Yes até finalizar, mantenha as opções padrão
```

### Executando

Execute o projeto:

```
No Android Studio, clique em Run → Run 'app'
```

> A primeira execução irá demorar, pois a IDE irá montar e instalar o APK no dispositivo.


## Demonstração

#### Utilização


```
Na tela inicial toque em + para cadastrar um novo cartão
Adicione os dados, em cor adicione uma cor em hexadecimal  ( ex: #FFFFFF para cor Branca) -> Confirmar
toque no cartão para compartilhar.
```



## Deployment

Distribua este projeto como um arquivo *.apk para instalar em um dispositivo Android ou enviar para a Play Store:

```
No Android Studio, com o botão direito sobre o projeto, vá em Build → Build Bundle(s) / APK(s) → Build APK(s)
```

## Tecnologias utilizadas

* [Kotlin](https://kotlinlang.org/) 
* [Android Studio](https://developer.android.com/studio) 
* [Gradle](https://gradle.org/) 
* [XML](https://fontawesome.com/) 

## Ferramentas utilizadas

* RecyclerView
* Room DataBase

## Licença

Este projeto está licenciado sob a MIT License - leia [LICENSE.md](LICENSE.md) para mais detalhes.

