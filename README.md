# Marvin
Meu primeiro contato com programação aconteceu através de um curso introdutório fornecido pela [ONG Gerando Falcões](https://gerandofalcoes.com/), onde conheci o Projeto Marvin.

O foco principal era desenvolver lógica de programação utilizando a linguagem JavaScript.

Existem mais fases do projeto, mas como o curso chegou ao fim, não consegui encontrar mais informações sobre o projeto.

## O que é o projeto Marvin

> É um programa de introdução à programação para jovens entre 17 e 24 anos, com 2 encontros semanais.  
>
> Serão desenvolvidas as habilidadedes de self-learning(auto aprendizagem) e peer-to-peer learning(aprendizado em pares) a partir de conteúdos e atividades práticas de programação no formato de projetos individuais e em equipe.
> 
> O programa é focado na introdução aos principais conceitos e habilidades de programação, além do desenvolvimento de soft skills que podem garantir um diferencial competitivo no mercado.

**Fonte:**  https://naacao.com.br/projeto-marvin/

## Resumo das Fases

A partir da Fase 1, cada etapa introduz novos desafios utilizando os conhecimentos adquiridos na fase anterior, com o objetivo de reforçar e aumentar a complexidade do aprendizado.

**Fase 1 -** Primeiro contato, diferença entre `console.log` e `return`.

**Fase 2 -** Uso de métodos nativos para manipulação de strings, além de variáveis e parâmetros.

**Fase 3 -** Introdução às estruturas de controle, com foco em `if`, `else` e `else if`.

**Fase 4 -** Estruturas de repetição com `while`, combinadas com condicionais para aumentar a complexidade.

**Fase 5 -** Introdução e manipulação de arrays.

## **Guia de Instalação**

Se você quiser rodar o projeto, um caminho eficiente é usando o gerenciador de versões [asdf](https://asdf-vm.com/) para instalar o **Nodejs**.

### **Node.js**

Sigua os comandos abaixo para instalar e configurar o nodejs. Vou trazer um pequeno resumo sobre cada passo.

Primeiro, adicionar o plugin para poder instalar as versões do **Nodejs**

```
asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
```

Para instalar uma versão expecífica rode: `asdf install nodejs 22.5.1`. Aqui, usarei a versão mais recente: 

```
asdf install nodejs latest
```

Para configurar podemos usar `asdf global` para aplicar como versão padrão em todo o sistema, ou `asdf local` para aplicar apenas nesse projeto.

`asdf list` para listar todas as linguagens e versões instaladas.

```
asdf global nodejs 25.5.1
```

### **Como executar**

Agora com o **Node.js** instalado e configurado. Apenas precisamos rodar no terminal: `node file_name.js`

Voce tambem pode instalar a extensão do VS Code [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) e executar usando atalho do teclado.
