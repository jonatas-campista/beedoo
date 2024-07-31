# beedoo

# Requisitos para Cadastro e Visualização de Cursos
### Cadastro de Novos Cursos
Como um administrador da plataforma, eu quero poder cadastrar novos cursos, para que eu possa oferecer novos conteúdos para os usuários.

### Critérios de Aceitação:
###### * Formulário de Cadastro de Curso:
* Deve haver um formulário disponível para cadastrar novos cursos.
* O formulário deve conter os seguintes campos obrigatórios:
* Nome do curso
* Descrição do curso
* Instrutor
* URL da imagem de capa
* Data de início
* Data de fim
* Número de vagas
* Tipo de curso (presencial ou remoto)
* Endereço
* O formulário deve ter validação para garantir que todos os campos obrigatórios sejam preenchidos corretamente:
* Campos obrigatórios não podem estar vazios.
* Formatos de data e URL devem ser validados.
* O número de vagas deve ser um valor positivo.
* Após o cadastro:
* Deve ser exibida uma mensagem de confirmação informando que o curso foi cadastrado com sucesso.
* O curso recém-cadastrado deve aparecer na lista de cursos disponíveis.
# Visualização da Lista de Cursos
Como um usuário da plataforma, eu quero visualizar a lista de cursos disponíveis, para que eu possa escolher o curso que mais me interessa.

# Critérios de Aceitação:
### Página de Lista de Cursos:

* Deve haver uma página ou seção que liste todos os cursos disponíveis.
* A lista deve exibir informações básicas sobre cada curso, como:
* Nome do curso
* Descrição do curso
* Instrutor
* Data de início e fim
* Número de vagas restantes
* Tipo de curso (presencial ou remoto)
#### Funcionalidade de Exclusão de Cursos:

* Deve ser possível excluir cursos da plataforma.
* Após a exclusão, o curso deve ser removido da lista de cursos disponíveis.
* Deve ser exibida uma mensagem de confirmação após a exclusão do curso.
