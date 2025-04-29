 ## 1. Fluxo-navegacao-principal.

Nome: Fluxo de Navegação Principal da Aplicação
Tipo: Fluxograma de Decisão
Este fluxograma mostra todo o caminho que um usuário pode percorrer dentro da plataforma, desde o momento em que acessa o sistema até o encerramento de sua navegação.
Inclui decisões como:

Login: verificar se o usuário já tem conta e, se não, criar uma nova.

Acesso a cursos: escolher entre visualizar e se inscrever em cursos disponíveis.

Busca por emprego: visualizar vagas, enviar currículo e aguardar retorno.

Fluxos com condições (sim/não): como aceitar os termos, ter conta criada, concluir ações ou sair do sistema.


Esse diagrama organiza bem os caminhos possíveis e suas consequências, o que ajuda tanto no desenvolvimento como na experiência do usuário.


---

## 2. Diagrama-casos-de-uso.

Nome: Diagrama UML de Casos de Uso
Este diagrama mostra os principais atores e ações que ocorrem dentro do sistema, focando em quem faz o quê.

Atores:

Usuário: acessa o sistema, faz login, procura cursos e empregos.

Governo: disponibiliza cursos.

Empresário: recebe inscrições para entrevistas.


Casos de uso principais:

Fazer login (com verificação de senha e possível erro).

Procurar cursos e se inscrever.

Procurar empregos e se inscrever em entrevistas.



As conexões indicam relacionamentos diretos entre os atores e os serviços prestados pela plataforma. Serve como base para entender a responsabilidade de cada tipo de usuário.


---

## 3. Fluxo-login-curso-emprego.

Nome: Fluxo Específico de Ações — Login, Cursos e Empregos
Tipo: Fluxograma Funcional com Interações Externas

Este fluxograma foca nos processos internos e integrações externas da plataforma em três situações principais:

Login: o sistema verifica a senha e trata o erro caso seja incorreta.

Cursos: o usuário busca cursos e se inscreve; essa ação gera uma comunicação com o setor responsável (governo).

Empregos: ao procurar emprego, o usuário pode se inscrever em entrevistas, ativando o contato com empresários.


Mostra as linhas de comunicação entre o sistema e os agentes externos (governo e empresas), além de deixar claro o que acontece dentro da aplicação e o que é resposta de fora.

### link do figma: https://www.figma.com/design/STPfMCYCUoWzJ7lzGfkfja/Untitled?node-id=4-38&t=Dd7DdgaJME4X8XPH-1
