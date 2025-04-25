Sistema de Gerenciamento de Colaboradores AstroTech
Visão Geral do Projeto
O Sistema de Gerenciamento de Colaboradores AstroTech é uma aplicação web simples projetada para gerenciar registros de trabalho de colaboradores da AstroTech. Ele permite que os usuários registrem detalhes dos colaboradores, incluindo nome, rota atribuída, horário de início e término, e observações adicionais. O sistema armazena os dados em um array JavaScript (banco de dados simulado) e oferece a funcionalidade de visualizar todos os registros salvos. Recursos futuros, como o cálculo de horas trabalhadas e a detecção de horas extras, estão planejados, mas ainda não foram implementados.
Funcionalidades

Adicionar Registros: Insira os detalhes do colaborador por meio de um formulário (nome, rota, horário de início, horário de término, observações) e salve-os.
Visualizar Registros: Exiba uma lista de todos os registros salvos com detalhes.
Design Responsivo: Construído com Tailwind CSS para uma interface limpa e amigável.
Recursos Futuros (planejados):
Calcular horas trabalhadas com base nos horários de início e término.
Identificar horas extras.



Tecnologias Utilizadas

HTML: Estrutura da página web.
JavaScript: Gerencia o envio de formulários, armazenamento de dados e exibição de registros.
Tailwind CSS: Estilização para uma interface moderna e responsiva.

Primeiros Passos
Pré-requisitos

Um navegador web moderno (por exemplo, Chrome, Firefox, Edge).
Não são necessários softwares ou dependências adicionais, pois a aplicação roda inteiramente no navegador.

Instalação

Clone ou baixe o repositório para sua máquina local.
Abra o arquivo index.html em um navegador web.
Comece a usar a aplicação preenchendo o formulário para adicionar registros ou clicando em "Ver Registros" para visualizar os registros salvos.

Uso

Adicionando um Registro:
Preencha os campos do formulário: Nome, Rota, Horário de Início, Horário de Término e Observações (opcional).
Clique no botão "Salvar" para armazenar o registro.
Um alerta de confirmação aparecerá, e o formulário será limpo.


Visualizando Registros:
Clique no botão "Ver Registros" para exibir todos os registros salvos.
Se não houver registros, uma mensagem será exibida.


Os registros são armazenados em memória (array JavaScript) e serão perdidos ao recarregar a página.

Autores

Guilherme Schuck dos Santos
Maykou Wathier
Deoclecio Spielmann

Melhorias Futuras

Implementar o cálculo de horas trabalhadas com base nos horários de início e término.
Adicionar lógica para detecção de horas extras.
Substituir o array em memória por um banco de dados persistente (por exemplo, SQLite, MongoDB).
Adicionar validação de entrada para formatos de horário e evitar registros duplicados.
Melhorar a interface com recursos avançados, como filtragem ou ordenação de registros.

Licença
Este projeto é de código aberto e está disponível sob a Licença MIT.
