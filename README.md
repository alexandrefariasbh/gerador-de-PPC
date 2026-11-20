# Gerador de Projeto Pedagógico dos Cursos Técnicos

Este é um gerador de Projeto Pedagógico de Curso (PPC) para os cursos técnicos da Educação Profissional Técnica de Nível Médio (EPTNM) da Universidade Federal de Ciência e Inovação de Minas Gerais (UFCIMG), o antigo CEFET-MG.

A ideia deste gerador é que as coordenações de curso produzam PPCs institucionais padronizados, todos no mesmo formato: as mesmas tabelas, carga horária dentro das normas, ementas coerentes com os programas e referências em ABNT. O coordenador de curso preenche o conteúdo, e o documento sai pronto, no padrão institucional.

**Acesse:** https://alexandrefariasbh.github.io/gerador-de-PPC/

## Como funciona

O gerador abre direto no navegador, sem instalar nada e sem login. Funciona no computador, no notebook e no tablet, com Chrome, Edge, Safari ou Firefox.

Ao abrir, ele começa em branco, só com as disciplinas da formação geral já preenchidas, porque elas são padronizadas para todos os cursos. Você segue as etapas do menu lateral:

1. **Identificação e capa:** curso, campus, forma de oferta, histórico e comissão proponente.
2. **Textos do projeto:** apresentação, justificativa, objetivos, perfil profissional e as demais seções.
3. **Matriz curricular:** as disciplinas da parte específica e a carga horária de cada uma.
4. **Ementário e programas:** ementa, objetivos, conteúdo, metodologia e bibliografia de cada disciplina.
5. **Instalações e laboratórios:** ambientes, laboratórios com seus equipamentos e acervo bibliográfico.
6. **Corpo docente:** o professor responsável por cada disciplina e o corpo técnico.
7. **Pendências:** a conferência automática de todo o projeto.
8. **Gerar documentos:** o PPC pronto em Word ou PDF, e as tabelas em Excel.

Enquanto você preenche, o gerador confere tudo contra o documento orientador, a Resolução CEPE nº 15/2022 e o check list de análise da comissão. Ele avisa, por exemplo, quando a carga horária da parte específica não atinge o mínimo do curso, quando uma série passa do limite semanal, quando falta uma unidade no programa ou quando uma referência está fora da ABNT. Cada aviso tem um atalho que leva direto ao campo a ser corrigido. Os números vermelhos no menu mostram quantas pendências ainda faltam em cada etapa.

## O que o gerador entrega

- **PPC completo**, no padrão institucional, em arquivo PDF ou .docx: capa, folha de rosto, sumário, ficha de identificação, matriz curricular, ementário, programas, laboratórios, acervo e corpo docente.
- **PPC completo – Novo Layout**, uma proposta de visual mais moderno para o mesmo conteúdo, em arquivo PDF ou .docx, para avaliação como novo padrão.
- **Tabelas em Excel**, para a comissão conferir a matriz e os demais quadros.

## Reestruturar um PPC a partir do anterior

Para reestruturar um curso, você não precisa começar do zero. Clique em **Importar PPC** e escolha o PPC vigente do curso, em PDF ou Word. O gerador lê o documento e aproveita o que já existe: textos do projeto, disciplinas e cargas horárias da matriz, ementas, programas com objetivos, unidades e bibliografias, laboratórios, acervo e corpo docente. Antes de confirmar, ele mostra um resumo do que conseguiu ler.

A partir daí, você edita apenas o que muda na nova versão. A matriz lida fica registrada como **matriz vigente**, e a matriz que você editar passa a ser a **matriz proposta**. No PPC gerado aparecem as duas, seguidas de um **quadro comparativo** com as disciplinas incluídas, excluídas e alteradas, com a carga horária antes e depois. Assim a comissão vê de imediato o que mudou.

O PDF precisa ter texto. Um PDF digitalizado (imagem escaneada) não pode ser lido; nesse caso, use o arquivo do Word ou o PDF gerado a partir dele.

## Novas funcionalidades

- **Importar PPC:** lê um PPC em PDF ou Word, preenche o gerador e permite gerar a versão reestruturada, como descrito acima.
- **A partir de PPC existente:** em **Novo**, você pode abrir o PPC do Curso Técnico em Eletrotécnica para se orientar, e então editá-lo e adaptá-lo ao seu curso. Ele vem sem nomes de pessoas: docentes, técnicos, proponentes e equipes elaboradoras ficam para você preencher.
- **PPC completo em PDF:** além do arquivo .docx, o PPC sai em PDF, no padrão institucional, sem precisar do Word.
- **PPC completo – Novo Layout:** uma proposta de visual mais moderno, com capa em destaque, indicadores do curso e tabelas mais limpas, em PDF ou .docx, para avaliação como novo padrão.
- **Prévia do PPC:** mostra o documento sendo montado ao lado do formulário, atualizado enquanto você digita.
- **Pendências:** a conferência automática lista o que falta ou está fora das normas, e cada item leva direto ao campo a ser corrigido.
- **Ementa da formação geral:** na matriz curricular, ao passar o mouse sobre uma disciplina da formação geral, aparece a ementa dela.
- **Normas e documentos:** reúne as Orientações para elaboração de PPC (que também podem ser lidas dentro do gerador), o Quadro 1, o check list de análise, o procedimento de encaminhamento e os links da legislação.
- **Sobre este gerador:** este texto, com o passo a passo de uso.
- **Compartilhar o gerador de PPC:** copia o link do gerador para enviar a colegas por WhatsApp, e-mail ou outro aplicativo.

## Onde ficam os dados

Tudo o que você digita fica salvo apenas no seu navegador. Nada é enviado para servidores. Por isso:

- para continuar em outro computador, ou passar o projeto a um colega, use **Salvar**. Ele gera um arquivo no seu computador, que depois pode ser aberto em **Abrir**;
- se você limpar os dados do navegador, o rascunho se perde, então salve o projeto com frequência;
- ao reabrir o gerador, ele começa em branco e oferece **Continuar rascunho** caso haja trabalho anterior salvo naquele navegador.

## Versão

A versão aparece no topo da tela, ao lado do título. Quando o gerador for atualizado, a versão muda. Se alguém relatar um problema, vale conferir primeiro se está usando a versão mais recente. Se o navegador continuar mostrando uma versão antiga, recarregue a página (Ctrl+Shift+R no Windows, Cmd+Shift+R no Mac).

## Arquivos deste repositório

- **`index.html`**: o gerador completo, em um único arquivo. É o que o GitHub Pages publica no link acima.
- **`README.md`**: este texto.

O `index.html` também funciona sozinho: baixe o arquivo e abra com dois cliques, mesmo sem internet.

## Sugestões e problemas

Sugestões, correções e relatos de problemas são bem-vindos. Abra uma *issue* aqui no GitHub ou fale diretamente com o autor.

## Autoria

Desenvolvido pelo Prof. Alexandre Rodrigues Farias, do Departamento de Eletrônica e Biomédica da UFCIMG.

LinkedIn: https://www.linkedin.com/in/alexandre-rodrigues-farias
