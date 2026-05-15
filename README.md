# Sistema de Operações Leapy

Documentação viva da operação Leapy — três macrossistemas (Atração & Contratação, Desenvolvimento, Suporte) com fluxos detalhados e links para a documentação no Notion.

## Como abrir

Acesse `index.html` em qualquer navegador. O conteúdo é estático (HTML + CSS + JS), não precisa de servidor.

## Atualização

Edite `index.html` direto. Mudanças mais comuns:
- **Adicionar/remover etapas:** procure os blocos `<div class="step ...">` e duplique/edite
- **Mudar status (farol):** troque a classe `green`, `amber`, `red`, `gap` no `<div class="step ...">`
- **Atualizar links Notion:** procure por `notion.so/leapyedtech` e substitua o ID
- **Editar tooltip:** atributos `data-tip-title`, `data-tip`, `data-tip-tag` no elemento

## Estrutura

- `index.html` — site completo (HTML, CSS e JS em um único arquivo)
- `README.md` — este arquivo

## Manutenção

Responsável atual: Lucas Moraes (lucas.moraes@leapy.com.br)

Para sugestões ou correções, abra uma issue ou edite direto via Pull Request.
