# Checklist de Acessibilidade - NutriKids

## Elementos Não Textuais

✅ **Todas as imagens têm um texto alternativo (alt)**  
Verificação: Sim, todas as imagens possuem um atributo "alt" adequado.  
Justificativa: Isso ajuda pessoas com deficiência visual a entenderem o conteúdo. Se for apenas decorativa, o "alt" deve estar vazio.

✅ **Os itens não textuais têm uma versão alternativa em texto**  
Verificação: Sim, estamos implementando isso.  
Justificativa: Elementos gráficos importantes precisam de descrições textuais para acessibilidade.

✅ **Não são usadas imagens que contêm blocos de texto**  
Verificação: Correto, não usamos imagens com textos embutidos.  
Justificativa: Isso melhora a responsividade e acessibilidade.


## Formulários

✅ **Todos os campos dos formulários têm uma `<label>` associada**  
Verificação: Sim, todos os campos possuem labels.  
Justificativa: Isso facilita o preenchimento para usuários de leitores de tela.

❌ **São usados `<fieldset>` e `<legend>` para agrupar os campos**  
Verificação: Ainda não implementado.  
Justificativa: Melhoraria a organização dos formulários.

✅ **O envio dos formulários é feito via `<input/button>`, e não por links/JavaScript**  
Verificação: Sim, o envio é feito corretamente.  
Justificativa: Isso evita problemas caso o JavaScript esteja desativado.

❌ **Os erros nos formulários são indicados junto ao campo correspondente**  
Verificação: Ainda não, mas será implementado em breve.  
Justificativa: Ajuda o usuário a entender onde precisa corrigir.


## Uso de Cor e Elementos Piscantes

✅ **Não é usada apenas a cor para transmitir informação**  
Verificação: Sim, e estamos melhorando isso.  
Justificativa: Pessoas com deficiência visual precisam de outros indicadores além da cor.

✅ **Não há elementos que piscam ou mudam de cor repetidamente**  
Verificação: Sim, não temos elementos piscantes.  
Justificativa: Isso evita desconforto ou crises epilépticas.


## Navegação

✅ **São fornecidos atalhos para saltar links repetitivos**  
Justificativa: Ajuda usuários de leitores de tela a acessar o conteúdo principal rapidamente.

✅ **O `<title>` das páginas é claro e relacionado ao conteúdo**  
Justificativa: Melhora a usabilidade e ajuda os mecanismos de busca.

✅ **O site é navegável usando apenas o teclado**  
Justificativa: Importante para quem não pode usar um mouse.


## Semântica e Legibilidade

✅ **O conteúdo está estruturado de forma semântica**  
Justificativa: Cabeçalhos e listas organizam o conteúdo para facilitar a leitura.

✅ **O idioma da página está indicado no HTML**  
Justificativa: Isso evita problemas na leitura por leitores de tela.

❌ **As tabelas têm headings `<th>` definidos**  
Verificação: Ainda não implementado.  
Justificativa: Melhora a acessibilidade para usuários de leitores de tela.

✅ **O site funciona com as imagens desativadas**  
Justificativa: O conteúdo continua acessível mesmo sem imagens.

✅ **O site é legível e navegável com o CSS desativado**  
Justificativa: Isso garante que a estrutura do site continue compreensível.

✅ **O site é legível aumentando o texto 2 vezes**  
Justificativa: Essencial para usuários com baixa visão.


