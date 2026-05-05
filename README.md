# Git-GitRub
-----------------------------------------------------------------------------------------------
*GIT(2005 Linus Torvals) --> Software de Controle de Versão (VSC)|(1972): {

- Git(Repositório Local)

- Criado devido a uma treta entre o criador do Bitkeeper(Centralizado) e Linus Torvalds;

- Ferramenta de Versionamento de soft;

- EX: Você cria um projeto e vai criando backups/zip e armazenando, mas e se seu hd corromper ? vai guardar
num google drive ? mas e se o projeto tiver várias pessoas responsáveis por back/frontand e 
todo mundo colocando numa pasta no google drive ? terá conflitos. 

- Máquina do tempo = Você poderá voltar a qqr ponto do projeto;

- Git != GitHub(Rede social dos programadores);



}
-----------------------------------------------------------------------------------------------
- Quando você conclui aqueles 2/4 do projeto final e quer armazená-lo em um repositório, você 
estará fazendo um commit;


- commit = Mandar seu projeto/versão para um repositório central;
------------------------------------------------------------------------------------------------

*Modelos de Repositórios VSC = Centralizado/Linear(Central) & --> Distribuído(Local/Remoto) <--;


*Centralizado = Precisa de um servidor constantemente conectado: {

-EX: CCC, SCCS, Panvalet, CVS, clearcase, Perforce; "São antigos"

- Como acontece =>  [Projeto] --> commit --> [R. Central] ;

}

*Distribuido = Local/Remoto: V {

- EX: Mercurial, Bazzar, GNU arch, BitKeeper, Git;

- Como acontece => [Projeto] --> commit --> [R. Local(Git)] --> push --> [R. Remoto(GitHub)];

}
-----------------------------------------------------------------------------------

*Vantagens: {

- Controle de histórico; ()
- Ramificação do projeto; (Cada um faz o seu trabalho) 
- Segurança; (Cada um só tem acesso a sua ramificação)
- Organização;

}

-----------------------------------------------------------------------------

*GitHub => Repositório Remoto;

- [Projeto] --> commit --> [R. Local(Git)] --> push --> [R. Remoto(GitHub)]

- Rede social dos programadores;

- Só existe ela? N!(- GitLab, Gogs, Kallithea, Bitbucket -);

---------------------------------------------------------------------------
*Características {

- Repositório ilimitados;
- Hospedagem de cógido-fonte;
- GitHub Pages integrado;
- Colaboração;

}
-----------------------------------------------------------------------------

* GitHub => kanban dentro do github: Aula 05/05/2026 (Projeto Wwb)

   - Papel de QA = Garantia de qualidade;
   - Garantir a qualidade do produto como um todo;

  
           🧠 O que um QA realmente faz
               ✔️ 1. Previne problemas (não só encontra)
                  
                     Um bom QA trabalha antes mesmo do código existir:
                     
                     Analisa requisitos
                     Questiona regras de negócio
                     Identifica falhas de lógica
                     
                     👉 Exemplo: “E se o usuário enviar um campo vazio?”
                     Se ninguém pensou nisso, o QA levanta antes de virar bug.
            
               ✔️ 2. Testa o sistema
            
                     Aqui entra o que todo mundo conhece:
                     
                     Testes manuais (clicando, validando fluxos)
                     Testes exploratórios
                     Testes de regressão
                     
                     Mas não é só “clicar” — é testar com intenção:
                     
                     Quebrar o sistema
                     Simular erro de usuário
                     Validar cenários reais
     
               ✔️ 3. Automatiza testes
            
                     QA moderno também programa:
                     
                     Testes automatizados (JUnit, Cypress, Selenium)
                     Testes de API (Postman, RestAssured)
                     Integração com CI/CD
                     
                     👉 No seu caso (Spring Boot), por exemplo:
                     
                     Testar endpoints REST
                     Validar respostas JSON
                     Garantir que o CRUD não quebre
 
     
               ✔️ 4. Garante qualidade contínua
            
                     QA acompanha o projeto inteiro:
                     
                     Participa de planning
                     Define critérios de aceitação
                     Valida entregas antes de produção
               ✔️ 5. Comunica problemas
            
                     QA não só acha bug — ele explica bem o problema:
                     
                     Como reproduzir
                     O que era esperado
                     O que aconteceu
                     Evidências (prints, logs)
---------------------------------------------------------------------------


