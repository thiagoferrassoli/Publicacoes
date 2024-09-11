# SysEurus Monitor

Este repositório contém apenas os **releases** (arquivos binários) da aplicação **[SysEurus Monitor]**. O código-fonte deste projeto não está disponível publicamente. No entanto, você pode baixar e utilizar a versão mais recente da aplicação a partir dos releases fornecidos abaixo.

## Releases

Para baixar a última versão da aplicação, vá para a seção de [Releases](https://github.com/SEU_USUARIO/SEU_REPOSITORIO/releases](https://github.com/thiagoferrassoli/Publicacoes/releases)) deste repositório.

### Instruções de Uso

1. Baixe o arquivo binário ou executável da versão mais recente na aba [Releases](https://github.com/SEU_USUARIO/SEU_REPOSITORIO/releases](https://github.com/thiagoferrassoli/Publicacoes/releases)).
2. Extraia e execute o arquivo SETUP.EXE em sua máquina.
3. Siga as instruções de instalação ou execução de acordo com o sistema operacional.

### Funcionalidades

- **Sincronização temporizada de clientes**: Automatiza a atualização dos dados dos clientes entre o ERP e o CRM em intervalos definidos, garantindo que ambos os sistemas estejam sempre alinhados.
- **Verificação de cadastros de clientes**: Compara os registros de clientes no ERP e no CRM para identificar e corrigir possíveis falsos positivos, melhorando a qualidade da sincronização.
- **Exportação temporizada de vendas**: Facilita a exportação de dados de vendas do ERP para o CRM de forma automatizada e programada, evitando discrepâncias entre os sistemas.
- **Comparativo de vendas ERP x CRM**: Gera relatórios comparativos das vendas registradas em ambos os sistemas, permitindo a identificação de divergências e uma análise detalhada das transações.
- **Reprocessamento de vendas**: Implementa a re-inserção automática de transações na fila de sincronização, permitindo que vendas falhas sejam reprocessadas sem intervenção manual.
- **Relação de arquivos XML enviados à API do CRM**: Documenta todos os arquivos XML gerados e enviados ao CRM, proporcionando uma rastreabilidade clara das transações realizadas.
- **Relação de XML de retorno da API**: Armazena e organiza as respostas da API do CRM após o recebimento de cada venda, facilitando o acompanhamento e a auditoria dos dados enviados.

### Requisitos

- **Sistema Operacional**: Windows.
- **Dependências**:
  - .NET Framework 4.7.2 ou superior
  - Mecanismo de Banco de Dados do Microsoft Access 2016 Redistribuível [aqui](https://www.microsoft.com/pt-BR/download/details.aspx?id=54920).
