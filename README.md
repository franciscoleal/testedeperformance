# teste de performance
Um teste rápido, simples para aplicar a teoria aprendida no curso a fim de mostrar o resultado de um teste feito via linha de comando.
Foi utilizado o seguinte comando para criar de uma única vez o arquivo de resultado, para com ele poder gerar o dashboard com as informações pertinentes ao teste.
# Linha de comando
Acesse a pasta onde se encontra o arquivo jmx \n
C:\exemplo \n
Acesse o executável do JMeter
C:\exemplo: C:\jmeter\bin\jmeter.bat
Essa opção diz para o JMeter ser executado apenas por linha de comando (sem a interface gráfica) 
C:\exemplo: C:\jmeter\bin\jmeter.bat -n
Para carregar o arquivo jmx usa-se o parametro -t e o nome do arquivo, Seu script plano de teste (arquivo JMX) 
C:\exemplo: C:\jmeter\bin\jmeter.bat -n -t Livros.jmx
Para que possa gerar o arquivo jtl ou log usa-se o parametro -l seguido do nome do arquivo, Arquivo log de resultados do seu teste (arquivo JTL) 
C:\exemplo: C:\jmeter\bin\jmeter.bat -n -t Livros.jmx -l resultado.log
O paramentro -e serve para criação da pasta 
C:\exemplo: C:\jmeter\bin\jmeter.bat -n -t Livros.jmx -l resultado.log -e
Pasta de saída onde será gerado o dashboard. Pasta não pode existir ou deve estar vazia
C:\exemplo: C:\jmeter\bin\jmeter.bat -n -t Livros.jmx -l resultado.log -e -o dashboard
