![GitHub](https://img.shields.io/github/license/giupolub/Convidados)
# Convidados

Com esse aplicativo é possível criar uma lista de convidados.

## 🔨 Funcionalidades do projeto

Este aplicativo foi elaborado através do Navigation Drawer Activity. Com este template é possível criar atalhos de outras activities/fragments em uma janela lateral que fica armazenada em forma de "gaveta".

Para a criação de um novo convidado, basta selecionar o botão :heavy_plus_sign: no rodapé. Uma nova activity será aberta com um campo para entrar com o nome do convidado e outro para selecionar se ele está ausente ou presente. Ao pressionar o botão "SALVAR" o convidado será adicionado e a fragment padrão, que armazena todos os convidados, reabrirá com a lista atualizada. 

Além desta fragment, também existem outras duas, uma para armazenar apenas os convidados presentes e outra para os ausentes. Em todas elas é possível selecionar o convidado, para realizar uma edição, bem como, selecionar e segurar para removê-lo. Lembrando que para acessar as demais fragments, é preciso selecionar o atalho que fica na ActionBar (localizado na região superior).

![ezgif com-gif-maker](https://user-images.githubusercontent.com/110063157/182751662-2b8ecc9c-fa8f-44ef-abcd-6df3186add3b.gif)

## ✔️ Técnicas e tecnologias utilizadas

Tecnologias:

- [Kotlin](https://kotlinlang.org/)
- [Android Studio](https://developer.android.com/studio?hl=pt&gclid=Cj0KCQjwio6XBhCMARIsAC0u9aFcStoZloea7hLJnt5StTOh7VHBqr15T1HpjgvOY00QfByC4676HYAaAmxmEALw_wcB&gclsrc=aw.ds)

Técnicas:

- `Navigation Drawer Activity`: template com uma activity que possui uma janela lateral que armazena atalhos para outras activities/fragments
- `Fragment`: representa uma parte reutilizável da IU do seu app
- `View Binding`: busca de views do layout de forma segura
- `AlertDialog`: yma subclasse de diálogo que pode exibir um, dois ou três botões
- `Toast notification`: um aviso fornecendo um feedback simples sobre uma operação em uma pequena janela pop-up
- `Radio group e Radio button`: botões de opção permitem que o usuário selecione uma opção em um conjunto delas
- `startActivity`: navegação entre activities e fragments
- `Intent e Bundle`: para navegar entre as activities com parâmetros previamente estabelecidos
- `MVVM`: padrão de arquitetura com divisão de responsabilidades entre as classes
- `RecycleView`: lista que mostra grandes conjuntos de dados na IU enquanto minimiza o uso de memória
- `Adapter e ViewHolder`: necessários para a criação da RecycleView
- `SQLiteDatabase`: com métodos para criar, excluir, executar comandos SQL e realizar outras tarefas comuns de gerenciamento de banco de dados
- `LiveData`: diferente de um observável comum, o LiveData conta com reconhecimento de ciclo de vida, ou seja, ele respeita o ciclo de vida de outros componentes do app, como ativities e fragments
- `Singleton`: é um padrão de projeto de software, ele garante a existência de apenas uma instância de uma classe, mantendo um ponto global de acesso

## 📁 Acesso ao projeto

Você pode [acessar o código fonte do projeto inicial](https://github.com/giupolub/Convidados) ou [baixá-lo](https://github.com/giupolub/Convidados/archive/refs/heads/main.zip).

## 🛠️ Abrir e rodar o projeto

Após baixar o projeto, você pode abrir com o Android Studio. Para isso, na tela de launcher clique em:

- **Open project**
- Procure o local onde o projeto está e o selecione (caso o projeto seja baixado via zip, é necessário extraí-lo antes de procurá-lo)
- Por fim clique em OK

O Android Studio deve executar algumas tasks do Gradle para configurar o projeto, aguarde até finalizar. Ao finalizar as tasks, você pode executar o App 🏆
