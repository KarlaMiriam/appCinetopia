# appCinetopia
Cinetopia 🎥
![image](https://github.com/user-attachments/assets/4fc13de2-e2e4-4b41-aa19-8e72167c9c3c)
![image](https://github.com/user-attachments/assets/777cdc0f-4be9-46bf-ac53-e8d4c53ec0c6)


Cinetopia é um aplicativo iOS desenvolvido oferecendo uma experiência simples e elegante para descobrir e explorar conteúdos cinematográficos.

📱 Funcionalidades

	•	Interface Programática:
Desenvolvido inteiramente com View Code utilizando o framework UIKit, garantindo performance e flexibilidade na criação de layouts.
	•	Listagem de Filmes:
Exibição de filmes com detalhes como título, descrição e pôster, utilizando componentes como UITableView para organizar os dados em formato de tabela.
	•	Consumo de APIs REST:
Comunicação com APIs externas para obter informações sobre filmes. Implementação com URLSession e decodificação de dados JSON via JSONDecoder.
	•	Persistência Local:
Armazenamento de preferências e dados simples utilizando UserDefaults para melhorar a experiência do usuário.
	•	Arquitetura Limpa:
Organização do código seguindo a arquitetura MVP (Model-View-Presenter), garantindo modularidade, facilidade de manutenção e escalabilidade.

🛠️ Tecnologias Utilizadas

	•	Linguagem: Swift
	•	Frameworks: UIKit
	•	Persistência de Dados: UserDefaults
	•	Consumo de APIs: URLSession, JSONDecoder
	•	Gerenciador de Dependências: CocoaPods

📂 Estrutura do Projeto

	•	View: Camadas de interface programadas com UIKit (View Code).
	•	Presenter: Responsável pela lógica de apresentação, conectando os dados às views.
	•	Model: Estruturas de dados decodificadas diretamente das APIs externas.

🚀 Como Executar

	1.	Clone o repositório:
   - git clone https://github.com/seu-usuario/cinetopia.git
   - cd cinetopia

2.	Instale as dependências do projeto com CocoaPods:
	- pod install
3.	Abra o arquivo Cinetopia.xcworkspace no Xcode.
4.	Configure o simulador ou dispositivo físico e execute o projeto (⌘ + R).
