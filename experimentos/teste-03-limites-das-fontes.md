# 🧪 Experimento 3 — Limites das Fontes

## Objetivo

Avaliar como o NotebookLM se comporta quando recebe uma solicitação que exige informações quantitativas específicas que não estão completamente disponíveis nas fontes utilizadas no projeto.

---

## Prompt 3 — Restritivo

> Utilizando exclusivamente as fontes disponíveis neste caderno, apresente três casos reais de empresas industriais brasileiras que obtiveram ganhos financeiros por meio da utilização de Inteligência Artificial.
>
> Para cada caso, informe:
>
> 1. Nome da empresa;
> 2. Aplicação da Inteligência Artificial;
> 3. Percentual de ganho financeiro;
> 4. Valor financeiro obtido;
> 5. Período analisado;
> 6. Fonte exata.
>
> Não faça estimativas.
>
> Não invente dados.
>
> Não utilize informações externas.
>
> Caso as fontes não contenham essas informações, informe explicitamente que os dados são insuficientes para responder.

---

## Resultado observado

O NotebookLM identificou que as fontes disponíveis eram insuficientes para apresentar três casos que atendessem integralmente a todos os critérios solicitados.

Em vez de completar as informações com estimativas, o modelo indicou a limitação da base documental.

Entre as evidências aproximadas encontradas nas fontes estavam:

- **Tractian:** referência a uma captação de R$ 700 milhões em 2024, deixando claro que o valor correspondia a investimento captado pela empresa e não a ganho financeiro obtido por um cliente industrial.
- **Estudo de caso de uma multinacional paulista:** o material analisava riscos em um projeto industrial, porém o nome da empresa foi omitido no estudo por questões de sigilo.

Essas informações não eram suficientes para atender integralmente ao que havia sido solicitado no prompt.

---

## Cicatriz identificada

Quando uma solicitação exige informações que não estão presentes na base documental, existe o risco de uma IA tentar preencher as lacunas com informações plausíveis.

A inclusão de instruções explícitas como:

> "Não faça estimativas."

> "Não invente dados."

> "Não utilize informações externas."

> "Caso as fontes não contenham essas informações, informe explicitamente que os dados são insuficientes."

funcionou como uma barreira de segurança para limitar a resposta ao conteúdo efetivamente disponível.

---

## Aprendizado

Um bom prompt também deve definir claramente **o que a IA não deve fazer**.

Neste experimento, as restrições negativas foram importantes para testar os limites das fontes e preservar a integridade das informações utilizadas no projeto.

A capacidade de reconhecer que uma base documental é insuficiente também faz parte do uso responsável da Inteligência Artificial.
