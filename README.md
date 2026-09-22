# 🎸 Automação N8N: Notícias de Rock e Metal no Telegram

Prompt estruturado para planejamento de automação no N8N a partir de feeds RSS, desenvolvido para o **Desafio Criativo da DIO**.

---

Atue como um especialista em N8N.

Crie uma automação para receber Notícias e matérias mais recentes de Rock e Metal do site Whiplash.Net no Grupo do Telegram.

Público:
Entusiastas de estilo de Rock e Metal.

Ferramentas envolvidas:
Schedule Trigger (Gatilho de Agendamento), RSS Read (Leitor de Feed), Filter (Filtro por Data e/ou Bandas), Code (JavaScript nativo para Formatação), Telegram (Envio).

Fluxo:
1. Schedule Trigger configurado para disparar diariamente às 09:00 AM.
2. RSS Read para coletar os artigos mais recentes do feed do Whiplash.Net.
3. Filter para manter apenas notícias com bandas de interesse e publicadas nas últimas 24 horas.
4. Code (JavaScript nativo) para concatenar e agrupar todas as notícias filtradas em uma única mensagem (HTML ou Markdown), evitando envios individuais para cada matéria.
5. Telegram para enviar a mensagem consolidada ao grupo.

Regras:
- Não enviar notícias antigas (considerar apenas itens publicados nas últimas 24 horas).
- Se não houver notícias que atendam aos filtros no dia, não enviar mensagem vazia.
- Tratar caracteres especiais para evitar erros de formatação no Telegram.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.
