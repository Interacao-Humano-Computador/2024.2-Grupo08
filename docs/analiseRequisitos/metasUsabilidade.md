# __Metas de Usabilidade__

## __Introdução__

Este documento descreve as metas de usabilidade para o portal do DETRAN-DF, baseadas. Segundo [Barbosa e Silva (2011, p.115)](referencias/usabilidade1.png), na fase da análise de requisitos são definidas as metas de usabilidades com base no perfil do usuário, análise de tarefas, características da plataforma, enquanto o guia de estilo funciona como um auxílio para a verificação durante o processo.

## __Plataforma__
  A avaliação considerará o contexto de uso do portal em navegadores web modernos (Google Chrome, Firefox, Safari e Microsoft Edge).

## **Metas de Usabilidade:**

* **Eficácia:** O portal deve permitir que os usuários realizem suas tarefas com sucesso, como acessar informações, realizar agendamentos e obter documentos.  A eficácia será medida pela taxa de sucesso na conclusão das tarefas.

* **Eficiência:** Os usuários devem conseguir realizar suas tarefas de forma rápida e com o mínimo de esforço. A eficiência será medida pelo tempo gasto para concluir as tarefas e pelo número de cliques/interações necessárias.

* **Segurança:** O portal deve proteger os dados dos usuários e garantir a segurança das transações.  A segurança será avaliada pela presença de mecanismos de segurança, como criptografia e proteção contra acesso não autorizado.  Além disso, o sistema deve minimizar a possibilidade de erros do usuário e fornecer mecanismos de recuperação.

* **Facilidade de Aprendizado:** O portal deve ser fácil de aprender a usar, mesmo para usuários com pouca experiência com computadores ou com o próprio portal. A facilidade de aprendizado será medida pelo tempo que os usuários levam para aprender a usar as principais funcionalidades do portal.

* **Facilidade de Recordação:** Os usuários devem ser capazes de se lembrar como usar o portal, mesmo após longos períodos sem utilizá-lo. A facilidade de recordação será avaliada testando a capacidade dos usuários de realizar tarefas após um período de inatividade.

* **Satisfação:** Os usuários devem ter uma experiência positiva ao usar o portal. A satisfação será medida por meio de pesquisas de satisfação e feedback dos usuários.


## **Requisitos de Usabilidade (derivados das metas):**

Requisitos de usabilidade:

* **MU1 (Eficiência):**  Acessar as principais funcionalidades (ex: agendamento de serviços, consulta de multas) deve ser possível em no máximo 4 cliques a partir da página inicial.

* **MU2 (Facilidade de Aprendizado/Eficácia):** A taxa de acesso à seção de ajuda para as principais funcionalidades deve ser inferior a 30%, indicando que a interface é intuitiva e fácil de usar.

* **MU3 (Satisfação/Eficiência):** O tempo médio de sessão do usuário deve ser analisado para identificar possíveis gargalos na usabilidade.  Sessões muito curtas podem indicar dificuldades em encontrar informações ou realizar tarefas.  Sessões muito longas podem indicar processos complexos e ineficientes.  A análise do tempo de sessão, combinada com outras métricas, ajudará a entender a experiência do usuário.

* **MU4 (Satisfação):**  A satisfação do usuário deve ser medida através de uma métrica como o Net Promoter Score (NPS), com o objetivo de alcançar uma pontuação promotora alta (ex: acima de 70).

* **MU5 (Eficiência):** O tempo médio para realizar tarefas-chave, como iniciar um agendamento ou consultar o status de um processo, deve ser minimizado (ex: menor que 1 minuto).

* **MU6 (Segurança/Satisfação - Adaptado):** O sistema deve fornecer notificações (ex: por email) sobre atualizações importantes em processos ou serviços solicitados pelo usuário, aumentando a transparência e a segurança.

## __Razão da escolha das metas de usabilidade__

Escolher as metas de usabilidade certas é essencial para criar sistemas fáceis de usar e que funcionem bem.  Para isso, precisamos entender o que os usuários querem, o que o projeto precisa alcançar e quais as melhores práticas de design.  O tipo de sistema e os recursos disponíveis também influenciam essa escolha.  

Basicamente, é um equilíbrio entre as necessidades dos usuários, os objetivos do projeto e o que é possível fazer.
Além disso, a seleção das metas deve se basear em princípios e boas práticas de usabilidade, como as heurísticas de Nielsen.  

Essas heurísticas, amplamente reconhecidas na área de Interação Humano-Computador (IHC), fornecem um conjunto de diretrizes para o design de interfaces usáveis, contribuindo para a definição de metas como facilidade de aprendizado e facilidade de recordação.

### 1. Eficácia

No geral o sistema é parcialmente eficaz, tudo que ela é proposta a ser feita, consegue com êxito mostrar os eventos que o usuário realize.

### 2. Eficiência

O sistema não apresenta uma eficiência mediana. A interface não possui ferramentas de auxílio a usuários com limitações, preenchimento de dados automático, atalhos e ou ferramentas de voz. 

### 3. Segurança

A aplicação possui algumas falhas de incertezas, como por exemplo na imagem 1, temos a tela de transferência de veículo, e solicita o RENAVAM do veículo. Não é claro que caso coloque o código, será feito a transferência ou não. ( comigo mesmo fiquei com receio de colocar o código do RENAVAM).

<center>

**Imagem 1**

</center>

![tela transferencia](referencias/tela-tranferencia.png)

<center>

_Autor: Márcio Henrique_

</center>

### 4. Utilidade

O sistema se apresenta eficiente. Ele assegura que veículos e condutores estejam em conformidade com as leis, promove a segurança nas vias ao monitorar infrações e acidentes, e oferece serviços práticos que simplificam a vida dos cidadãos. 

### 5. Aprendizado

O sistema possui funcionalidades explicitas para o usuário sendo elas objetivas, evitando que o usuário precise de um longo período de treinamento.

### 6. Memorização

A utilização do sistema se torna bastante intuitiva com a experiência de apenas alguns usuários, voltado para quem tem mais afinidade a tecnologia essa memorização torna-se mais propícia.

## __Referências Bibliográficas__

> _BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011._


## __Histórico de versão__

| Versão |    Data    |      Descrição      |             Autor(es)                        |Revisor(es)|
|--------|------------|---------------------|----------------------------------------------|---------|
| `1.0`  | 02/12/2024 | Criação do documento. | [Kaio Enzo](https://github.com/kaioenzo) e [Márcio Henrique](https://github.com/DeM4rcio) | [Luiza Maluf](https://github.com/LuizaMaluf)|
| `1.1`  | 05/12/2024 | Correções da verificação. |[Márcio Henrique](https://github.com/DeM4rcio) | [Luiza Maluf](https://github.com/LuizaMaluf)|