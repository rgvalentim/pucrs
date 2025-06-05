# pucrs
Trabalho da discuplina de Introdução a Sistemas Web

# Minimercado Web

## Descrição

Minimercado Web é um site estático simples que simula a presença online de um minimercado. Ele permite aos usuários visualizar diferentes categorias de produtos, seus preços e informações sobre serviços de entrega. O site é composto por 5 páginas HTML principais, cada uma focada em um aspecto do minimercado.

## Estrutura do Site e Páginas

O site é composto pelas seguintes páginas HTML:

1.  **`home.html`**:
    * Título da página: "Minimercado Home".
    * Serve como a página inicial do site.
    * Apresenta o título principal "Minimercado Web".
    * Exibe uma seleção de imagens de produtos que funcionam como links visuais para as respectivas seções do site (Alimentos, Frutas & Verduras, Higiene).

2.  **`alimentos.html`**:
    * Título da página: "Minimercado Serviços" (embora o conteúdo seja sobre alimentos).
    * Título da seção: "Minimercado Web - Alimentos".
    * Lista produtos alimentícios com seus preços:
        * Arroz parboelizado Urbano: R$ 5,00
        * Feijão Carioca Kicaldo: R$ 9,00

3.  **`frutas.html`**:
    * Título da página: "Minimercado Serviços" (embora o conteúdo seja sobre frutas e verduras).
    * Título da seção: "Minimercado Web - Frutas & Verduras".
    * Lista frutas e verduras com seus preços:
        * Chuchu: R$ 3,00/kg
        * Maçã nacional: R$ 4,00/kg

4.  **`higiene.html`**:
    * Título da página: "Minimercado Serviços" (embora o conteúdo seja sobre higiene e limpeza).
    * Título da seção: "Minimercado - Higiene & Limpeza".
    * Lista produtos de higiene e limpeza com seus preços:
        * Papel higiênico Delicatto Premium, 4 rolos: R$ 6,00
        * Sabonete Lux Botanicals 125g: R$ 3,00

5.  **`servicos.html`**:
    * Título da página: "Minimercado Serviços".
    * Título da seção: "Minimercado Web - Serviços".
    * Apresenta os serviços disponíveis:
        * Retirada Local: R$ 0,00
        * Tele-entrega: R$ 30,00
    * Inclui um formulário para preenchimento de dados de entrega, como nome do destinatário, endereço, telefone e ponto de referência. A instrução para preenchimento do endereço de entrega "em caso de retirada" pode necessitar de revisão para "em caso de tele-entrega" ou ser um formulário geral.

## Elementos Comuns

Todas as páginas compartilham uma estrutura de cabeçalho e rodapé consistente:

* **Cabeçalho (`<header>`):**
    * Exibe um logo do site (`logo.png`).
    * Apresenta o título da respectiva página/seção.
    * Contém um menu de navegação (`<nav>`) com links para todas as seções principais do site: Início, Frutas & Verduras, Alimentos, Higiene & Limpeza, e Serviços.
* **Rodapé (`<footer>`):**
    * Nome do minimercado: "Minimercado Web".
    * Descrição: "Oferecemos frutas, verduras, produtos alimentícios e de higiene com qualidade e economia para sua casa."
    * Informações de Contato:
        * Endereço: Rua das Flores, 123 - Centro
        * Telefone: (81) 99999-9999
        * Email: contato@minimercadoweb.com
    * Links úteis (repetição do menu de navegação).
    * Aviso de direitos autorais: "&copy; 2025 Minimercado Web. Todos os direitos reservados."

## Tecnologias Utilizadas

* HTML5

## Como Visualizar

Para visualizar o site, basta abrir qualquer um dos arquivos `.html` (preferencialmente `home.html` para começar) em um navegador web.

## Observações

* Os títulos (`<title>`) das páginas `alimentos.html`, `frutas.html` e `higiene.html` estão definidos como "Minimercado Serviços". Seria mais apropriado que refletissem o conteúdo específico da página (e.g., "Minimercado Alimentos").
* As imagens dos produtos (ex: `arroz.jpg`, `chuchu.jpg`) são referenciadas localmente e precisariam estar na mesma pasta que os arquivos HTML ou no caminho especificado para serem exibidas corretamente.
