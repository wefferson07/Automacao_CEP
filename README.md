# Automacao_CEP

# Descrição

1-Clique no link, faça o download da última versão estável e instale o Ruby na máquina: https://rubyinstaller.org/downloads/.

2-Instale o bundler: gem install bundler.

3-Clone o projeto em uma pasta do PC/Notebook de sua preferência: git clone https://github.com/wefferson07/Automacao_CEP.

4-Navegue até o diretório do projeto.

5-Execute o comando no terminal: bundle install.

6-Execute o comando no terminal: cucumber (no windows) ou bundle exec cucumber(no linux/Mac).

7-Para executar somente cenários especificos, use o comando cucumber -t + a tag do cenário. Ex.: cucumber -t @cep_invalido.

# Objetivo da automação:
# Regras:
Implementar os testes com Cucumber + Ruby
Enviar o teste em um repositório público do Github ou similar
3 dias para resolver o exercício
Teste:
Criar uma funcionalidade para consultar os dados de um endereço a partir de um CEP.

# Cenários:

2.1. Criar um cenário de sucesso na consulta, printando o código do IBGE do endereço no stdout.

2.2. Criar um cenário passando um CEP inválido
# Dicas:
Utilizar a API https://viacep.com.br/ws/01001000/json/ para consulta; Gem HTTParty pode ser uma ajuda incrível para trabalhar com as requisições HTTP
