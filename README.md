# Laboratório – Azure Speech Studio & Language Studio

O repositório contém os resultados da exploração prática de recursos de IA voltados para fala e linguagem natural das plataforma Azure Speech Studio e o Language Studio. O experimento simula um fluxo típico de desenvolvimento com IA Cognitiva da Microsoft, incluindo análise prática, documentação técnica e reflexões acadêmicas sobre o uso das ferramentas.

## Dados do Aluno
**Nome:** Marcio Salmazo Ramos \
**Redes sociais e contato:**

| [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcio-ramos-b94669235) | [![Instagram](https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/marcio.salmazo) | [![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:contato.marcio.salmazo19@gmail.com) | [![GitHub](https://img.shields.io/badge/GitHub-0077B5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Marcio-Salmazo) |
|---|---|---|---|

## Objetivos da atividade

* Familiarização com ferramentas cognitivas Microsoft Azure;
* Aplicação prática de IA em voz e linguagem;
* Documentação técnica e acadêmica;
* Desenvolvimento de visão crítica.

## Ferramentas utilizadas

* **Azure Speech Studio** para a transcrição de áudio e implementação do Text-to-Speech;
* **Azure Language Studio**	para a análise de texto e insights semânticos;
* **GitHub** para o registro e documentação do projeto.

## Atividades Realizadas

1. **Speech-to-Text (Reconhecimento de Fala):** 
Como entrada do sistema, é gravado um áudio curto em português, no contexto desta atividade o conteúdo falado foi: "Oi, este audio é um teste para a Inteligencia artificial da Microsoft". O resultado retornado pelo sistema pode ser observado na Figura 'transcrição.png', alocada no diretório ***\images*** deste repositório.

**Resultados e Discussões da atividade:**

* O reconhecimento de fala natural foi feito de maneira rápida e eficiente;
* A pontuação automática aplicada corretamente, mesmo que não tenha sido especificada;
* Foi apresentado um bom desempenho para o português brasileiro.

---

2. **Text-to-Speech (Síntese de Voz):** 
Como entrada do sistema, foi passada a seguinte frase em português: "Oi, está frase testa o recurso de sintese de voz com o Azure Speech Studio". O resultado retornado pelo sistema não pode ser plenamente ilustrado por imagens neste documento (uma vez que o retorno é sonoro), contudo, a página referente à esta atividade pode ser observada na Figura 'sintese.png', alocada no diretório ***\images*** deste repositório.

É importante ressaltar que a plataforma dispões de diferentes tipos de vozes, especificando-as quanto ao genero, idade e idioma falado. Além disso características específicas de personalidade e cenários são associadas ao timbre da voz selecionada(como 'Confiante', 'Otimista', dentre outros). Tais funcionalidades podem ser observadas na fingura 'vozes.png', também alocada no diretório ***\images*** deste repositório.

**Resultados e Discussões da atividade:**

* Percebe-se que a voz gerada pelo sistema possui entonação natural e cadência fluida, o que se mostra fundamental para aplicações de assistentes virtuais que visam a acessibilidade;
* A fala está devidamente ajustada para o idioma português.

---

3. **Tradução automática:** 
Como entrada do sistema, foi passada a seguinte frase em português: "Este é um teste para a tradução de fala da ferramenta de inteligência artificial da Microsoft". Espera-se que o sistema retorne a mesma frase traduzida para a linguagem selecionada (que neste caso foi o inglês). O resultado pode ser observada na Figura 'tradução.png', alocada no diretório ***\images*** deste repositório.


**Resultados e Discussões da atividade:**

* O sistema é ágil e eficiente para converter a fala em texto e traduzi-la;
* É notavel a otimização da tradução, tornando a o resultado mais coeso (percebe-se que há uma leve correção da entrada para se ajustar à escrita formal, quando possível).

---

4. **Análise de sentimentos na linguagem natural:** 
Como entrada do sistema, foi passada o seguinte trecho simulando uma avaliação de serviço: "O atendimento foi excelente, porém o tempo de espera precisa melhorar". Espera-se que o sistema retorne porcentagem de probabilidade entre as classes 'positivo' e 'negativo', indicando a tendencia de satisfação do cliente. O resultado da atividade pode ser observado na Figura 'sentimentos.png', alocada no diretório ***\images*** deste repositório.

**Resultados e Discussões da atividade:**

* A ferramente indica prevalência positiva de sentimento positivo;
* O sistema foi capaz de entender que mesmo com nuances expressivas que indicam satisfação, também há um sentimento negativo no contexto geral da frase;
* O sistema demonstra capacidade de equilibrar bem a intensidade de cada sentimento expresso no texto.

---

5. **Extração de Entidades e Expressões-Chave:** 
Como entrada do sistema, foi passada o seguinte trecho textual: "A Microsoft lançou novos recursos de IA em Uberlândia no dia 15 de março de 2024". Espera-se que o sistema retorne as principais entidades que fornecem a lógica semantica na frase, evidenciando as palvras que mais contribuem para o sentido geral. O resultado da atividade pode ser observado na Figura 'entidades.png', alocada no diretório ***\images*** deste repositório.

**Entidades identificadas:**

* *Microsoft* &rarr;
* *São Paulo* &rarr;
* *15 de março de 2024* &rarr;
* *IA / tecnologia* &rarr; 

**Resultados e Discussões da atividade:**

* A ferramente demonstra capacidade sólida de extrair os *tokens* que contribuem com maior expressividade para o sentido geral do texto apresentado;
* O sistema foi capaz de atribuir uma lógica do porquê da escolha dos *tokens* extraídos

---

## Reflexões e Considerações

As ferramentas Azure Speech Studio e Language Studio, do ponto de vista profissional, se mostram adequadas para o desenvolvimento de protótipos e até mesmo para a construção de soluções corporativas (desde de níveis básicos à avançados), especialmente em cenários de automação e atendimento ao cliente.

Contudo, é importante considerar algumas limitações, como a dependência de conexão com a internet, podendo impactar sua utilização em ambientes offline ou com restrições tecnológicas. Adicionalmente, tive uma experiência negativa com a plataforma da Microsoft, o que não reflete diretamente na robustez do Azure, mas preciso ser franco que algumas funcionalidades apresentaram bugs, afetando diretamente minha experiência pessoal.

A Microsoft, de modo geral, apresenta (ao meu ver) uma interface confusa, com funcionalidades escondidas, além de um processo lento e burocrático para login. Tais problemas desestimulam projetos explotórios voltados para o aprendizado por alunos e profissionais iniciantes, que desejam apenas ter uma familiaridade com o serviço


## Referências

**Materiais complementares fornecidos pelo curso:**
* Explore Speech Studio - Laboratório no Microsoft Learning
* Analyze text with Language Studio - Laboratório no Microsoft Learning
* Materiais Complementares sobre GitHub 
* ***url:*** https://web.dio.me/lab/analise-de-sentimentos-com-language-studio-no-azure-ai/learning/f6884c74-e7aa-4700-a84b-a3446e0b6d8d?back=/track/randstad-analise-de-dados
