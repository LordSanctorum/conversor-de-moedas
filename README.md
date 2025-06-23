Conversor de Moedas em Java
https://img.shields.io/badge/Java-17%252B-blue
https://img.shields.io/badge/License-MIT-green

Um conversor de moedas que obtém taxas de câmbio em tempo real através de uma API pública e permite conversões entre diversas moedas.

📋 Funcionalidades
✅ Conversão entre 6 pares de moedas pré-definidos

🔄 Conversão personalizada entre quaisquer moedas suportadas

⏱️ Taxas de câmbio atualizadas em tempo real

💰 Formatação adequada de valores monetários

🖥️ Interface simples via console

📦 Pré-requisitos
Java JDK 17 ou superior

Conexão com a internet (para acessar a API)

Chave de API gratuita do ExchangeRate-API

🚀 Como executar
Obtenha uma chave de API:

Acesse ExchangeRate-API e cadastre-se

Obtenha sua chave gratuita (permite 1,500 requisições/mês)

Configure o projeto:

bash
git clone https://github.com/seu-usuario/conversor-moedas-java.git
cd conversor-moedas-java
Edite o arquivo:

Abra ConversorMoedas.java

Substitua sua_chave_api pela chave obtida

Compile e execute:

bash
javac ConversorMoedas.java
java ConversorMoedas
🎮 Como usar
Ao iniciar o programa, você verá um menu com opções de conversão

Selecione uma opção de 1 a 6 para conversões pré-definidas

Para conversão personalizada, selecione a opção 7

Digite o valor a ser convertido quando solicitado

O resultado será exibido formatado com 2 casas decimais

Selecione a opção 8 para sair do programa

📊 Moedas suportadas
O programa suporta todas as moedas disponíveis na API, incluindo:

USD (Dólar Americano)

BRL (Real Brasileiro)

EUR (Euro)

GBP (Libra Esterlina)

JPY (Iene Japonês)

CNY (Yuan Chinês)

E muitas outras (consulte a API para lista completa)

🛠️ Estrutura do código
plaintext
ConversorMoedas/
└── ConversorMoedas.java
Principais componentes:

obterTaxasCambio(): Faz requisição à API e retorna as taxas

exibirMenu(): Controla a interface com o usuário

converterMoeda(): Realiza a conversão entre duas moedas

converterMoedaPersonalizada(): Permite conversão entre quaisquer moedas

📄 Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes.

🤝 Contribuição
Contribuições são bem-vindas! Siga estes passos:

Faça um fork do projeto

Crie uma branch para sua feature (git checkout -b feature/incrivel)

Commit suas mudanças (git commit -m 'Adiciona feature incrível')

Push para a branch (git push origin feature/incrivel)

Abra um Pull Request
