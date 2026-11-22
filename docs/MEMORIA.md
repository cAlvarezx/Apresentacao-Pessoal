# Memória do projeto — página inicial

Decisões acordadas em 22/11/2026:

- A página inicial conecta as apresentações dos seis integrantes: Arthur, Cauê, João, Mariana, Osmar e Raphael.
- Manter HTML e CSS, visual escuro com lilás e comentários indicando onde personalizar textos, fotos, cores e links.
- Manter espaços para a foto do grupo e para as fotos individuais que ainda faltam.
- As fotos dos integrantes ficam quadradas (1:1), preenchendo o quadro, sem faixas laterais, sem padding interno e sem zoom ao passar o mouse. Evitar o recorte horizontal anterior, que aproximava demais os rostos.
- Remover a seção visível de conteúdos e seus oito tópicos, conforme a revisão solicitada. O pedido inicial exigia os oito conceitos no trabalho; seus exemplos técnicos continuam nos comentários e na implementação do index.
- A mensagem final celebra o ano vivido em conjunto e lembra que no próximo ano os integrantes vão trocar de sala: “Ano que vem, outra sala. As lembranças ficam.”
- Cauê e Osmar têm apresentações existentes. As páginas de João, Mariana e Raphael são provisórias, aguardando o conteúdo de cada integrante. Arthur tem uma cópia independente do modelo do Cauê em arthur/arthur.html, arthur/arthur.css e arthur/assets, com comentários para personalização; as fotos e os conteúdos herdados ainda precisam ser substituídos pelos dele.
- Conferir os nomes completos de Mariana e Raphael, pois aparecem cortados na referência enviada.
- Bootstrap está salvo localmente e organiza a grade da mensagem final.

Arquivos principais: index.html e style.css. Cada apresentação existente mantém seu próprio CSS.

Branch solicitada: feat/inicio.

- A página do Arthur usa a paleta azul elétrico: fundo #080F20, destaque #60A5FA e cards #121E36. As variáveis em arthur/arthur.css têm nomes das cores, como --azul e --azul-noturno; as cores das seções também estão centralizadas no :root.
