# 💪 MauiAppFit - .NET MAUI

## Sobre o Projeto

Este aplicativo foi desenvolvido utilizando .NET MAUI com o objetivo de registrar e gerenciar atividades físicas.

O usuário pode:

* Cadastrar atividades
* Informar descrição da atividade
* Registrar peso
* Adicionar observações
* Visualizar atividades cadastradas
* Buscar atividades
* Editar ou excluir registros

Os dados são armazenados localmente utilizando SQLite.

---

## Conteúdos Aprendidos

Durante o desenvolvimento deste projeto foram aprendidos os seguintes conceitos:

### Interface gráfica com XAML

Uso de componentes como:

* Label
* Entry
* Button
* ListView
* SearchBar
* RefreshView
* DatePicker
* Grid
* ToolbarItem
* TabBar

### Programação em C#

* Manipulação de eventos
* Estruturas condicionais
* Propriedades e métodos
* Comandos (`ICommand`)
* Programação assíncrona com `async/await`
* Navegação entre páginas

### Arquitetura MVVM

* Separação entre interface e lógica
* Utilização de ViewModels
* Data Binding
* Atualização automática da interface com `INotifyPropertyChanged`

### Banco de Dados SQLite

* Criação de tabelas
* Inserção de dados
* Atualização de registros
* Exclusão de registros
* Busca de informações
* Persistência local de dados

### Desenvolvimento Mobile com .NET MAUI

* Criação de aplicações multiplataforma
* Navegação utilizando Shell
* Organização de Views, Models e ViewModels
* Estruturação de aplicações mobile

---

## Funcionalidades do Projeto

O aplicativo possui funcionalidades como:

* Cadastro de atividades físicas
* Listagem de atividades
* Busca por descrição
* Atualização de registros
* Exclusão de atividades
* Navegação entre telas
* Armazenamento local utilizando SQLite

---

## Estrutura do Projeto

* `Models` → Classe `Atividade`
* `ViewModels` → Lógica da aplicação
* `Views` → Interfaces gráficas
* `Helpers` → Classe de acesso ao banco SQLite
* `AppShell.xaml` → Navegação da aplicação

---

## Como Executar o Projeto

1. Clone o repositório
2. Abra o projeto no Visual Studio 2026
3. Restaure os pacotes necessários
4. Execute o projeto em um emulador Android ou Windows

Projeto desenvolvido para a disciplina de Programação para Dispositivos Móveis II com .NET MAUI.
