# angular-crud
Aprendendo Angular
--------------

### O que é Angular?
* Angular é um framework JavaScript desenvolvido pelo Google para criação de 'aplicações Web SPA (simple page application)' baseada em componentes

### Versões do Angular:
* *Versão 1* - AngularJS
* A partir da *Versão 2*, foi criado um Novo Angular (Comp.)
* Pularam a *Versão 3* e foram direto para *Versão 4* e assim por diante...

### Command Line Interface
* Usado frequente CLI
* Instalação feita a partir do *__npm i -g @angular/cli__*
* Criando a aplicação a partir do *__ng new minha-app__*

### TypeScript
* Linguagem criada pela **Microsoft**
* O código escrito em TypeScript é **compilado** para JavaScrit, pois o browser não reconhece a sintaxe do TS
* TS é um Superset de JS, possui tudo que o JS tem e acrescenta uma série de funcionalides a mais - (TS possui **Tipagem Forte**)...

### Árvore de Componentes - exemplo
* Começa a aplicação, a partir de um componente principal (raiz da aplicação) - APPComponent
* APPComponent -> Header -> Nav -> List -> Item
* APPComponent -> Header -> Nav -> List -> Item
* APPComponent -> Content -> ContentTitle
* APPComponent -> Content -> ProductCrud -> ProductForm -> Input
* APPComponent -> Content -> ProductCrud -> ProductForm -> Button

### Inicialização da APP
* 1º arquivo **_main.ts_**
* Este aquivo chama o **_AppModule_**
* **_main.ts -> AppModule -> AppComponent -> x_**

### O que é um Componente?
* "Um pedaço dentro da aplicação", um trecho de código que representa um componente visual da tela
* Componente Visual: **HTML -> CSS -> TS**

### Anatomia do Módulo
<img width="500" alt="anatomia-do-modulo" src="https://user-images.githubusercontent.com/78311671/140981629-d90765e8-695a-4a13-bc6a-5de367ebad76.png">

### Organização Usando Módulo
<img width="500" alt="organiacao" src="https://user-images.githubusercontent.com/78311671/140982338-6681bead-3604-4939-a425-35a5f98dc158.png">

### Elementos do Angular #1
#### 1. Componente Angular 
* Formado por via de regra, por 3 partes: 
*      **HTML _(home.component.html)_ -> CSS _(home.component.css) -> TS _(home.component.ts)_  /// -> _(<app-home></app-home>)_
* Não necessáriamente presisa ter style **(.css)** no componente, apenas ter o HTML e o TS
* Não é obrigado a ter o aquivo **.html**, pode-se colocar o template dentro do TS

#### 2. Attribute Directives
* Altera a **aparência** e o **comportamento** de um elemento, componente ou outra diretiva
<img width="500" alt="directive" src="https://user-images.githubusercontent.com/78311671/141170343-95673c50-d1ab-4ad7-ad50-c54451b348d3.png">

* Decorator = padão de projeto; Ex.: **@Directive**
<img width="500" alt="directive" src="https://user-images.githubusercontent.com/78311671/141177730-aa0029a8-252f-42e1-b55c-d6201a8f6845.png">




