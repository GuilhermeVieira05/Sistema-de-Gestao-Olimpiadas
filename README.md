# 🏅 Sistema de Gestão das Olimpíadas (SGO)

### 📝 Descrição do Sistema
Com a chegada das **Olimpíadas**, um novo sistema de gestão é necessário para coordenar os diferentes aspectos do evento.  
O **SGO (Sistema de Gestão das Olimpíadas)** tem como objetivo permitir o **gerenciamento de competições**, **inscrições de atletas**, **alocação de locais para as provas** e o **controle de resultados**, garantindo uma organização eficiente e integrada de todas as atividades envolvidas.

---

## Diagrama de Caso de Uso:

![Diagrama de Caso de Uso](https://github.com/GuilhermeVieira05/Sistema-de-Gestao-Olimpiadas/blob/main/imagens/diagrama-de-caso-de-uso.png)

> 🔗 **Para melhor visualização**, acesse o diagrama completo no [Creately](https://app.creately.com/d/GdDfLxQfDhd/edit).

---

## Diagrama de Classe e Pacote:

![Diagrama de Classe e Pacote](https://github.com/GuilhermeVieira05/Sistema-de-Gestao-Olimpiadas/blob/main/imagens/diagrama-de-classes-e-pacotes.png)

> 🔗 **Modelagem detalhada disponível no [Figma](https://www.figma.com/board/bOZNhxoYdgG25CeLt4xI4r/Class-Diagram-Template--Community-?node-id=0-1&p=f&t=TJiBYnzaVgd5QrzF-0)**

---

## Diagrama de Componentes:

![Diagrama de Componentes](https://github.com/GuilhermeVieira05/Sistema-de-Gestao-Olimpiadas/blob/main/imagens/diagrama-de-componentes.png)

> 🔗 **Visualize melhor no [Figma](https://www.figma.com/design/pt0Nla4KSWvQhoRzDnycWB/Diagrama-de-Componentes--Projeto-de-Software-?node-id=0-1&p=f&t=EkLgwELRe672RGGB-0)**

---

## Diagrama de Implantação:

![Diagrama de Implantação](https://github.com/GuilhermeVieira05/Sistema-de-Gestao-Olimpiadas/blob/main/imagens/diagrama-de-implantacao.png)

> 🔗 **Para uma visualização mais completa**, acesse o diagrama completo no [Draw.io](https://drive.google.com/file/d/1Nnr9rx9MP-sN_LaD1t7a79D2_ca7z6y9/view?usp=sharing).

---

## Histórias de Usuários:

### 🏆 US01 – Cadastro de Competições
**Como** organizador do evento,  
**quero** cadastrar competições com informações sobre modalidade, data, horário, local e atletas inscritos,  
**para que** o sistema mantenha um controle organizado de todas as provas que ocorrerão durante as Olimpíadas.

**Critérios de Aceitação:**
- O sistema deve permitir o cadastro de uma nova competição com os campos: modalidade, data, horário e local.  
- Deve ser possível adicionar ou remover atletas da lista de inscritos.  
- O sistema deve validar se o local e horário estão disponíveis antes de confirmar o cadastro.

---

### 🥇 US02 – Inscrição de Atletas
**Como** atleta participante,  
**quero** me inscrever em diferentes competições, especificando o país que represento,  
**para** participar oficialmente das provas nas quais desejo competir.

**Critérios de Aceitação:**
- O atleta deve poder se inscrever em mais de uma competição.  
- O atleta só pode representar um país em cada modalidade.  
- O sistema deve validar se o atleta já está inscrito na competição antes de aceitar nova inscrição.

---

### 🏟️ US03 – Alocação de Locais
**Como** organizador do evento,  
**quero** alocar locais para cada competição,  
**para** garantir que não haja conflitos de horário e que cada local seja utilizado de forma organizada.

**Critérios de Aceitação:**
- Um local não pode ser utilizado por duas competições ao mesmo tempo.  
- O sistema deve emitir um aviso caso o local esteja indisponível no horário desejado.  
- Deve ser possível consultar a agenda de uso dos locais.

---

### 🏁 US04 – Controle de Resultados
**Como** organizador do evento,  
**quero** registrar os resultados após a realização das provas,  
**para** determinar os vencedores e atualizar automaticamente o quadro de medalhas.

**Critérios de Aceitação:**
- O sistema deve permitir o registro do 1º, 2º e 3º colocados de cada competição.  
- Ao salvar os resultados, o sistema deve atualizar o relatório de medalhas por país.  
- Deve haver histórico dos resultados para consultas posteriores.

---

### 🥈 US05 – Relatórios de Medalhas
**Como** organizador do evento,  
**quero** gerar relatórios de medalhas por país,  
**para** visualizar o desempenho geral e classificar as nações de acordo com o número de medalhas de ouro, prata e bronze.

**Critérios de Aceitação:**
- O sistema deve exibir um ranking com o total de medalhas por país.  
- Deve permitir filtrar os relatórios por modalidade ou período.  
- O relatório deve poder ser exportado em formato PDF ou CSV.

---

### 🏋️‍♂️ US06 – Cadastro de Atletas
**Como** organizador do evento,  
**quero** cadastrar atletas com informações pessoais e país de origem,  
**para** que possam ser inscritos nas competições e identificados corretamente nos resultados.

**Critérios de Aceitação:**
- O sistema deve permitir o cadastro de atletas com os campos: nome completo, data de nascimento, gênero e país representado.  
- Deve ser possível editar ou remover cadastros de atletas.  
- O sistema deve validar se o atleta já está registrado antes de permitir novo cadastro.

---

### 📅 US07 – Consulta e Agenda de Competições
**Como** atleta,  
**quero** consultar a agenda completa das competições,  
**para** visualizar os horários, locais e provas nas quais estou inscrito ou pretendo participar.

**Critérios de Aceitação:**
- O sistema deve listar todas as competições com data, horário, local e modalidade.  
- Deve ser possível filtrar as competições por data, modalidade ou local.  
- O atleta deve poder visualizar em destaque as competições em que está inscrito.

---

### 📊 US08 – Histórico
**Como** organizador do evento,  
**quero** acessar o histórico de resultados,  
**para** acompanhar a evolução das competições e gerar estatísticas sobre os participantes.

**Critérios de Aceitação:**
- O sistema deve manter histórico de resultados de todas as competições.  
- Deve ser possível consultar o número de medalhas conquistadas por atleta e por país.  
- O sistema deve gerar gráficos e estatísticas de desempenho com base nos dados registrados.

---
