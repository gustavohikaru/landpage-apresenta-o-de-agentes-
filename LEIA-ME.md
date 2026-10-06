# Superagentes

Landing page estática em português, com visual cyberpunk e as quatro imagens fornecidas em `Imagem/Super agentes imagem`.

Abra `index.html`, na raiz desta pasta, no navegador. HTML, CSS e JavaScript não precisam de instalação nem de compilação. A tipografia usa Google Fonts e alternativas locais quando não houver conexão.

## Conteúdo e funcionamento

- Seis agentes: Lume, Lucila, Joyce, Mentor Jobs, Mentor Bezos e Agente X.
- Detalhes de especialidades, exemplos de entregas e pedidos iniciais editáveis.
- Botão para copiar pedido, com seleção manual quando a área de transferência não estiver disponível.
- Navegação interna e perguntas frequentes.
- Layout responsivo e suporte a movimento reduzido.

Os retratos e imagens compõem o universo visual, sem representar identidades reais dos agentes. Lucila aparece como MOVA no título da nota original; esta página usa o nome da identidade e do arquivo.

Não há chat conectado, integração com sistemas corporativos, formulário ou contato comercial. Os pedidos são copiados para utilização com as instruções dos agentes em uma ferramenta de IA. Não foram incluídos preços nem depoimentos.

## Estrutura do site estático

```text
superagentes/
├── index.html
├── styles.css
├── script.js
└── assets/
```

Para hospedagem estática, envie `index.html`, `styles.css`, `script.js` e a pasta `assets/` juntos para a pasta pública da hospedagem. O `index.html` é a página inicial. Os caminhos são relativos e funcionam também em subpastas.

A pasta `dist/` mantém a cópia usada pela configuração existente do Sites. Para publicar futuras alterações nessa configuração, copie os arquivos da raiz e `assets/` para `dist/` antes da publicação. Esta reorganização entrega os arquivos locais; não altera a versão publicada.
