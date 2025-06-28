# IASearch_Index

# Descrição do Desafio
Aplicar técnicas de organização e pesquisa de documentos por meio da ingestão de dados e indexação utilizando ferramentas de inteligência artificial. Durante as aulas, foram abordados três passos principais: ingestão de conteúdo para IA, criação de índices inteligentes e exploração prática dos dados organizados. O foco está em desenvolver uma compreensão sólida sobre como essas ferramentas podem ser utilizadas para minerar e extrair conhecimento de grandes volumes de informação. Como entregável, espera-se um repositório estruturado contendo registros das etapas realizadas e insights obtidos ao longo da prática.

# Objetivos de Aprendizagem 
- Aplicar os conceitos aprendidos em um ambiente prático;  
- Documentar processos técnicos de forma clara e estruturada;   
- Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica.   

# Links
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

# Desafio
Ao procurar Pesquisa de IA, ou IA search seremos direcionados a esta URL: https://portal.azure.com/#view/Microsoft_Azure_ProjectOxford/CognitiveServicesHub/~/CognitiveSearch.  
Embora tenha feito a conta na azure e feito o passo a passo, não encontrei os arquivos disponibilizados de reviews fakes.  
Será necessário a criação em 3 partes. A primeira é necessário criar o recurso de pesquisa de IA, no link acima. Importante ter em mente o grupo de recurso que será criado, pois para as próximas partes iso será importante.    
A segunda parte sendo a criação da máquina para pesquisa de IA, onde é necessário criar um recurso de inteligência artificial em Criar um recurso> IA + machine learning >Azure IA services.  
Após esta criação de recurso é necessária a terceira - a conta de armazenamento. https://portal.azure.com/#browse/Microsoft.Storage%2FStorageAccounts. Lembrando que o resource group deve ser o mesmo dos dois acima. Aqui será utilizado para armazenamento dos dados que serão tratados, podendo estes serem separados em containers, files, queues e tabelas.  Para o teste em questão será necessário quebrar um regra do storage account. A regra de acessos anônimos para as informações (Allow Blolb anonymous acess - Enabled). No caso mostrado seria necessário descompactar a pasta com as reviews fornecidas, ir em container e fazer o upload das informações.  

Após a criação dos 3 recursos, o de mecanismo de busca, um de inteligência artificial e o storage account. No mecanismo de busca podemos importar os dados do storage account. Ali no search explorer é possível consultar a base de dados dado a pesquisa que se deseja. ex: search=locations:'Chicago'; search=sentiment:'negative'.  

Conclusão: Foi criado um serviço de inteligência artificial, fazer o link com a automação direcionando ao repositório. Utilizando um serviço de busca, um storage account e um serviço de automação.


