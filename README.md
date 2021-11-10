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
* **HTML _(home.component .html) -> CSS (home.component .css) -> TS (home.component .ts)_** **_(< app-home> ? < /app-home>)_**
* Não necessáriamente presisa ter style **(.css)** no componente, apenas ter o HTML e o TS
* Não é obrigado a ter o aquivo **.html**, pode-se colocar o template dentro do TS

#### 2. Attribute Directives
* Altera a **aparência** e o **comportamento** de um elemento, componente ou outra diretiva
<img width="500" alt="directive" src="https://user-images.githubusercontent.com/78311671/141170343-95673c50-d1ab-4ad7-ad50-c54451b348d3.png">

* Decorator = padão de projeto; Ex.: **@Directive**
<img width="500" alt="exemploo" src="https://user-images.githubusercontent.com/78311671/141177730-aa0029a8-252f-42e1-b55c-d6201a8f6845.png">

#### 3. Structural Directives
* Altera o layout **adicionando** e **removendo** elementos da **_DOM_**
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141179109-b92fddd2-322a-48cd-ae55-99325fb0959d.png">

#### 4. Property Binding []
* Necessidade de comunicação entre o código TS e o código HTML
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141181179-2b692030-7da5-483e-9998-9351fcf230af.png">

#### 5. Event Binding ()
* Como ligar um evento do HTML para um método que está dentro de um componente associado aquele HTML
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141181619-8e0e77b1-353f-4e77-8af0-88c585426e3b.png">

#### 6. One Way Data Binding
* TS para HTML
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141182338-003a1298-c910-4e34-bdfe-d081b24d6417.png">

#### 7. Two Way Data Binging
* Se atualiza o TS - altera o HTML // Se atualiza o HTML - altera o TS
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141182866-53faca11-b9cf-4874-af24-20d5b4ba9791.png">

#### 8. Angular Router 
* sempre que navegamos na aplicação, basicamente é feito um mapeamento entre a rota e o componente
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141209873-1989073c-740a-45c9-98ae-d646809378ec.png">
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141210110-53b2f871-fd45-4d0f-9a37-63a6979bd914.png">

#### 9. Angular Pipes
* Processamentos feitos em cima de variáveis
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141210486-f9fddc16-6615-4944-826e-b2b2cff990e8.png">
<img width="500" alt="exemplo" src="https://user-images.githubusercontent.com/78311671/141210553-8a502eb0-1358-4e8d-8a26-efa3dc6bf015.png">

* Pode ser usado uma cadeia de Pipes - CHAINING 

