# 🌤️ Qual Comprar? — Portal Editorial

<p align="center">

  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff" alt="HTML5">

  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff" alt="CSS3">

  <img src="https://img.shields.io/badge/Google%20Fonts-Open%20Sans-4285F4" alt="Google Fonts">

</p>

## 📌 Sobre o Projeto

O **Qual Comprar?** é uma réplica de uma interface web inspirada na arquitetura visual de portais de notícias e blogs de tecnologia.

O projeto foi desenvolvido com base nos desafios práticos propostos pela plataforma **ProgramadorBR**, tendo como objetivo reproduzir a estrutura de um artigo editorial relacionado à **eficiência energética de eletrodomésticos**.

O conteúdo aborda o impacto de equipamentos como **geladeiras e chuveiros elétricos** no consumo de energia, relacionando conceitos de potência elétrica, consumo em kWh e custos na fatura de eletricidade.

Além do conteúdo editorial, o projeto procura demonstrar boas práticas de **HTML semântico, CSS3, tipografia, organização visual e Box Model**.

---

## 🌐 Demonstração Online

Acesse a versão publicada do projeto através da Vercel:

**🔗 https://projeto-qual-comprar.vercel.app/**

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica da página
- **CSS3** — Estilização e organização do layout
- **Google Fonts** — Utilização da família tipográfica Open Sans
- **HTML5 `<figure>` e `<figcaption>`** — Estruturação semântica de imagens e legendas
- **CSS Box Model** — Controle de dimensões, espaçamentos e alinhamentos

---

## 🎨 Engenharia de Estilos

### Tipografia

A interface utiliza a família tipográfica **Open Sans**, disponibilizada através do Google Fonts.

Foram definidos diferentes pesos tipográficos para estabelecer uma hierarquia visual entre títulos, subtítulos, textos corridos e elementos de navegação.

### Hierarquia de Conteúdo

O layout utiliza diferentes limites de largura para equilibrar a apresentação visual:

- **Container principal:** até `888px`
- **Área de conteúdo textual:** até `648px`

Essa diferenciação permite manter uma largura confortável para leitura, evitando linhas excessivamente longas em ecrãs de maior resolução.

### Semântica Multimédia

As imagens são estruturadas utilizando elementos semânticos do HTML5:

```html
<figure>
   <img src="imagem.jpg" alt="Descrição da imagem" />
   <figcaption>Crédito da imagem</figcaption>
</figure>
```

As imagens utilizam dimensões fluidas para se adaptarem à largura disponível.

### Identidade Visual

A interface utiliza uma paleta visual com destaque para o **laranja `#fd8a24`**, aplicado principalmente em elementos de navegação e chamadas para ação.

A barra superior de navegação permanece fixa durante a navegação, facilitando o acesso aos principais elementos da página.

---

## 📐 Conteúdo e Conceitos Abordados

O artigo apresenta uma abordagem introdutória ao **consumo de energia elétrica**, relacionando conceitos físicos com situações do quotidiano.

### ⚡ Quilowatt-hora

O **kWh** é utilizado como unidade de referência para representar o consumo de energia elétrica.

O projeto explora a relação entre:

- potência elétrica;
- tempo de utilização;
- energia consumida;
- custo estimado na fatura.

### 🧊 Geladeiras

A análise considera o funcionamento de uma geladeira e o processo de manutenção da temperatura interna.

O conteúdo utiliza como referência um consumo médio de aproximadamente **93 kWh por mês**, permitindo discutir o impacto desse equipamento no consumo residencial.

### 🚿 Chuveiros Elétricos

O chuveiro elétrico é apresentado como um equipamento de elevada potência instantânea.

O projeto utiliza como exemplo uma potência de aproximadamente **3500 W**, relacionando o tempo de utilização com o consumo de energia e o respetivo impacto financeiro.

---

## 📁 Estrutura do Projeto

Uma estrutura possível para o projeto é:

```text
projeto-qual-comprar/

│
├── index.html
├── style.css
├── imagens/
│   └── ...
└── README.md
```

---

## 💻 Como Executar Localmente

Como se trata de uma aplicação web estática, não é necessária qualquer instalação de dependências ou servidor backend.

### 1. Clonar o repositório

```bash
git clone <URL_DO_REPOSITORIO>
```

### 2. Aceder ao diretório

```bash
cd projeto-qual-comprar
```

### 3. Executar

Abra o ficheiro `index.html` diretamente num navegador moderno.

Como alternativa, pode utilizar a extensão **Live Server** no Visual Studio Code para executar o projeto através de um servidor local.

---

## 🎯 Objetivos de Aprendizagem

Este projeto foi desenvolvido com foco no aperfeiçoamento das seguintes competências:

- Estruturação de páginas com **HTML5 semântico**;
- Desenvolvimento de layouts com **CSS3**;
- Aplicação prática do **Box Model**;
- Organização de conteúdo editorial;
- Utilização de **tipografia web**;
- Estruturação acessível de imagens;
- Criação de layouts com largura de conteúdo controlada;
- Desenvolvimento de interfaces inspiradas em portais editoriais.

---

## 👨‍💻 Autor

**Rafael Santana** 🚀

_Estudante de Engenharia da Computação, com foco em Interfaces Web Estruturadas, Semântica de Código e Engenharia de Software._

---

## 📄 Licença

Este projeto foi desenvolvido para fins **educacionais e de portefólio**.

---

<p align="center">
  Projeto desenvolvido para fins educacionais e para consolidação de conhecimentos em HTML5, CSS3, CSS Grid, Flexbox e desenvolvimento de interfaces responsivas.
</p>
