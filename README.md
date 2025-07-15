Flutter Starter Template

Este repositório é uma estrutura base para iniciar projetos Flutter de forma organizada, seguindo boas práticas de separação de responsabilidades, modularização e reutilização de código.

 Estrutura do projeto

lib/
 ├── core/         # Configurações globais (themes, rotas, cores)
 │   ├── theme/
 │   │   ├── app_theme.dart
 │   │   ├── colors.dart
 │   ├── routes/
 │   │   ├── app_routes.dart
 ├── features/     # Módulos por funcionalidade
 │   ├── home/
 │   │   ├── home_page.dart
 ├── shared/       # Widgets e utils reutilizáveis
 │   ├── widgets/
 │   │   ├── custom_button.dart
 │   ├── utils/
 │   │   ├── validators.dart
 ├── main.dart     # Ponto de entrada da aplicação

Tecnologias

Flutter

Dart

Como executar o projeto

Clone o repositório:

git clone https://github.com/gabriel-albqr/flutter_starter_template.git

Navegue até a pasta do projeto:

cd flutter_starter_template

Instale as dependências:

flutter pub get

Execute o app:

flutter run

Funcionalidades básicas incluídas

✅ Estrutura modular organizada✅ Tema centralizado com ThemeData✅ Widget customizado (CustomButton)✅ Utils para validação✅ Preparado para expansão com novas features

 Sobre

Este template foi criado para ajudar desenvolvedores a iniciarem projetos Flutter de forma limpa e organizada, com uma base sólida para evoluir para apps de qualquer tamanho.

👨Autor

Gabriel Gomes de Albuquerque SilvaLinkedIn | GitHub | 📧 gabriel.albqdev@outlook.com

“Código limpo é código que funciona.” – Robert C. Martin

