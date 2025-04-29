# Atividade: Teste unitário #
O trabalho baseia-se na geração de código de teste unitário por uma LLM, a partir de um documento de Casos de Uso. Será utilizado um Caso de Uso. A fim de gerar o código de teste unitário, gera-se requisitos de todos os Caso de Uso. Em seguida, gera-se Casos de Teste de todos os requisitos. Depois, gera-se código de teste unitário do Caso De Teste escolhido.

O documento de Casos de Uso é de um projeto web chamado "SuperFrog Scheduler". SuperFrog é o mascote da Universidade Cristã de Texas, e tem participação em vários eventos anualmente, como esportes, mídia e caridades. O projeto tem a função de facilitar o agendamento e administração dos aparecimentos dos alunos que participam como SuperFrog.

O Caso de Uso que será analisado neste trabalho será o Caso de Uso 18: The Spirit Director generates TCU Honorarium (Payment for services) Request Forms.

## Instruções ##
O trabalho consiste em escrever teste unitário para 1 caso de teste escolhido por mim, usando a biblioteca pytest. Será providenciado o documento de Casos de Uso e todos os artefatos gerados (requisitos e casos de teste). Também deverá ser entregue código de teste unitário gerado por LLM para cada caso de teste. Logo, deverá ser feito:
* Código de teste unitário escrito manualmente 
* Codigo de teste unitário gerado por LLM

O código de teste deve passar na execução do pytest.

**Vou saber identificar se os dois códigos são escritos por LLM. Não tente a sorte!**

O Caso de Teste escolhido é o **Caso de Teste 2**.

### Instalando e rodando o pytest ###
Caso não tenha o python instalado, baixe o executável do site. Depois da instalação, baixe o pytest usando `pip install pytest` no terminal ou no terminal do VSCode (ou outra ferramenta de sua escolha).

Para rodar o código de teste, use `pytest nome_do_arquivo.py`. O código de teste precisa da implementação do código principal para que rode. Este código pode ser puramente para o teste passe, e não precisa ser uma implementação real do Caso de Teste. **O código deve passar no teste.**


## A pesquisa ##
A pesquisa em que esta atividade está incluída tem o objetivo de tirar conclusões de código de teste unitário escrito por LLM e por humanos e fazer uma análise qualitativa. Esta primeira etapa consiste da produção do código de teste unitário humano. As próximas etapas envolverão a permutação dos códigos dos alunos, e um questionário para fins de pesquisa. Para isso, é **essencial que o código escrito seja escrito manualmente**, para que os dados obtidos sejam relevantes para a condução da pesquisa.