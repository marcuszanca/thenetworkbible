# Network Bible — Guia Visual de Redes

Site estático em português, feito com HTML, CSS e JavaScript sem dependências de build. Inclui mapa de módulos, pesquisa global, páginas individuais para cada tópico, catálogo inicial de fabricantes/ferramentas/cursos, comandos, troubleshooting, glossário, trilhas e tema claro/escuro.

## Executar localmente
Abra `index.html` no navegador. Para um teste mais próximo da hospedagem, use um servidor estático local, por exemplo a extensão Live Server do VS Code.

## Publicar gratuitamente com GitHub Pages
1. Crie uma conta no GitHub, caso ainda não tenha.
2. Crie um repositório público chamado `network-bible`.
3. Envie todos os arquivos e pastas desta pasta para a raiz do repositório.
4. No repositório, abra **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**; selecione `main` e `/ (root)`; salve.
6. Aguarde a publicação. O endereço ficará semelhante a `https://SEU-USUARIO.github.io/network-bible/`.
7. Para um domínio próprio, registre o domínio e configure-o em **Settings → Pages → Custom domain**, seguindo as instruções atuais do GitHub.

Documentação oficial:
- https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Alternativa: Cloudflare Pages
1. Crie um projeto no Cloudflare Pages e conecte o repositório GitHub ou envie os arquivos estáticos.
2. Para domínio próprio, adicione o domínio em **Workers & Pages → seu projeto → Custom domains** e siga as instruções exibidas.
3. A configuração de domínio raiz exige gerenciamento da zona DNS no Cloudflare; para subdomínios, normalmente usa-se CNAME, conforme a documentação.
- https://developers.cloudflare.com/pages/

## Domínio econômico no Brasil
O Registro.br informa o valor de R$ 40/ano para domínios registrados diretamente por ele (preço sujeito a alterações). Antes de comprar, confira a disponibilidade do nome e o valor vigente.
- https://registro.br/dominio

Sugestões de nome para pesquisar (disponibilidade não verificada):
- networkatlas.com.br
- atlasderedes.com.br
- guiaderedes.com.br
- mapaderedes.com.br

## Antes de publicar
- Revise conteúdo e links externos.
- Confira se não há informações internas ou credenciais.
- Teste pesquisa, navegação móvel, tema claro/escuro e links diretos.
- Confirme o domínio exato disponível antes de comprar.
- O domínio é pago separadamente; hospedagem estática pode permanecer gratuita conforme limites e políticas do provedor.

## Limitações da primeira versão
- O conteúdo é uma base inicial e precisa ser expandido/revisado antes de ser tratado como guia exaustivo.
- Alguns tópicos são resumos de orientação; comandos e sintaxe dependem do fabricante/versão.
- O mapa é um protótipo funcional simples, não um editor de grafos.
- Não há conta de usuário, progresso sincronizado, painel editorial ou backend.


## Expansão desta revisão
- Cada tópico de módulo recebe um identificador e uma página independente, acessível por hash direto.
- Clique em um módulo para abrir seus conceitos em cartões; clique em um cartão para abrir o artigo.
- Catálogo inicial organizado por Access Points, switches, roteadores/WAN, segurança, fibra/transceptores, monitoramento, cursos e padrões.
- Referências específicas por tópico quando existe uma fonte primária identificada; links de fabricantes levam aos portais oficiais.
- Os artigos gerados incluem orientação geral, exemplo de laboratório, validação, troubleshooting e segurança. Revise comandos e detalhes de cada fabricante/versão antes de uso operacional.


## Expansão enciclopédica
Esta versão inclui artigos individuais adicionais para Wi‑Fi (planejamento, bandas, canais, gerações, segurança, RSSI/SNR), Ethernet/ARP, VLANs, roteamento, DNS/DHCP, fibra/SFP, segurança, monitoramento e troubleshooting. As referências estão dentro dos próprios artigos. Conteúdo educacional: confirme sempre normas brasileiras, firmware, modelo e documentação do fabricante antes de alterar redes em produção.
