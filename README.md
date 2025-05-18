
![Template rluipdev](rluispdev(2).png)
# Sistema de Criação de Posts para Instagram com Agentes

Este projeto implementa um sistema de criação de posts para Instagram utilizando múltiplos agentes baseados em modelos de linguagem, com foco em gerar conteúdo sobre novidades e tendências de um determinado tópico. O sistema automatiza as etapas de busca de informações, planejamento do conteúdo, redação do post e revisão.

## Tabela de Conteúdo

- [Visão Geral](#visão-geral)
- [Recursos](#recursos)
- [Arquitetura](#arquitetura)
- [Configuração](#configuração)
- [Uso](#uso)
- [Agentes](#agentes)
- [Dependências](#dependências)

## Visão Geral

O projeto utiliza a biblioteca Google ADK (Agent Development Kit) para criar uma cadeia de agentes que colaboram para gerar um post de Instagram. Dado um tópico inicial, o sistema busca as últimas notícias, planeja o conteúdo do post com base nos achados, escreve um rascunho e, finalmente, revisa o texto para garantir a qualidade e o tom adequado para o público do Instagram.

## Recursos

- **Busca Automatizada de Notícias:** Encontra as últimas notícias e lançamentos relevantes sobre um tópico específico.
- **Planejamento de Conteúdo:** Analisa as notícias e identifica os pontos mais importantes para incluir no post.
- **Redação de Rascunhos:** Gera um rascunho de post para Instagram com base no planejamento.
- **Revisão de Qualidade:** Revisa o rascunho do post para garantir clareza, correção e tom adequado.
- **Arquitetura Modular:** Utiliza uma cadeia de agentes, permitindo a fácil expansão e modificação do fluxo de trabalho.

## Arquitetura

O sistema é composto por uma sequência de quatro agentes, cada um com uma função específica:

1.  **Agente Buscador de Notícias Global:** Responsável por buscar notícias relevantes usando a ferramenta Google Search.
2.  **Agente Planejador de Posts:** Analisa os resultados da busca e planeja o conteúdo do post, identificando pontos importantes.
3.  **Agente Redator do Post:** Escreve um rascunho de post para Instagram com base no plano fornecido.
4.  **Agente Revisor de Qualidade:** Revisa o rascunho do post, verificando a qualidade e adequação para o público-alvo.

## Configuração

Para executar este projeto, você precisa configurar o ambiente e fornecer sua chave de API do Google.

1.  **Instale as Dependências:** Certifique-se de ter o Python instalado. Instale as bibliotecas necessárias executando os comandos `pip install` no seu ambiente (como no seu notebook Colab).
2.  **Configure a Chave de API:** Obtenha uma chave de API do Google Gemini. No Google Colab, você pode armazenar sua chave usando o serviço `userdata.get('GOOGLE_API_KEY')`. Certifique-se de que a variável de ambiente `GOOGLE_API_KEY` esteja definida com sua chave.

## Uso

1.  **Execute o Código:** Execute o código no seu ambiente Python ou notebook Jupyter/Colab.
2.  **Forneça o Tópico:** O programa irá solicitar que você digite o tópico sobre o qual deseja criar o post.
3.  **Aguarde a Execução:** O sistema irá executar a cadeia de agentes automaticamente.
4.  **Visualize o Resultado:** O post revisado será exibido no final da execução.

## Agentes

Detalhes sobre cada agente e suas instruções podem ser encontrados no código-fonte. Cada agente possui uma instrução específica que define seu papel e comportamento.

## Dependências

As principais dependências deste projeto incluem:

- `google-genai`
- `google-adk`
- `IPython`
- `requests`
- `datetime`

Essas dependências são instaladas no início do seu código, garantindo que o ambiente esteja pronto para a execução dos agentes.

---

## Agradecimentos

- Alura e o evento "Imersão IA Gemini 3" pela inspiração e orientação.
- Google pela API Gemini.

  ## 👨‍💻 rluispdev
<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://avatars.githubusercontent.com/u/128305083?s=96&v=4"
    />
    <p>
     <a href="https://rluispdev.github.io/portifolio/" target="_blank"> Portifólio</a>
&nbsp;|&nbsp;
    <a href="https://github.com/rluispdev" target="_blank">
    GitHub</a>&nbsp;|&nbsp;
     <a href="https://cursos.alura.com.br/user/rluisp" target="_blank"> Alura Profile</a>
&nbsp;|&nbsp;
       <a href="https://www.dio.me/users/rluispdev" target="_blank">DIO</a>
&nbsp;|&nbsp;      
    <a href="https://www.linkedin.com/in/rafael-luis-gonzaga-b11634186/" target="_blank">LinkedIn</a>
&nbsp;|&nbsp;
    <a href="https://www.instagram.com/rluispdevs?igsh=cnoxenpmaHY1amE0&utm_source=qr" target="_blank">
    Instagram</a>
&nbsp;|&nbsp;</p>
</p>
<br/><br/>
<p>
