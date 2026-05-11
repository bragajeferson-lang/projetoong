Documentação do Sistema Web - ONG Mãe Águia

Resumo Este projeto visa desenvolver uma aplicação web responsiva para a ONG Mãe Águia, atualizando o sistema desktop original desenvolvido em PyQt5. A solução web permite o controle eficiente dos atendimentos realizados pela organização, com interface acessível via navegador, facilitando o acesso dos colaboradores independentemente de sua localização ou dispositivo utilizado. A implementação utiliza HTML5, CSS3 e Bootstrap 5 para garantir uma experiência moderna, responsiva e alinhada com as necessidades de usabilidade da organização.

Introdução A ONG Mãe Águia atua no atendimento a famílias, jovens e crianças em situação de vulnerabilidade, mas enfrentava desafios com o manual de gestão de informações. O sistema original em PyQt5, embora funcional, limitou o acesso aos computadores onde estava instalado. Esta solução web migra toda a funcionalidade para uma plataforma acessível via navegador, mantendo a identidade visual e as funcionalidades essenciais, enquanto adiciona vantagens da acessibilidade web.

Objetivo Geral Desenvolver uma aplicação web responsiva para gestão de atendimentos da ONG Mãe Águia, integrando sistema de autenticação, registro de atendimentos e geração de relatórios, com interface adaptada a diferentes dispositivos.

Objetivos Específicos Implementar interface web responsiva utilizando HTML5, CSS3 e Bootstrap 5

Desenvolver sistema de autenticação para colaboradores

Criar mecanismos de registro e consulta de atendimentos

Implementar geração de relatórios estatísticos

Garantir compatibilidade com diferentes navegadores e dispositivos

Justificativa e Delimitação do Problema A migração para uma solução web justifica-se pela necessidade de ampliar o acesso ao sistema, permitindo que os colaboradores utilizem diferentes dispositivos (computadores, tablets e smartphones) para registrar atendimentos. A solução é delimitada ao controle de atendimentos e geração de relatórios, não incluindo funcionalidades financeiras ou de gestão de ações.

Fundamento Teórico O desenvolvimento utiliza Bootstrap 5, framework front-end que facilita a criação de interfaces responsivas através de seu sistema de grid e componentes pré-estilizados (OTAN, 2021). A arquitetura segue princípios de Design Responsivo, garantindo adaptação a diferentes tamanhos de tela (MARCOTTE, 2011). A segurança da aplicação é garantida através de validações no front-end e back-end.

Metodologia 7.1 Planejamento e Definição do Projeto Análise do sistema original em PyQt5 para identificação de funcionalidades essenciais

Definição de requisitos com colaboradores da ONG

Seleção de tecnologias: HTML5, CSS3, Bootstrap 5, JavaScript e Python/Flask para back-end

7.2 Implementação Estruturação dos componentes modulares do front-end do Bootstrap

Desenvolvimento de interface responsiva e acessível

Implementação de sistema de autenticação

Integração com API back-end para persistência de dados

7.3 Publicação e Documentação Hospedagem em servidor web com certificado SSL

Documentação no README com instruções de uso

Treinamento de colaboradores para utilização do sistema

Resultados Preliminares: Solução Inicial A solução inicial implementa a tela de login com os seguintes elementos:
Cabeçalho com identidade da ONG Mãe Águia

Imagem representativa da águia americana

Formulário de login com campos para e-mail e senha

Botão de acesso com validação básica

Seção de funcionalidades do sistema

A interface é totalmente responsiva, adaptando-se a diferentes tamanhos de tela, e mantém o visual azul do sistema original.

Conclusão A migração do sistema desktop para a versão web representa um avanço significativo na acessibilidade e usabilidade do sistema de controle de atendimentos da ONG Mãe Águia. A utilização do Bootstrap 5 permitiu desenvolver uma interface moderna e responsiva em tempo limitado. Como próximos passos, planeja-se a implementação completa das funcionalidades de registro de atendimentos e geração de relatórios, seguida de testes de usabilidade com os colaboradores.

Referências MARCOTTE, Ethan. Web Design Responsivo. Uma lista à parte, 2011.

OTAN. Documentação do Bootstrap 5. 2021. Disponível em: https://getbootstrap.com/docs/5.0/getting-started/introduction/

SILVA, João. Desenvolvimento Web Moderno. Editora Tecnologia, 2022.
