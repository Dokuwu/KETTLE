### Projeto Integração de Sistemas de Informação numero 01
## Autor
Fabio José Silva Miranda, aluno nº 26003

## Descrição dos Ficheiros

# flows.json: 
Este ficheiro contém o fluxo do Node-RED.

# isi_26003.bak: 
Este ficheiro é a base de dados em SQL Server.

# GuardarDadosLocal.ktr: 
Este ficheiro é uma transformação que tem como objetivo guardar dados numa base de dados sobre um local especifico.

# GuardarDadosPrevisao.ktr: 
Este ficheiro é uma transformação do Pentaho Kettle que armazena previsões meteorológicas numa base de dados e num xml.

# VariavelAmbienteHTML.ktr: 
Este ficheiro é uma transformação do Pentaho Kettle que manipula variáveis de ambiente para gerar conteúdo HTML. Ele lê um arquivo HTML, agrupa os dados e define variáveis que serão utilizadas em outras partes do processo.

# EnviarPrevisaoEmail.kjb: 
Este ficheiro é um job do Pentaho Kettle que orquestra a execução das transformações anteriores, incluindo o envio de previsões meteorológicas por e-mail.

# localPrevisão.json: 
Este ficheiro é um arquivo JSON no qual o utilizador digita o nome do local desejado.

# previsao.xsl: 
Este ficheiro é um arquivo XSL que define como transformar documentos XML em HTML.

# weather-type-classe.json: 
Este ficheiro é provido do IPMA que contém a descrição temporal das previsões meteorológicas perante um id.

# previsao.html: 
Este ficheiro é um documento HTML que contém a apresentação formatada das previsões meteorológicas.

# previsao.xml: 
Este ficheiro é um documento XML que armazena as previsões meteorológicas resultantes da transformação GuardarDadosPrevisao.krt. 

# Video_Demonstracao.mp4: 
Este ficheiro é um vídeo que demonstra o funcionamento da aplicação.

# TP01_26003_doc.pdf: 
Este ficheiro é o relatorio realizado para este trabalho pratico.
