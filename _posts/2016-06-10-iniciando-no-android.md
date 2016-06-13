---
layout: post
title: "Um guia inicial sobre o desenvolvimento para Android"
categories: [software, android]
author: Rodrigo Bresan
comments: true
lang: pt
ref: starting-android
---
Nos últimos 3 anos tive o prazer de trabalhar com a plataforma Android, e não tenho como não dizer a vocês que foi um caminho, no mínimo *conturbado*, principalmente no que diz respeito à busca por materiais de estudo, ainda mais no que se refere à conteúdo em português. Este post tem então como propósito fornecer um guia para quem está se aventurando nesse mundo, bem como também servir como uma coletânea de materiais e referências que virão a ser úteis para você como desenvolvedor.

<!--more-->

O desenvolvimento Android se dá principalmente através da linguagem de programação **Java**, então é importante que você já possua uma noção sobre como a linguagem funciona, entendendo como sua sintaxe é, e certamente possuindo conceitos de OOP (Orientação a Objetos) bem definidos, visto que o Android utiliza de muitos recursos de herança e polimorfismo – *não é como se fosse um bixo de sete cabeças, mas você precisa ter uma mínima noção de como funcionam tais conceitos, caso contrário o entendimento dos diversos componentes e comportamentos existentes no Android irão ser de difícil compreensão.*

Caso você ainda não possua uma boa base de Java, recomendo que dê uma olhada em algum curso, ao menos para ter um mínimo conhecimento da linguagem. O curso de Java da Codecademy é uma boa recomendação para quem quiser aprendar mais sobre a linguagem, cujo link vou deixar ao final do post.

# Cursos

Hoje na comunidade de desenvolvimento Android você pode encontrar diversos materiais de estudo, sendo tanto eles na forma de apostilas, livros, vídeo aulas e também cursos. Nessa seção iremos ver alguns cursos existentes, boa parte deles em inglês, porém de fácil compreensão, bastando apenas ir acompanhando o desenvolvimento das aplicações e entendo minimamente o contexto do tópico apresentado.

