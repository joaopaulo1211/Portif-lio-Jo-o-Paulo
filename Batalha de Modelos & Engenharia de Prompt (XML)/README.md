⚔️ Batalha de Modelos & Engenharia de Prompt (XML)
📝 Descrição do Projeto
Este projeto consiste em uma análise comparativa entre diferentes modelos de inteligência artificial utilizando um prompt estruturado em XML. O objetivo principal foi construir um prompt capaz de gerar uma página HTML Single Page com CSS integrado e testá-lo em múltiplas ferramentas de IA, avaliando precisão, criatividade, erros e consumo de tokens.
Desenvolvido como parte da disciplina de Engenharia de Prompt e Aplicações em IA, o experimento submeteu o mesmo prompt XML a sete modelos (ChatGPT, Gemini, Claude, Qwen, DeepSeek, Grok e Maritaca) e documentou os resultados em um quadro comparativo com reflexão crítica.
Figura 1: Prompt XML estruturado utilizado como entrada para todos os modelos avaliados.
🚀 Tecnologias Utilizadas

Linguagem: HTML5 + CSS3 (Single Page gerada pelos modelos)
Metodologia: Engenharia de Prompt com estrutura XML
Ferramentas testadas: ChatGPT, Gemini, DeepSeek, Qwen, Grok, Maritaca, Claude

📊 Resultados e Aprendizados
O experimento revelou diferenças significativas entre os modelos em todos os critérios avaliados.

Melhor desempenho geral: Claude — superou as expectativas em precisão, completude do HTML e criatividade, gerando o site mais completo e informativo, com 27.000 tokens.
Maior consumo de tokens: Claude (27.000) contra uma média de 1.100 a 4.820 dos demais modelos, evidenciando verbosidade significativamente superior.
Pior desempenho: Grok — apresentou o menor nível de conteúdo e criatividade entre todos os modelos testados.

ModeloPrecisão do PromptPrecisão HTMLCriatividadeTokensChatGPTBaixaBaixoAbaixo do esperado1.250–1.400GeminiMédiaMédiaBaixa1.450DeepSeekMédiaMédiaBaixa2.850QwenBaixaBaixoAbaixo do esperado1.800–2.200GrokBaixaBaixoMuito baixa4.820MaritacaBaixaBaixoAbaixo do esperado1.100ClaudeAltaAltaAlta27.000
Figura 2: Quadro comparativo completo dos critérios de avaliação entre os modelos.
🔧 Como Executar

Clone o repositório.
Abra o arquivo prompt.xml em qualquer editor de texto.
Cole o prompt em qualquer ferramenta de IA e analise o resultado gerado.

Figura 3: Fluxo do experimento — prompt XML → modelo de IA → página HTML gerada → análise comparativa.
