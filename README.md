# AtivoOperante
Seja um cidadão atento aos problemas do dia a dia. Avise e denuncie de forma eficiente e rápida os problemas que encontrar na sua comunidade. Instale o app Ativo e Operante!

O sistema é composto por um App Android e um Sistema Web capaz de oferecer uma ferramenta ao cidadão que deseja avisar ou denunciar aos orgãos competentes sobre problemas na cidade, como buracos na rua, abandono de animais, poda ou corte de árvores, problemas no trânsito, enfim qualquer contratempo que pode afetar o dia a dia do cidadão.

O App Android permite o acesso de pessoas autenticadas e assim fornece o módulo de denúncia, na qual o usuário conseguirá registrar uma denúncia informando um título, uma descrição, o nível de urgência, o orgão competente e o tipo de problema. Após preenchida a denúnia, ela é enviada ao Sistema Web e recebida por uma API Rest.

O Sistema Web foi desenvolvido em Spring Boot e além dos serviços (APIs) para interagir com o app, ele oferece um módulo para o responsável pelo sistema cadastrar os orgãos responsáveis e os tipos de de problema, além de possuir uma interface que permite listar e visualizar todas as denúncias, com opções para deletar e alterar as mesmas.
