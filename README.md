# Desafio_dio_Azure
 Análise de Sentimentos com Language Studio no Azure AI

✅ EXEMPLO 1 – Azure Speech Studio
🎙️ Cenário: Transcrever uma Reunião Gravada (áudio em português)
🔧 Passo a Passo:
Acesse: https://speech.microsoft.com/

Faça login com sua conta Microsoft/Azure.

No menu lateral, selecione Speech-to-text > Custom Speech > Audio Files.

Clique em Upload audio, selecione seu arquivo .wav ou .mp3.

Escolha o idioma: Português (Brasil).

Clique em Transcribe.

📸 Print Simulado:

less
Copiar
Editar
[SPEECH STUDIO DASHBOARD]
+-------------------------------------------+
| Upload de Áudio: [✔] reunião-21julho.mp3  |
| Idioma selecionado: Português (Brasil)    |
| Status: Transcrição concluída             |
| Texto gerado:                             |
| “Bom dia a todos, vamos iniciar a reunião|
| sobre o novo projeto de integração de IA…”|
+-------------------------------------------+
[🔽 Baixar transcrição .txt] [🔁 Nova transcrição]
🟢 Resultado: Arquivo de texto com o conteúdo falado da reunião, pronto para edição, envio ou indexação.

✅ EXEMPLO 2 – Azure Language Studio
📄 Cenário: Detectar sentimento de avaliações de usuários
🔧 Passo a Passo:
Acesse: https://language.azure.com/

Faça login com sua conta Microsoft/Azure.

No menu, selecione Análise de Texto > Sentiment Analysis.

Insira ou cole o texto da avaliação:

css
Copiar
Editar
“Achei o atendimento excelente, mas a entrega demorou demais.”
Clique em Analyze.

📸 Print Simulado:

less
Copiar
Editar
[LANGUAGE STUDIO – ANÁLISE DE SENTIMENTO]
+----------------------------------------------------+
| Texto: “Achei o atendimento excelente, mas a entrega|
| demorou demais.”                                   |
|                                                    |
| Resultado:                                          |
| - Sentimento geral: NEUTRO                         |
| - Sentimento por sentença:                         |
|   * “Achei o atendimento excelente” → POSITIVO     |
|   * “...mas a entrega demorou demais.” → NEGATIVO  |
+----------------------------------------------------+
[🔁 Analisar novo texto]  [📊 Ver análise completa JSON]
🟢 Resultado: Visão detalhada da opinião do cliente por partes, útil para decisões em SAC, produto ou marketing.
