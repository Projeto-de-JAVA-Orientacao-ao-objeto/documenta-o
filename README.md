# Future

## Descrição

Este projeto visa desenvolver um sistema de uma instituição de ensino utilizando a metodologia ágil e práticas de DevOps integradas ao GitHub. A arquitetura do software seguirá o padrão Model-View-Controller (MVC) e incorporará o(s) padrõe(s) de projeto  Factory e Observer para garantir uma base de código robusta e escalável. O desenvolvimento será feito na linguagem Java.-

## Índice

1. [Objetivos do Projeto](#objetivo)
2. [Definições, Acrônimos e Abreviações](#definição)
3. [Requisitos](#requisitos)
   1. [Requisitos Funcionais](#rf)
   2. [Requisitos Não Funcionais](#rnf)
4. [Diagramas UML](#uml)
   1. [Diagrama de Casos de Uso](#uc)
   2. [Diagrama de Classe](#classe)
5. [Estrutura do Projeto](#estrutura)
6. [Contribuição](#contribuição)
7. [Licença](#licença)
8. [Contato](#contato)

## Definições, Acrônimos e Abreviações.
 < ▪ DC - Documentação 
 < ▪ UC - Unidade de codigo        
 < ▪ BD - Banco de dados   
 < ▪ SCRUM - Metodologia ágil utilizada no desenvolvimento de projetos   

## Requisitos ou História de Usuário

 < ▪ O usuário administrador/aluno/professor deve conseguir acessar a tela de login.   
 < ▪ O login deve ser efetuado em no maximo 3 segundos.   

   ### Requisitos Funcionais
ID Login - 01 -  O sistema deverá solicitar ao usuário seu login e senha e verificar se o mesmo possui permissão de acesso ao sistema  
 
ID Administrador RF 02 O sistema irá exibir uma interface com as seguinte opções  

   < ▪ Cadastrar Usuário  
   < ▪ Cadastrar Curso  
   < ▪ Cadastrar Aulas  
   < ▪ Vizualizar Cursos  
   < ▪ Vizualizar Alunos  
   < ▪ Vizualizar Pofessores  

ID Professor RF 03 O sistema irá exibir uma interface com as seguinte opções:

   < ▪ Sala de Aula    
   < ▪ Atividades   
   < ▪ Distribuir Notas  
   < ▪ Encaminhar Avisos   
   < ▪ Membros Materia  
   < ▪ Vizualizar Atividades Encaminhadas  

ID Aluno RF 04 O sistema irá exibir uma interface com as seguinte opções:

   < ▪ Assistir Aulas   
   < ▪ Atividades   
   < ▪ Vizualizar notas   
   < ▪ Membros Matéria   
   < ▪ Alterar Grade   
   < ▪ Avisos  

   ### Requisitos Não Funcionais
   < ▪ O sistema deve responder a qualquer operação no tempo máximo de 2 segundos.  
   < ▪ O sistema deve ser seguro ao armazenar as informações do cliente.  

## Diagramas UML
   <Comentario
   
   ### Diagrama de Casos de Uso
    <Comentario 
    ID Caso de Uso               Descrição do Objetivo do Caso de Uso
    UC1 Consultar Pedido de Sala Permite consultar os pedidos de sala solicitados.
   
   ### Diagrama de Classe

1. Desempenho
▪ O sistema deve carregar as principais funcionalidades em menos de 2 segundos para a maioria dos usuários, considerando conexões de internet com velocidade média de 10 Mbps.
▪ O tempo de resposta para as ações do usuário (como salvar notas ou postar atividades) deve ser inferior a 1 segundo.
▪ O aplicativo deve funcionar de forma eficiente em dispositivos com memória RAM a partir de 2 GB.

2. Usabilidade
▪ O sistema deve ser intuitivo e fácil de usar, minimizando a necessidade de treinamento para professores, alunos e administradores.
▪ Deve incluir um design responsivo, que permita a utilização em smartphones, tablets e desktops sem perda de funcionalidade ou legibilidade.
▪ Deve apresentar feedback visual imediato para cada interação do usuário (ex.: animações simples, mensagens de confirmação ou erro).

3. Confiabilidade e Disponibilidade
▪ O sistema deve ter uma disponibilidade mínima de 99,5% ao longo do mês.
▪ Em caso de falhas ou interrupções, a aplicação deve oferecer uma recuperação em menos de 1 hora.
▪ Deve manter backups automáticos diários das informações críticas para garantir a integridade dos dados.

4. Escalabilidade
▪ O sistema deve ser capaz de suportar até 5.000 usuários simultâneos sem perda significativa de desempenho.
▪ Deve permitir a expansão futura com adição de novos módulos (ex.: funcionalidades extras ou integração com outros sistemas) sem reestruturação significativa.

5. Segurança
▪ Todas as comunicações entre o cliente e o servidor devem ser criptografadas usando HTTPS e SSL/TLS.
▪ Deve garantir autenticação segura para todos os usuários com controle de acesso baseado em papéis (RBAC).
▪ Os dados sensíveis devem ser armazenados com hashing seguro para senhas e criptografia para informações críticas.


## Estrutura do Projeto 
<Comentario: faça a adaptação necessária para o seu projeto
- `src/`: Código-fonte do projeto.
- `docs/`: (https://github.com/Projeto-de-JAVA-Orientacao-ao-objeto/documents)

## Tecnologias Utilizadas
- [JAVA]
- [SQL]
- 
- [Outras Tecnologias]

## Instruções de Instalação
1. Clone o repositório:
   ```sh
   git clone https://github.com/sua-organizacao/nome-do-repositorio.git
## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo <LICENSE> para mais detalhes.
## Contato
<Comentario: adicione foto, nome e email dos integrantes do grupo>
