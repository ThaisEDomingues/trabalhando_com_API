# trabalhando_com_API

🌦️ Consulta de Previsão do Tempo com API Open-MeteoEste projeto consiste em um script Python que realiza requisições em tempo real para obter dados meteorológicos de qualquer coordenada geográfica do planeta. Ele utiliza a biblioteca Requests para interagir com a API pública da Open-Meteo. 

🚀 Funcionalidades 
O script executa as seguintes etapas:Entrada de Coordenadas: O usuário informa a latitude e a longitude desejadas.  
Configuração de Parâmetros: Define as chaves necessárias para a API, como localização e a solicitação do clima atual (current_weather).  Requisição HTTP: Utiliza o método GET para enviar os parâmetros ao endpoint da API.  Validação de Status: Verifica se a comunicação foi bem-sucedida através do código de status 200.  Processamento de JSON: Converte a resposta bruta em um formato de dicionário Python (JSON) para extrair informações específicas.  Exibição de Resultados: Mostra a temperatura em graus Celsius e a velocidade do vento em km/h. 

🧠 Conceitos e Métodos UtilizadosAPI (Application Programming Interface): 
Interface que permite a comunicação entre o script e o servidor meteorológico.  Biblioteca requests: Ferramenta essencial para realizar requisições HTTP em Python.  Status Codes: Uso de códigos de resposta como 200 (Sucesso) e 404 (Não encontrado) para tratamento de erros.  JSON: Formato de troca de dados leve e fácil de ler, utilizado para receber as informações da API.  

🛠️ Tecnologias UtilizadasPython 3  Biblioteca requests  API Open-Meteo  

📝 Exemplo de UsoAo executar o programa e inserir as coordenadas, você terá um retorno semelhante a este:
Plaintext
informe a latitude desejada: 2
informe a longitude desejada: 2
a temperatura é 28.8 °C
a velocidade do vento é 14.4 km/h

📂 Como ExecutarCertifique-se de ter o Python instalado.
Instale a biblioteca necessária:Bashpip install requests
Execute o script e insira a latitude e longitude da região que deseja consultar.  
