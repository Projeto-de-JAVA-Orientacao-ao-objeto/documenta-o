# Future

## Descrição

Este projeto visa desenvolver um sistema de uma instituição de ensino utilizando a metodologia ágil e práticas de DevOps integradas ao GitHub. A arquitetura do software seguirá o padrão Model-View-Controller (MVC) e incorporará o(s) padrõe(s) de projeto  Factory, Observer, Singleton, Strategy e Command  para garantir uma base de código robusta e escalável. O desenvolvimento será feito na linguagem Java.-

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


## Requisitos ou História de Usuário

Ideia inicial do projeto`https://www.figma.com/design/1xbJAbvJVv1xFJAJ1zLqtj/ProjetoJava?node-id=0-1&t=9TOV98ulzcJDptbf-1`

![WhatsApp Image 2024-12-09 at 19 38 14](https://github.com/user-attachments/assets/9c20665d-8563-453a-8db4-e477b6b84e0b)


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

![Future](https://github.com/user-attachments/assets/d396e9f4-ef91-4333-abe4-fc3a47aebdcd)

   
   ### Diagrama de Classe

Link do arquivo Diagrama de Classe: [Future [MConverter.eu].pdf](https://github.com/user-attachments/files/18068499/Future.MConverter.eu.pdf)


## Estrutura do Projeto  
•    Estrutura de Diretórios Utilizada:   
├── src/   
│   ├── `model/`   
│   ├── `view/`   
│   ├── `controller/`   
│   ├── `service/`    
│   └── `database/`   
•    Explicação rápida de cada diretório:   
o    Model: Classes que representam os dados e regras de negócio.   
o    View: Classes que representam a interface do projeto.   
o    Controller: Classes utilizadas para a intermediação entre a interface e o projeto.   
o    Service: Classes utilizadas para gerenciar a lógica do projeto.   
o    Database: Classes utilizadas para a interação com o banco de dados.   
__   
•    Diagrama do fluxo de dados no projeto:  
o    Usuário interage com a View.   
o    Controller processa a interação e acessa o Service.   
o    Service interage com o Database e Model.  
o    View exibe os resultados.    
  
## Tecnologias Utilizadas
- [JAVA]
- [MYSQL]

## Instruções de Instalação
1. Clone o repositório:
   ```sh
   git clone [https://github.com/sua-organizacao/nome-do-repositorio.git](https://github.com/Projeto-de-JAVA-Orientacao-ao-objeto/code/tree/main/Future)

   importar e instalar banco de dados https://github.com/Projeto-de-JAVA-Orientacao-ao-objeto/database/blob/main/future.sql
   
   caminho do banco: localhost:3306
   login: root
   senha: future2024

   executar pastar "main"
   
## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo (https://github.com/Projeto-de-JAVA-Orientacao-ao-objeto/documents/blob/main/MIT%20License) para mais detalhes.
## Contato
<Comentario: adicione foto, nome e email dos integrantes do grupo>   
    
Eric Dias Lemos - ericdias0603@gmail.com     
Vitor Junio Moreira da Silva - vitorjunio312@hotmail.com   
Gabriel Henrique Nascimento Ribeiro Rezende - gabrielhnrezende@gmail.com     
Gustavo Lopes de Oliveira    
