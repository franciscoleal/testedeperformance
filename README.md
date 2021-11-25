# teste de performance
Um teste rápido, simples para aplicar a teoria aprendida no curso a fim de mostrar o resultado de um teste feito via linha de comando.
Foi utilizado o seguinte comando para criar de uma única vez o arquivo de resultado, para com ele poder gerar o dashboard com as informações pertinentes ao teste.
# Linha de comando <br>
Acesse a pasta onde se encontra o arquivo jmx <br>
C:\exemplo <br>
Acesse o executável do JMeter <br>
C:\exemplo: C:\jmeter\bin\jmeter.bat <br>
Essa opção diz para o JMeter ser executado apenas por linha de comando (sem a interface gráfica)  <br>
C:\exemplo: C:\jmeter\bin\jmeter.bat -n <br>
Para carregar o arquivo jmx usa-se o parametro -t e o nome do arquivo, Seu script plano de teste (arquivo JMX) <br>
C:\exemplo: C:\jmeter\bin\jmeter.bat -n -t Livros.jmx <br>
Para que possa gerar o arquivo jtl ou log usa-se o parametro -l seguido do nome do arquivo, Arquivo log de resultados do seu teste (arquivo JTL) <br>
C:\exemplo: C:\jmeter\bin\jmeter.bat -n -t Livros.jmx -l resultado.log <br>
- e >> O paramentro -e serve para geração do dashboard <br>
C:\exemplo: C:\jmeter\bin\jmeter.bat -n -t Livros.jmx -l resultado.log -e <br>
-o >> Pasta de saída onde será gerado o dashboard. Pasta não pode existir ou deve estar vazia <br>
C:\exemplo: C:\jmeter\bin\jmeter.bat -n -t Livros.jmx -l resultado.log -e -o dashboard <br>