[Desenvolvimento Android pela Udacity (Iniciantes):](https://www.udacity.com/course/android-development-for-beginners--ud837) Um curso voltado para estudantes que são novos na programação e querem aprender como desenvolver aplicações para Android. **Não é necessário nenhuma experiência com programação para começar este curso.**

[Desenvolvimento Android pela Google (Intermediários):](https://www.udacity.com/course/ud853) Um curso também da Udacity, porém criado pela Google, que visa ensinar os conceitos fundamentais do desenvolvimento Android através de vídeos e projetos.

[Programando em Android pela Universidade de Maryland (Coursera):](https://www.coursera.org/course/androidpart1) Um curso online oferecido pela Unviersidade de Maryland, visando abordar desde as etapas de instalação do Android Studio, chegando até ao desenvolvimento de telas e interfaces.

[Google CodeLabs:](https://codelabs.developers.google.com/?cat=Android) Site oficial da Google contendo diversos tutoriais e as etapas existentes na criação de uma aplicação, cobrindo tópicos desde Android Wear, Google Compute Engine, Project Tango, Google APIs e desenvolvimento iOS.

# Android SDK

O Kit de Desenvolvimento Android, comumente referido como Android SDK (Android Software Development Kit), é uma coletânea de ferramentas que vão lhe auxiliar a desenvolver aplicações para a plataforma Android. O SDK do Android contém todas as bibliotecas e recursos necessários para que você possa desenvolver para o Android.

O link para download do Android SDK, junto também do Android Studio (o qual falarei na próxima seção) estão disponíveis ao final desse post.

# IDE (Integrated Development Environments)

Como todos sabemos, uma IDE hoje em dia é indispensável para o desenvolvimento, seja por questões de produtividade, possuindo atalhos e macros, como também por redução da ocorrência de erros, visto que muitas hoje em dia já avisam no caso de uma possível incidência de erro no código.

O Android Studio é uma IDE voltada para o desenvolvimento de aplicações Android, e atualmente roda em cima da IDE IntelliJ.

Anteriormente era muito comum o desenvolvimento de aplicações utilizando o Eclipse com o plugin ADT, tanto que se você for procurar por tutoriais mais antigos, verá que basicamente apenas o Eclipse era utilizado. Um ponto importante aqui é que o Eclipse **ainda serve** para o desenvolvimento de aplicações Android, porém é uma prática **não recomendada tanto pela Google quanto pela comunidade**, visto sua escassez de recursos em comparação com o Android Studio. Caso você planeje iniciar um projeto novo, o mais recomendado é que o faça utilizando o Android Studio.

# Emulador

O propósito do emulador é o de permitir rodar nossas aplicações desenvolvidas, funcionando como um dispositivo Android real, porém emulado em seu computador. Hoje em dia podemos contar com três principais ferramentas no que diz respeito à emular um dispositivo Android para rodar nossas aplicações.

- Emulador nativo do Android SDK: É um emulador que vem junto com o SDK do Android. Há um tempo atrás era mal visto na comunidade por conta de sua lentidão, porém com a versão 2.0 do Android Studio, atualmente roda bem liso, similar à um dispositivo real.

- Genymotion: é um emulador que roda em cima da VirtualBox, portanto é uma imagem do Android. É bem estável e possui uma performance muito boa, tanto que eu ainda o utilizava como principal emulador até a chegada do novo emulador do Android Studio 2.0.

Há algumas outras opções não tão conhecidas, porém se você procurar pela internet são fácilmente encontradas. **Recomendo que rodem os seus aplicativos em um dispositivo real**, principalmente pelo fato de ser o mais próximo que você terá de um aplicativo em produção – **aconselho principalmente por questões de usabilidade**, visto que no emulador você fica em muitos casos limitado a utilizar o mouse e o teclado físico para controlá-lo.

# Comece a desenvolver!

Como citado no post anterior [Começando a programar](http://bresan.github.io/articles/2016-06/aprendendo-a-programar), o fator chave que vai te fazer aprender algo, é certamente a prática daquele tópico.

Um ótimo vídeo que mostra como fazer um simples aplicativo de calculadora pode ser visualizado abaixo. Está em inglês, porém é só prestar atenção nas etapas que fica bem claro de entender. No caso de qualquer dúvida, pode mandar diretamente na seção de comentários que respondo:-)

[![Video tutorial](http://img.youtube.com/vi/Xl1x8eazbrM/0.jpg)](http://www.youtube.com/watch?v=Xl1x8eazbrM)

Uma recomendação pessoal é que você não apenas assista ao vídeo, mas também vá realizando as etapas simultaneamente, para que assim você possa absorver melhor o conteúdo.

Outros materiais muito bons para quem está iniciando podem ser encontrados abaixo:

[Site oficial do Android:](https://developer.android.com/develop/index.html?hl=pt-br) um site contendo todas as referências existentes no Android, desde como instalar, APIs da plataforma, exemplos, dentre diversas outras referências.

[Treinamento do site oficial do Android:](https://developer.android.com/training/index.html) um guia para você encontrar exemplos de código, bem como também algumas seções que ensinam passo a passo como desenvolver uma aplicação, passando desde etapas como criando sua primeira aplicação, como suportar os diversos dispositivos e seus diversos tamanhos de tela, controlando o ciclo de vida da sua aplicação, persistir os dados na sua aplicação, interagir com outros aplicativos, dentre diversos outros tutoriais.

[GitHub:](http://github.com/) como já dito no post anterior, o GitHub contém uma gama muitíssimo valiosa de projetos open source para os desenvolvedores que estão aprendendo, visto que é possível encontrar diversos exemplos de aplicações já feitas por outros usuários.

Um excelente livro e guia de referência para o desenvolvimento Android é o [The Busy Coder’s Guide to Android Development](http://commonsware.com/Android/), um livro extremamente compreensível e didático, apesar de ser um pouco volumoso – a última vez que vi, tinha mais de 3000 páginas. Contém exercícios muito bons para a fixação do material apresentado.

# Utilize as ferramentas disponíveis

Uma ferramenta indispensável que vem junto com o Android SDK é o ADB, do inglês Android Debug Bridge, que serve para realizar a conexão entre o seu dispositivo e o seu computador. Em boa parte dos casos você não verá tal ferramenta sendo utilizada explicitamente, mas a sua IDE (provavelmente Android Studio), fará uso do ADB para realizar toda e qualquer conexão - instalar o aplicativo, realizar debug, capturar logs - com seu dispositivo. É uma ferramenta muito útil pois permite que você possa controlar seu dispositivo totalmente pelo terminal, possibilitando ver todos os logs do sistema através do comando logcat, bem como as funcionalidades já descritas.

# Nota final

Espero que com esse *mini* guia, vocês possam ter uma noção melhor de como o desenvolvimento para Android é realizado, bem como também de quais materiais lhe serão útil durante o dia a dia como desenvolvedores.

No caso de qualquer dúvida e/ou erro de minha parte, fiquem a vontade para postar nos comentários.

## Links de referência

[Curso de Java da Codecademy](https://www.codecademy.com/pt-BR/learn/learn-java)

[Android Studio + SDK](https://developer.android.com/studio/index.html)

[Genymotion](https://www.genymotion.com/)
