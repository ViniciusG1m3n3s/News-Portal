# News Portal

Portal de notícias desenvolvido durante o curso de Desenvolvedor Fullstack da Rocketseat, focando no aprendizado de CSS Grid Layout.

## 📚 Aprendizados Principais

### Grid Layout

O CSS Grid Layout é um sistema bidimensional de layout que oferece grande controle sobre a estruturação de páginas web. Neste projeto, exploramos diversos conceitos importantes:

#### 1. Containers Grid Básicos

```css
.grid {
  display: grid;
}
```
Este é o comando fundamental para criar um container grid. Ele transforma um elemento em um grid container, permitindo que seus filhos sejam organizados em linhas e colunas.

#### 2. Fluxo de Colunas

```css
.grid-flow-col {
  grid-auto-flow: column;
}
```
Esta propriedade define a direção do fluxo dos elementos dentro do grid. No nosso caso, `column` faz com que os elementos se organizem horizontalmente.

#### 3. Definição de Colunas

```css
.grid-cols-2 {
  grid-template-columns: repeat(2, 1fr);
}
```
Esta propriedade cria um grid com duas colunas de tamanhos iguais. O `1fr` representa uma fração do espaço disponível.

#### 4. Espaçamento entre Elementos

```css
.gap-16 {
  gap: 16px;
}

.gap-32 {
  gap: 32px;
}
```
A propriedade `gap` define o espaçamento entre os elementos do grid, tanto vertical quanto horizontalmente.


## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3 (Grid Layout)
- CSS Variables

## 📖 Conceitos Aplicados

- Grid Layout
- Nomenclatura consistente de classes
- Organização modular de CSS
- Variáveis CSS para manutenção facilitada
- Acessibilidade com estrutura semântica

## 🔍 Como Utilizar

1. Clone o repositório
2. Abra o arquivo `index.html` em seu navegador
3. Explore o código-fonte para entender a implementação

## 🎨 Estrutura do Projeto

```
news-portal/
├── styles/
│   ├── global.css
│   ├── header.css
│   ├── sections.css
│   ├── utility.css
│   └── index.css
├── assets/
│   ├── images/
│   └── icons/
└── index.html
```
