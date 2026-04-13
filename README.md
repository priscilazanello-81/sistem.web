# sistem.web

SISKTEMATIZAÇÃO WEB

INTRODUÇÃO

A página da Clínica Bem Viver é um site institucional estático, desenvolvido
inteiramente com HTML5 e CSS3, em um único arquivo. O objetivo da página é
apresentar a clínica, seus serviços, equipe e permitir que o usuário agende
uma consulta por meio de um formulário de contato.

ESTRUTURA GERAL

O arquivo é dividido em duas grandes partes: o cabeçalho, chamado de head,
e o corpo da página, chamado de body. No head estão todas as configurações
iniciais, como a definição do idioma português, a codificação de caracteres
UTF-8, que garante o correto funcionamento de acentos e caracteres especiais,
o título que aparece na aba do navegador, e a importação das fontes do
Google Fonts. Foram utilizadas duas fontes: a Lora, uma fonte serifada usada
nos títulos, e a Inter, uma fonte sem serifa usada nos textos do corpo.

ESTILO VISUAL — CSS

Todo o estilo da página está escrito diretamente no head, dentro de uma tag
chamada style. O CSS começa com um reset global, que zera as margens e
espaçamentos padrão do navegador, garantindo consistência visual.

A cor principal da identidade visual é um verde escuro, utilizado na
navegação, nos títulos, nos botões e no rodapé. Os textos de apoio aparecem
em tons de cinza, e os cargos da equipe são destacados em um tom de laranja
terroso, criando um contraste elegante.

Para os layouts, foram utilizados dois recursos modernos do CSS: o Flexbox
e o Grid. O Flexbox organiza a barra de navegação, colocando o logo à
esquerda e os links à direita. Já o Grid é utilizado nas seções de serviços,
sobre e equipe, organizando os elementos em colunas fixas de forma limpa
e alinhada.

SEÇÕES DA PÁGINA

A página é composta por sete seções principais.

A primeira é a navegação, que contém o logo da clínica à esquerda e, à
direita, links de acesso rápido para as seções de Serviços e Equipe, além
de um botão de destaque para agendamento.

A segunda é o hero, que é a seção principal de boas-vindas. Ela apresenta
o título da página, um parágrafo de apresentação, um botão de chamada para
ação e uma imagem da clínica.

A terceira é a seção de Serviços, que exibe seis especialidades disponíveis:
Clínica Geral, Saúde Mental, Nutrição, Fisioterapia, Odontologia e
Laboratório. Cada serviço é apresentado em um card com um ícone, título
e breve descrição.

A quarta seção é o Sobre, que apresenta a clínica em um layout de duas
colunas: duas fotos à esquerda, com bordas arredondadas assimétricas para
dar dinamismo visual, e um texto de apresentação à direita, informando que
a clínica foi fundada em 2010.

A quinta seção é a da Equipe, com quatro profissionais apresentados em cards
individuais, cada um com foto em formato circular, nome, cargo e uma breve
biografia.

A sexta seção é o formulário de Contato, onde o usuário pode preencher seu
nome, e-mail, cidade, estado e uma mensagem opcional para agendar uma
consulta. Os campos recebem um destaque verde na borda ao serem clicados,
melhorando a experiência visual do preenchimento.

Por fim, o rodapé encerra a página com o copyright, a localização da clínica
em Brasília, Distrito Federal, e o número de telefone.

RECURSOS EXTERNOS UTILIZADOS

A página utiliza três recursos externos. O primeiro é o Google Fonts, para
importar as fontes Lora e Inter. O segundo é o Unsplash, de onde vêm as
fotos utilizadas no hero e na seção Sobre. O terceiro é o site xsgames,
que fornece os avatares dos membros da equipe.

CONSIDERAÇÕES FINAIS

Por se tratar de uma página desenvolvida exclusivamente para visualização
em desktop, a linha de código responsável pela adaptação em dispositivos
móveis, chamada de meta viewport, foi removida. Da mesma forma, os grids
foram configurados com colunas fixas, sem o uso de auto-fit, que é um
recurso voltado para layouts responsivos.

O resultado é uma página limpa, organizada e visualmente coerente, que
cumpre seu objetivo de apresentar a Clínica Bem Viver de forma profissional
e acolhedora.
Assim foi possível modernizaar a clínica e apresentá-la da melhor forma, melhorando 
a experiência dos pacientes.

======================================================
Clínica Bem Viver — Brasília, DF | (61) 3344-5566
© 2025 — Projeto acadêmico de Desenvolvimento Web
