![](https://avatars.githubusercontent.com/u/9659273?v=3&s=25) Brasil.js
===================

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/brasil-js/brasil-js.github.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

*Este é um projeto em construção, mantido pela comunidade. Faça um pull-request e torne-se um contribuidor!*

O Brasil.js é um conjunto de módulos JavaScript com ferramentas para facilitar a vida do desenvolvedor brasileiro. A maioria dos módulos também roda no browser. Visite a página de cada projeto clicando no seu respectivo link abaixo:

- **[Boleto Bancário](https://github.com/brasil-js/boletobancario)**   
     Gerador de boletos bancários dos principais bancos do Brasil em `.pdf`, `.png` e `.html` diretamente no node.js ou no browser. Inspirado no [Caellum Stella](https://github.com/caelum/caelum-stella). Visite o site de demonstração e [emita um boleto de teste!](http://boletobancar.io/) ou veja um [boleto de exemplo](https://s3-sa-east-1.amazonaws.com/gammasoft/open-source/brasil/boleto.pdf)  
    <sub>Apenas banco itaú e formato `.pdf` implementados no node.js até agora</sub>

- **[Nota Fiscal Eletrônica](https://github.com/brasil-js/notafiscaleletronica)**  
     Gerador de notas fiscais eletrônicas. Este módulo tem a finalidade de montar o arquivo `.xml` de uma NFe a partir de uma API e um estrutura de dados simples e intuitiva, além de assinar digitalmente e fazer a comunicação com os variados webservices da receita federal.  
     <sub>Nada implementado até agora</sub>

- **[DANFE](https://github.com/brasil-js/danfe)**  
     Gerador de DANFES em `.pdf`, `.png` e `.html` diretamente no node.js ou no browser! Este módulo cuida apenas da geração da DANFE. Para emissão de NFe verifique o módulo NFE. Veja uma [DANFE de exemplo!](https://s3-sa-east-1.amazonaws.com/gammasoft/open-source/brasil/danfe.pdf) 
     <sub>Apenas formato `.pdf` implementado no node.js até agora</sub>

- **[Consultas](https://github.com/brasil-js/consultas)**  
     Faça consultas diretamente na Receita Federal, ao SEFAZ, ao SIMPLES e ao Sintegra de cada estado para obter informações disponibilizadas publicamente na internet sobre um CNPJ/CPF. [Visite o site de demonstração e faça uma consulta!](http://brasil.gammasoft.com.br/)!    
     <sub>Apenas consulta de CNPJ na receita federal e na sefaz do GO e DF implementadas até agora</sub>

- **[Dados](https://github.com/brasil-js/dados)**  
     Um repositório de dados públicos que podem ser úteis para a construção do seu software que lida com NFe ou similares. Por exemplo: relação de CNAES, CFOPS, tabela de municípios do IBGE completa, dentre outros.  

- **[Paranauê](https://github.com/brasil-js/paranaue)**  
      Um módulo para formatar, validar e remover a máscara dos diferentes documentos e números comuns no brasil:   
      - CNPJ e CPF (registro nacional)  
      - Linha digitável do boleto bancário
      - Título de eleitor (valida e retorna o estado onde o titulo foi emitido)
      - PIS/PASEP (NIT)
      - Telefone (a validação inclui a verificação do DDD válido)
      - CEP
      - Número e Chave de Acesso da NFe
      - Data (ex.: 21/12/2012)
      - Hora (ex.: 14:23:23 ou 10:23)
      - Data e Hora (ex.: 21/12/2012 10:23)
      - Dinheiro (ex.: formata um número em R$ 1.234,56)  
      - Número (ex.: 1.234,56)

- **[Inscrição Estadual](https://github.com/brasil-js/inscricaoestadual)**  
     Este módulo implementa a validação de inscrição estadual de todos os estados brasileiros de acordo com os algoritmos descritos no [manual do SINTEGRA](http://www.sintegra.gov.br/insc_est.html).

------

Todos os repositórios da organização [Brasil.js](https://github.com/brasil-js) estão disponibilizados sobre a licença MIT. Utilize gratuitamente.


### Licença MIT

The MIT License (MIT)

Copyright (c) 2015 Brasil.js Developers

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

![Licença MIT](http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png)
      
