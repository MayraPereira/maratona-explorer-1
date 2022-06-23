# HTML
- HyperText Markup Language
- Hiper Texto: links que podemos colocar no texto
- Marcação: tags, atributos (dar mais informação)
- Linguagem: maneira de escrever

# CSS
- Apresentação visual para o cliente
- Estilos para o HTML (estrutura da página)
- Modificar os textos, colocar cor, etc.

- CSS: Cascading Style Sheets (folha de estilo em cascata)
- Declaração:
    - Seletor: nome, poder ser nome da tag
    - Propriedade e valor: dentro coloca propriedade e valor
- Cascata:
    - Folha de estiloÇ arquivo em que coloca estilos
    - Cascata vai considerar o último que colocar, declaração por declaração.
    - Especificidade (como que estou colando os seletores)
        - Seletor de tag possui peso (0,0,1)
        - Mas pode-se usar o "id". Um atributo HTML que é um identificador único.
    - ESPECIFICIDADE FALA MAIS ALTO QUE A CASCATA

- Box-model
    - Tudo são caixas (todas as tags)
    - A caixas possuem propriedades
        - Margin: espaços ao redor de uma caixa
        - Border: borda de uma caixa, pode ser maior
        - Padding: preenchimento
            Content (toda caixa tem conteúdo)
                Altura: height
                Largura: width

- Seletor universal (*)
    - Reset
    - Pega todos os elementos

- Display block x inline
    - Block: elemento anterior e outro próximo (linhas diferentes)
    - Inline: elemento um ao lado do outro

# JavaScript
- Linguagem de programação interpretada e executada pelos navegadores
- É a inteligência da tríade
    - HTML: estrutura / css: beleza / JS: inteligência
-Sintaxe
    - Está presente em toda linguagem e é importante para a comunicação. Maneira correta de colocar as informações.

1. Variáveis: aloca espaço na memõria e atribui um valor
    let: pode alterar o valor a qualquer momento (let change)
    const: não pode alterar, é uma variável constante

2. Tipos de dados
    String: cadeia de caracteres
    Numbers: números. Podem ser inteiros (integer) ou flutuantes (float)
    Boolean: true ou false. Mais utilizado em condições.
    Undefined: indefinido. Não existe.

3. Operadores
    Atribuição de valor (=)
    Aritméticos (* / + -)
        Cálculos matemáticos simples. Tenta transformar os dois lados em números, exceto o "+".
    Concatenação de valores (+)
    Comparação (> < ==)

5. Condicional (if/else)

5. Estrutura de dados
    Array = Lista = Vetor
    Qualquer tipo de valor. Acessa posição pelos índices

    Object (propriedade e valor)

6. Function (função)
    Vantagem: executar um bloco de código mais de uma vez, várias vezes. Reuso.

7. Extensões da linguagem (Math, Date..)
    Dentro da linguagem traz outras ferramentas (de conta, de data, etc)

8. DOM - Document Object Model
    Modelagem do documento em objeto
    Transforma tudo em objeto, inclusive a janela do navegador

### imagem bola de cristal
https://gist.githubusercontent.com/maykbrito/0acdf4ce919838ffed50915a31fc5b23/raw/6f4dd01ec3116428ec4c99255944cb9ac7927590/cristal-ball.svg