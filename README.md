Formulário de Inscrição Este documento descreve a estrutura e o funcionamento do formulário de inscrição desenvolvido para o projeto. O formulário tem o objetivo de coletar informações dos usuários interessados em se inscrever em determinado serviço ou evento.

HTML Estrutura do Documento O arquivo HTML (“index.html”) contém a estrutura básica do formulário de inscrição, incluindo campos para nome, email, CPF, telefone, endereço e documentos.

Tags

: Define o conjunto de caracteres utilizado no documento como UTF-8.

: Define a escala inicial e a largura da viewport para o tamanho do dispositivo.

: Importa o arquivo CSS responsável pelo estilo do formulário. : Importa o arquivo CSS do pacote de ícones Font Awesome. <title>Formulário</title>: Define o título da página como "Formulário".
Corpo do Documento

: Define o formulário de inscrição com o id "formulario".
Inscreva-se
: Título do formulário.
Campos de entrada para nome, email, CPF, telefone, CEP, estado, cidade, rua, documento de identidade e comprovante.

*Atenção: Todos os dados acima são obrigatórios

: Aviso sobre a obrigatoriedade dos campos.
Botões para cancelar e enviar o formulário.

Scripts

<script src="assets/js/index.js"></script>: Importa o arquivo JavaScript responsável pela validação e envio do formulário.
CSS

Estilo do Formulário O arquivo CSS (“style.css”) contém estilos para o formulário de inscrição, incluindo cores, fontes, tamanhos e posicionamento dos elementos.

Definição de Variáveis

--font: Define a fonte padrão como "Roboto, sans-serif".

--background-input: Define a cor de fundo dos campos de entrada como "#fffaf2".

--border-color: Define a cor da borda como "#cacaca".

--background-gradient: Define um gradiente de fundo para o corpo do documento.

--btn-orange: Define a cor laranja como "#ff6a0086".

Estilos Gerais

Reset de margens, preenchimento e caixa-modelo para todos os elementos (*).

Corpo do documento com fundo degradê e imagem de fundo.

Formulário com largura máxima de 500px, fundo branco, sombra e bordas arredondadas.

Título do formulário centralizado e com margem inferior.

Estilos para campos de entrada, incluindo largura, cor de fundo, borda e borda-radius.

Responsividade Estilos para dispositivos com largura máxima de 920px, ajustando o padding e o espaçamento dos elementos.

Conclusão O formulário de inscrição foi desenvolvido de forma a proporcionar uma experiência de usuário agradável e intuitiva. A estrutura do HTML e o estilo do CSS foram cuidadosamente elaborados para garantir a funcionalidade e a estética do formulário. O arquivo JavaScript (index.js) é responsável pela validação e envio dos dados do formulário, garantindo a integridade das informações fornecidas pelos usuários.
