# Test: Maker

Site de apresentação e ferramentas locais do projeto de recriação manuscrita.

## Recursos

- página inicial personalizada e responsiva;
- explicação do projeto e fluxo passo a passo;
- galeria das imagens de exemplo carregadas localmente em `assets/`;
- visualização ampliada das referências;
- função **Criar PDF da letra**;
- instrução para copiar os exemplos exatamente em folha pautada;
- seleção de imagens e pré-visualização do documento;
- scanner dentro do site;
- câmera do dispositivo quando o navegador permitir;
- envio da galeria ou computador;
- captura de múltiplas folhas;
- seleção e exclusão de páginas;
- rotação e ajustes de brilho e contraste;
- pré-visualização e download de PDF;
- processamento local no navegador.

## Instalação local

Não é necessário Node.js. Clone ou baixe o repositório e abra `index.html` em um navegador moderno. Para acesso à câmera, use HTTPS ou `localhost`; alguns navegadores bloqueiam câmera em arquivos `file://`.

A biblioteca jsPDF é carregada por CDN somente no momento do download. Para uso totalmente offline, baixe a biblioteca e altere o endereço em `app.js`.

## Imagens anexadas

As imagens de exemplo devem estar na pasta `assets/` com os nomes descritos em `assets/README.md`. O site não depende de links externos para a galeria.

## GitHub Pages

1. Abra **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`.
4. Salve.

URL esperada: `https://raphaellarroude.github.io/test-maker-site/`.

## Privacidade

As imagens permanecem no navegador durante o uso. O site não envia arquivos para um servidor próprio. Não publique referências pessoais sem autorização.

## Limitações conhecidas

A versão atual permite selecionar, excluir, girar e ajustar brilho/contraste. Recorte manual e correção automática de perspectiva podem exigir uma etapa adicional; o site informa a disponibilidade real em vez de simular essas funções.

## Licença

MIT.
