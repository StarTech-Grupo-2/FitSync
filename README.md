
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet: [https://padlet.com/josianebatista1](https://padlet.com/josianebatista1)

## 1. Introdução

***1.1.  Nome do Grupo***

Josiane Batista        - [https://github.com/josibatista](https://github.com/josibatista )  
Leticia Bento          - [https://github.com/lettiebento](https://github.com/lettiebento)   
Maria Clara Nascimento - [https://github.com/mariandj](https://github.com/mariandj)  
Pamela Berti           - [https://github.com/pamms2](https://github.com/pamms2)

<!-- essa é uma forma de deixar alinhado, mas não sei se é a melhor
| Nome                  | GitHub Link                           |
|-----------------------|---------------------------------------|
| Josiane Batista       | [https://github.com/josibatista](https://github.com/josibatista) |
| Leticia Bento         | [https://github.com/lettiebento](https://github.com/lettiebento) |
| Maria Clara Nascimento| [https://github.com/mariandj](https://github.com/mariandj) |
| Pamela Berti          | [https://github.com/pamms2](https://github.com/pamms2) |
-->

***1.2.  Nome do Sistema***

FitSync

***1.3.  Propósito do Sistema***

O aplicativo propõe gerenciar os treinos dos usuários com uma abordagem interativa entre eles, permitindo o compartilhamento de metas e rotinas de treino, promovendo assim um ambiente de incentivo mútuo.  
A StarTech entende que resolver desafios como a falta de engajamento, a desistência de usuários, a dificuldade na gestão de treinos e o acompanhamento de progressos, além de democratizar o acesso a informações de treinos personalizados e nutrição, é tanto vantajoso quanto estratégico.   
Em resposta a esses problemas, e alinhada à crescente tendência de uma vida saudável e à busca pela otimização de tempo e economia de dinheiro, a aplicação integra alimentação e treino, além de apresentar uma IA especializada que fornece treinos e rotinas saudáveis na alimentação, proporcionando uma experiência personalizada e acessível. Essa abordagem torna o aplicativo uma solução promissora.  
Entre os diferenciais da aplicações estão: A função de competição entre usuários, que incentiva a assiduidade nos treinos ao registrar a sequência de dias em que o usuário realiza atividades físicas, e a IA que personaliza as rotinas de treino e alimentação.

***1.4.  Público Alvo***

Pessoas que já possuem ou desejam iniciar uma rotina de atividades físicas e estão em busca de recursos para monitorar tanto seus treinos quanto sua evolução nutricional, com o objetivo de manter a motivação e alcançar resultados de forma consistente.


***1.5. Descrição dos usuários***

Os usuários finais do sistema se dividem em dois perfis principais, com características e necessidades distintas:


Perfil do Usuário A: Esse perfil é composto por jovens de 18 a 25 anos, representando 75% do público total e com uma leve maioria masculina. Esses usuários têm uma grande familiaridade com o smartphone, utilizando-o ao longo do dia. Aprendem melhor na prática, preferindo explorar para adquirir novas habilidades. Eles seguem uma dieta voltada para o ganho de massa muscular e definição, priorizando proteínas e restringindo carboidratos. Costumam manter uma rotina intensa de exercícios, treinando quase todos os dias da semana.


Perfil do Usuário B: Representando 25% dos usuários, esse perfil é formado por pessoas entre 30 e 60 anos, com predominância feminina. Esses usuários fazem um uso moderado do smartphone e preferem aprender através de questionamentos e busca por informações detalhadas. Estão focados em uma alimentação equilibrada para melhorar a saúde e aumentar a longevidade. Sua rotina de exercícios é mais leve e espaçada, com treinos algumas vezes na semana.


| **Perfil do Usuário A**                                 | **Perfil do Usuário B**                                |
|---------------------------------------------------------|--------------------------------------------------------|
| **Porcentagem de usuário:** 75%                         | **Porcentagem de usuário:** 25%                        |
| **Faixa etária:** [18, 25]                              | **Faixa etária:** [30, 60]                             |
| **Gênero:** 55% masculino, 45% feminino                 | **Gênero:** 40% masculino, 60% feminino                |
| **Frequência de uso de smartphone:** Muito alta, mais de 5 horas por dia | **Frequência de uso de smartphone:** Moderada, menos de 5 horas por dia |
| **Estilo de aprendizado:** Aprende usando              | **Estilo de aprendizado:** Aprendem perguntando        |
| **Faz dieta:** Sim, focada em hipertrofia e definição muscular com baixo consumo de carboidratos e alto em proteínas | **Faz dieta:** Sim, focada em saúde e longevidade      |
| **Frequência de treinos:** 5 a 6 vezes na semana        | **Frequência de treinos:** 2 a 3 vezes na semana       |


***Personas:***

![PERSONA-A](https://github.com/user-attachments/assets/e0ae34c8-9a2c-476f-bac2-618ae2d37bae)

![PERSONA-B](https://github.com/user-attachments/assets/10f9997b-2666-40cb-9151-6a5edc33825b)

***Análise da situação atual: antes da introdução de sua solução***

*`1. O que as pessoas fazem?`*

Muitos usuários tentam manter uma rotina de treinos registrando o progresso em cadernos, planilhas ou aplicativos não integrados. Além disso, reconhecem a necessidade de serviços como personal trainers e nutricionistas para melhores resultados, mas esses serviços são inacessíveis para muitos devido ao custo. Frequentemente, negligenciam a importância da hidratação adequada, não atingindo as metas diárias de consumo de água. A falta de motivação é um grande desafio, levando muitos a desistirem de hábitos saudáveis.

*`2. Quais os artefatos envolvidos?`*

Aplicativos de treino e plataformas oferecidas pelas academias - que raramente integram áreas como nutrição. Sites e redes sociais com dicas de saúde. Além de planilhas digitais e cadernos físicos para registros manuais de progresso.

*`3. O que elas precisam saber?`*

Como desenvolver e manter uma rotina de treinos alinhada aos seus objetivos e condicionamento físico, incluindo progressões e variações. Como registrar e acompanhar seu progresso de forma clara e motivadora. Quais planos de treino e dieta são mais adequados às suas necessidades individuais, considerando saúde e objetivos pessoais.


***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

*`1. O que as pessoas fazem?`*

Com o aplicativo FitSync, os usuários conseguem acessar um sistema integrado para acompanhar treinos, dieta e consumo de água em um único lugar. Eles podem gerenciar suas rotinas personalizadas, consultando uma IA treinada para criar planos específicos de treino e alimentação focados em seus objetivos. O app também envia notificações personalizadas ao longo do dia para lembrá-los de treinar, seguir a dieta e manter a hidratação, ajudando-os a cumprir suas metas de forma prática e organizada.

*`2. Quais os artefatos envolvidos?`*

O aplicativo FitSync, que oferece uma integração completa entre a gestão de treinos, dieta e consumo de água, além de funcionalidades personalizadas como notificações e sugestões da IA integrada.

*`3. O que elas precisam saber?`*

Os usuários precisam aprender a utilizar o aplicativo FitSync e explorar suas funcionalidades para atingir seus objetivos. Para usuários da versão gratuita, é necessário já terem um treino e uma dieta definidos.


***Cenário: Antes***

Gabriel é um estudante universitário e praticante ativo de musculação. Ele utiliza planilhas no Google Sheets e anotações no celular para registrar seus treinos e dieta. Apesar de ser organizado, Gabriel sente dificuldade em manter tudo atualizado e centralizado, o que o faz perder tempo organizando informações em diferentes plataformas.  

Ele tenta ajustar sua dieta manualmente, pesquisando alimentos e montando refeições baseadas em suas metas de proteínas e carboidratos. Além disso, Gabriel usa aplicativos de redes sociais para compartilhar seu progresso com amigos e acompanhar desafios, mas o processo é desarticulado e exige múltiplos aplicativos. Isso o deixa frustrado por não conseguir integrar tudo em um só lugar.  

Com sua rotina intensa de estudos e academia, Gabriel frequentemente esquece de acompanhar sua hidratação, o que impacta negativamente seu desempenho nos treinos. Ele sente que não está atingindo seu potencial máximo por falta de uma ferramenta que facilite esse controle.

<img src=https://i.imgur.com/tO7bqgZ.png alt="Cenário - antes" width="1000">

***Cenário: Depois***

Gabriel utiliza o FitSync para centralizar todas as informações relacionadas à sua rotina de treinos e dieta. Após baixar o aplicativo, ele cria um perfil, assina o plano premium e insere suas metas de ganho muscular e definição. A partir disso, o FitSync sugere treinos personalizados, adequados à sua rotina, e uma dieta com foco em alto consumo proteico e controle de carboidratos, que ele pode ajustar facilmente.

Com o FitSync, Gabriel registra seus treinos rapidamente no final de cada sessão, e acompanha seu progresso e metas alcançadas. Ele também monitora sua dieta inserindo as refeições com horários pré-definidos. As notificações inteligentes do FitSync lembram Gabriel dos treinos e refeições no horário definido e, também, de se hidratar em intervalos regulares. 

Agora, Gabriel sente que está aproveitando ao máximo seu potencial. Com tudo integrado, ele tem mais tempo para focar nos estudos e treinos, enquanto acompanha sua evolução de forma prática e motivadora em um único sistema.

<img src=https://i.imgur.com/xbNwiOX.png alt="Cenário - depois" width="1000">

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

| Identificador | Descrição |
|---------------|------------|
| RF001 | O software deve permitir ao usuário realizar seu cadastro e login |
| RF002 | O software deve permitir ao usuário logado que registre seu treino |
| RF003 | O software deve proporcionar interface de checklist para o usuário fazer seu registro de exercícios |
| RF004 | O software deve permitir que o usuário adicione outros usuários ao seu perfil |
| RF005 | O software deve permitir que o usuário compartilhe treinos com outros usuários já inseridos em seu perfil |
| RF006 | O software deve enviar ao usuários notificações da dieta e água |
| RF007 | O software deve permitir que o usuário logado consulte os seus registros de exercícios, treinos e metas estabelecidas |
| RF008 | O software deve permitir que o usuário logado consulte a sua dieta e consumo de água |
| RF009 | O software deve permitir que o usuário solicite treinos e dietas à IA personalizada |
| RF010 | O software deve permitir que o usuário assine o plano premium |

***2.2. Requisitos Não Funcionais***

*<Link, imagem, arquivo com os requisitos não funcionais.>*

***2.3. Perguntas***

*<Arquivo com as perguntas realizadas na entrevista .>*

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***

*<Imagem, arquivo (PDF), link com as Histórias de Usuário.>*

***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

***2.9. Protótipos***

*<Imagem, arquivo (PDF), link com Protótipo.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
