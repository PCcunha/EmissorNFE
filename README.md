# EmissorNFE - 3.10.86

Este projeto contem uma cópia executavel localmente do Emissor de Nota Fiscal Eletônica Gratuito desenvolvido pela Secretaria de Fazenda de São Paulo.

## Aviso!

Não há qualquer garantia que este projeto irá funcionar para você, e se ele não funcionar eu não prestarei nenhum tipo de suporte para tal. Use-o ao seu próprio risco!

## Sobre

O Emissor de Nota Fiscal Eletônica Gratuito desenvolvido pela Secretaria de Fazenda de São Paulo foi o primeiro emissor livre e gratuíto disponibilizado para a utilziação no brasil. Ele atende boa parte das necessidades de pequenas a grandes empresas. Funciona muito bem mais infelizmente, conforme a nota abaixo divulgada no site do emissor, o seu desenvolvimento será encerrado.

>Informamos que, a partir de 01/01/2017, o emissor gratuito da NF-e (versão 3.10) será descontinuado e nova versão não será desenvolvida. 
>
>A partir dessa data não será mais possível fazer download do aplicativo, porém os usuários que tiverem o aplicativo instalado em seus computadores poderão continuar utilizando-o até que novas atualizações das regras de validação da NFe impeçam o seu correto funcionamento.
*Informação obtida em 28/12/2017 do site [do emissor NFE](http://www.emissornfe.fazenda.sp.gov.br/)


Como o emissor é distribuido sobre a platavorma JAVA JNLP, assim que a sefaz tira-lo do ar em 1/1/2017 provavelmente o mesmo irá parar de funcionar.

## Objetivos
  - Possibilitar a execução local sem a necessidade de utilziação de internet ou consulta ao site da SRFSP após 01/01/2017.
  - Manter uma cópia para a posteridade, assim as pessoas que possuem notas geradas pelo programa ainda consigam utiliza-lo para consulta.
  - Postergar o seu uso até que o mesmo pare de funcionar em função de alterações na legislação.

## Como?

De forma bem resumida, baixando-se todos os arquivos de bibliotecas necessárias ao seu funcionamento e executando-se diretamente pelo java.

## Instalação e uso

É necessário que possua o Java instalado e atualizado, e com o seu diretório de binários disponível no PATH do sistema. Teste executanto o comando java em um terminal (prompt de comando)

Para usuários Linux, infelizmente é necessário utilizar-se do usuário root na execução. Ainda não verifiquei exatamente o por que desta necessidade.

Baixe o conteudo deste repositório para uma pasta em seu computador pelo link de [Download](https://github.com/pcunha-lab/EmissorNFE/archive/master.zip)

execute o arquivo .bat(windows) ou .sh(linux) e o programa deve abrir-se.

# Banco de dados

O banco de dados do programa inicialmente é criado na pasta c:\database (windows ou /database (linux), então se for mudar de computador, você terá que copiar esta pasta juntamente com o programa para um novo computador.

# Licença

O Emissor de NFE da Sefaz-SP tanto em seu website quanto no próprio software não possui nenhuma menção a sua licença de software. Mesmo possuindo em seu software a utilização de diversas bibliotecas de código aberto. 

