# 📱 Flutter Todo App

Um aplicativo moderno e funcional de gerenciamento de tarefas desenvolvido em Flutter, com interface elegante e recursos avançados.

## 🚀 Funcionalidades

- ✅ **Gerenciamento Completo de Tarefas**: Criar, editar, excluir e marcar como concluída
- 🏷️ **Categorização**: Organize tarefas por categorias (Trabalho, Pessoal, Compras, Saúde, Estudos, Outros)
- 🎯 **Níveis de Prioridade**: Baixa, Média e Alta com indicadores visuais coloridos
- 📅 **Datas de Vencimento**: Defina prazos para suas tarefas
- 🔍 **Filtros Inteligentes**: Visualize todas, pendentes, concluídas ou tarefas do dia
- 💾 **Persistência Local**: Dados salvos automaticamente no dispositivo
- 🎨 **Design Moderno**: Interface seguindo Material Design 3
- 📱 **Responsivo**: Funciona perfeitamente em mobile e web
- 🌙 **Tema Escuro**: Suporte automático ao tema do sistema
- ✨ **Animações Fluidas**: Transições suaves e feedback visual

## 🛠️ Tecnologias Utilizadas

- **Flutter 3.10+**: Framework principal
- **Dart 3.0+**: Linguagem de programação
- **Material Design 3**: Sistema de design
- **SharedPreferences**: Armazenamento local
- **Intl**: Formatação de datas
- **Flutter Staggered Animations**: Animações em lista

## 📋 Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (versão 3.10 ou superior)
- [Dart SDK](https://dart.dev/get-dart) (versão 3.0 ou superior)
- [Android Studio](https://developer.android.com/studio) ou [VS Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)

### Verificar Instalação

```bash
flutter doctor
```

## 🚀 Como Executar

### 1. Clone o Repositório

```bash
git clone https://github.com/seu-usuario/Mobile2.git
cd Mobile2 
```

### 2. Instale as Dependências

```bash
flutter pub get
```

### 3. Execute o Aplicativo

#### Para Android/iOS:
```bash
flutter run
```

#### Para Web:
```bash
flutter run -d chrome
```

#### Para Desktop (Windows/macOS/Linux):
```bash
flutter run -d windows  # Windows
flutter run -d macos    # macOS  
flutter run -d linux    # Linux
```

## 🌐 Versão Web

O aplicativo está disponível online em: https://mobile2-topaz.vercel.app/

Para fazer deploy da versão web:

```bash
flutter build web
```

## 📱 Videos do funcionamento do Mobile

https://github.com/user-attachments/assets/beb66b36-742f-4d18-896e-b817c643873d

### Tela Principal
- Lista de tarefas com filtros
- Indicadores de prioridade e categoria
- Contador de tarefas por status

### Adicionar/Editar Tarefa
- Formulário completo com validação
- Seleção de categoria e prioridade
- Seletor de data de vencimento

### Funcionalidades
- Marcar tarefas como concluídas
- Excluir com confirmação
- Filtros por status e data

## 🏗️ Estrutura do Projeto

```
lib/
├── main.dart                 # Ponto de entrada da aplicação
├── models/
│   └── task.dart            # Modelo de dados da tarefa
├── screens/
│   ├── home_screen.dart     # Tela principal
│   └── add_task_screen.dart # Tela de adicionar/editar
├── services/
│   └── task_service.dart    # Serviço de persistência
└── widgets/
    └── task_card.dart       # Widget do card de tarefa
```

## 🎯 Funcionalidades Detalhadas

### Gerenciamento de Tarefas
- **Criar**: Adicione novas tarefas com título, descrição, categoria, prioridade e data
- **Editar**: Modifique qualquer aspecto de uma tarefa existente
- **Excluir**: Remova tarefas com confirmação e opção de desfazer
- **Completar**: Marque tarefas como concluídas com um toque

### Organização
- **Categorias**: 6 categorias pré-definidas com ícones únicos
- **Prioridades**: 3 níveis com cores distintivas
- **Filtros**: 4 visualizações diferentes (Todas, Pendentes, Concluídas, Hoje)

### Interface
- **Design Responsivo**: Adapta-se a diferentes tamanhos de tela
- **Tema Dinâmico**: Suporte a tema claro e escuro
- **Animações**: Transições suaves entre estados
- **Feedback Visual**: Indicadores de carregamento e confirmações

## 🔧 Personalização

### Adicionar Nova Categoria
1. Abra `lib/models/task.dart`
2. Adicione nova entrada no enum `TaskCategory`
3. Defina label e ícone correspondente

### Modificar Cores de Prioridade
1. Edite o enum `TaskPriority` em `lib/models/task.dart`
2. Ajuste as cores conforme necessário

### Alterar Tema
1. Modifique `ThemeData` em `lib/main.dart`
2. Personalize cores, fontes e componentes

## 🧪 Testes

Execute os testes do projeto:

```bash
flutter test
```

## 📦 Build para Produção

### Android APK
```bash
flutter build apk --release
```

### iOS
```bash
flutter build ios --release
```

### Web
```bash
flutter build web --release
```












