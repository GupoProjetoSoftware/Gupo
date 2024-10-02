<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Sistema de presença Gupo&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#autores)
- [Descrição do Projeto](#descrição-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)
- [Descrição dos Casos de Uso](#descrição-dos-casos-de-uso)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* André Sapucaia                 10418734
* Bernardo Souza Oliveira        10312871
* Diogo Ozi                      10403852
* Henrique Yuji Isogai Yoneoka   10418153
* José Victor Scheurich Roling   10418225


# Descrição do Projeto

O projeto consistirá de um sistema de presença para a escola INFINITO. Ele terá que computar as faltas dos alunos de todas as turmas da escola (do primeiro ao quinto ano do ensino fundamental). Haverá um professor principal que é responsável pelas disciplinas de Matemática, Português, Artes, Ciências, História e Geografia, e um professor para Inlês e outro para Educação Física.</br> Esse sistema deverá gerar um relatório de faltas organizados por diversas categorias, como data, ano de ensino, turma, professor, disciplina ou aluno. Nessa escola, a chamada é feita duas vezes ao dia, já que a maior parte das matérias é ministrada pelo mesmo professor. Caso o aluno termine o ano com menos de 75% de presença, o sistema deverá considerá-lo como "reprovado por faltas". Portanto, a partir do momento em que o aluno tiver uma porcentagem de presença menor do que 80%, o sistema deverá enviar uma notificação aos responsáveis do aluno avisando que ele está próximo do limite de faltas.</br> Adicionalmente, o sistema deverá ser inclusivo, de forma que pessoas portadoras de deficiências físicas sejam capazes de utilizá-lo sem dificuldades com o aumento do tamanho dos textos e uma opção para ouvir as funcionalidades em áudio, de forma que os usuários consigam utilizá-lo de forma prática, e por meio de qualquer navegador web.

# Análise de Requisitos Funcionais e Não-Funcionais
[RF001  - Login]: O usuário deve ser capaz de entrar no sistema utilizando o nome de usuário e senha.</br>
[RF002  -  Cadastro]: O usuário deve ser capaz de criar uma conta no sistema inserindo os dados pessoais.</br>
[RF003  -  Registro de faltas]: O sistema deve permitir que o professor registre as faltas dos alunos duas vezes por dia</br>
[RF004  -  Relatório de faltas]: O sistema deve permitir que o professor gere relatorios capaz de visualizar as faltas organizadas em datas, turmas, disciplinas, professor, ano de ensino e faltas.</br>
[RF005  -  Notificação ao responsável]: O sistema deve enviar uma notificação por e-mail ao responsável do aluno quando o mesmo atinge 80% de presença.</br>
[RF006  -  Visualizar perfil]: O aluno, o professor e o responsável deve ser capaz de acessar o perfil do aluno com as suas informações.</br>
[RF007  -  Pesquisar aluno]: O professor deve ser capaz de encontrar o aluno desejado por nome e turma.</br>
[RF008  -  Gestão de turmas]: O sistema deve permitir a criação e gerenciamento de turmas, alocando alunos e professores em cada turma.</br>
[RF009 - Exportação de relatórios]: O sistema deve permitir a exportação de relatórios de faltas e presenças em formatos como PDF ou Excel.</br>
[RF010 - Níveis de acesso]: O sistema deve suportar diferentes níveis de acesso, como administrador, professor, aluno e responsável, com permissões específicas para cada perfil.</br>



[RNF001  -  Configuração]: O sistema deve ser capaz de suportar minimamente 300 computações de falta por dia</br>
[RNF002  -  Acessibilidade]: O sistema deve ser acessível, permitindo alterações como tamanho da fonte, reconhecimento por voz, plugin de acessibilidade em línguas de sinais e software de leitura de tela.</br>
[RNF003  -  Compatibilidade]: O sistema deve permitir o acesso em dispositivos móveis e computadores, tendo seu próprio aplicativo ou via web.</br>
[RNF004 - Desempenho]: O sistema deve responder às ações do usuário em até 2 segundos para garantir uma experiência fluida.</br>
[RNF005 - Usabilidade]: O sistema deve ser intuitivo e fácil de usar, seguindo as melhores práticas de design de interface e experiência do usuário.</br>
[RNF006 - Escalabilidade]: O sistema deve ser escalável para suportar um aumento no número de usuários sem perda de desempenho.</br>

# Diagrama de Atividades
![image](https://github.com/user-attachments/assets/6ba2fc0f-e42d-4d74-a695-20b1f7ca9e14)
![image](https://github.com/user-attachments/assets/937af0d5-c827-4252-b78b-93f738208170)
link: https://app.diagrams.net/#G1cr0_u92LDlYab_agNlxLE18xNJm6x0E1#%7B%22pageId%22%3A%22cSahUEfquRX7Xm5HyozH%22%7D

# Diagrama de Casos de Uso

![image](https://github.com/user-attachments/assets/a8723126-092d-4082-8210-5423762df325)
link: https://app.diagrams.net/#G1t5n4MYqT5EJt036Dnl3jX7yXbz_8akx1#%7B%22pageId%22%3A%22C5RBs43oDa-KdzZeNtuy%22%7D

# Descrição dos Casos de Uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
