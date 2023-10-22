## Sobre o projeto
Projeto "Build a Survey Form" do freeCodeCamp. 

## Tags utilizadas comumente em formulários
* form
  - method = "GET/POST"
  - onsubmit = "entenderei quando estudar javascript"
  - action = "localparaondeosdadosseraoenviados.com"
  - autocomplete = "on/off"
    <br/>
    *O GET é utilizado para acessar um recurso, uma informação, não para enviar dados como dados de um formulário, por exemplo, isso é responsabilidade do POST.*

* fieldset
  <br/>
    *Abriga o formulário, envolvendo com uma borda.*

* embed
  <br/>
   *Insere uma mídia externa no site, porém não possui valor semântico. Devido a isso, vale mais a pena usar uma tag video ou com algum 
    valor.*
  
* iframe
  <br/>  
  *Permite incorporar outra página em seu site, como YT ou maps. Utilizando iframe, as views em um vídeo contam para o site incorporado,   
  não para o seu site.*
  
* input
  - type = "text/number/password/button/range/color/email/url/date/week/month/checkbox/radio/file/search"
  - name = "nome/idade/senha/botao/slider/seletor_cores/email/url/data/semana/mes/caixa_seletora/botao_redondo/arquivo/busca"
    <br/>
    ### Se for type number
  - min = "0"
  - max = "38"
  - step = "5"
    <br/>
    ### Se for type range
  - min = "valorminimoaserinserido"
  - max = "valormaximoquealcança"
  - value = "valorinicial"
    <br/>
    ### Se for type checkbox ou radio
  - disabled // Desabilita o campo
  - name = "valores[]"
  - value = "enviado_ao_server"
  - value = "value2"
  - value = "value3"
    <br/>
    Como é enviado ao servidor: $valores[enviado_ao_server, value2, value 3]
    <br/><br/>
    *Checkbox permite selecionar mais de um campo, radio apenas um.*
    
* button
  - type = "submit/reset"

* textarea
  - rows = "n_de_linhas"
  - cols = "n_de_colunas"
    
* label
  
* select
  - multiple //Selecionar varios itens da lista
    * option
      - selected
      - value
