# 📱 SmartList

Aplicativo mobile desenvolvido em **Flutter** com o objetivo de auxiliar usuários na organização de **listas de compras**, permitindo o cadastro de produtos, controle dos itens adquiridos e gerenciamento de diferentes listas de forma simples, prática e intuitiva.

O projeto está sendo desenvolvido como atividade da disciplina de **Programação para Dispositivos Móveis**, utilizando Flutter e a linguagem Dart.

---

# 📌 Tema do Projeto

O **SmartList** é um aplicativo destinado ao gerenciamento de listas de compras.

A proposta é oferecer uma solução simples para que os usuários possam criar e organizar listas de produtos antes de realizar suas compras, reduzindo o risco de esquecer itens importantes e tornando o processo de compra mais organizado.

O aplicativo utilizará armazenamento local, permitindo que as listas permaneçam disponíveis mesmo sem conexão com a internet.

---

# 💡 Motivação

Muitas pessoas utilizam papel, aplicativos de notas ou mensagens para organizar suas compras, tornando difícil o controle dos produtos que já foram adquiridos ou daqueles que ainda precisam ser comprados.

O SmartList surge como uma alternativa prática e intuitiva para centralizar essas informações em um único aplicativo.

Além disso, o desenvolvimento deste projeto tem como finalidade aplicar os conhecimentos adquiridos na disciplina de Programação para Dispositivos Móveis, utilizando o framework Flutter e boas práticas de desenvolvimento de software.

---

# 🎯 Objetivos

O SmartList tem como principais objetivos:

- Facilitar a organização de listas de compras;
- Permitir o gerenciamento de múltiplas listas;
- Auxiliar o usuário durante o processo de compra;
- Disponibilizar uma interface simples e intuitiva;
- Armazenar as informações localmente no dispositivo.

---

# 👥 Público-alvo

O aplicativo é destinado a qualquer pessoa que deseje organizar suas compras de forma prática utilizando um dispositivo móvel.

---

# 🎯 Escopo do Projeto

## Funcionalidades previstas (Dentro do escopo)

O aplicativo deverá permitir:

- Criar múltiplas listas de compras;
- Editar o nome de uma lista;
- Excluir listas;
- Adicionar produtos em uma lista;
- Informar a quantidade desejada de cada produto;
- Editar produtos cadastrados;
- Remover produtos da lista;
- Marcar produtos como comprados;
- Pesquisar listas pelo nome;
- Armazenar todas as informações localmente;
- Interface desenvolvida seguindo os padrões do Material Design.

---

## Funcionalidades fora do escopo

As funcionalidades abaixo não fazem parte da primeira versão do projeto:

- Cadastro de usuários;
- Sistema de login e autenticação;
- Sincronização em nuvem;
- Compartilhamento de listas;
- Leitura de código de barras;
- Comparação automática de preços entre supermercados;
- Integração com supermercados;
- Histórico de compras;
- Controle financeiro completo;
- Geração de relatórios em PDF;
- Notificações e lembretes;
- Versão Web ou Desktop.

---

# 🔄 Fluxo de Utilização

O funcionamento previsto para o aplicativo será:

1. O usuário abre o SmartList;
2. Cria uma nova lista de compras;
3. Adiciona os produtos desejados;
4. Informa a quantidade de cada produto;
5. O aplicativo salva os dados localmente;
6. Durante a compra, o usuário marca os produtos já adquiridos;
7. Caso necessário, os produtos e listas podem ser editados ou removidos.

---

# 📋 Casos de Uso

O sistema permitirá que o usuário:

- Criar listas de compras;
- Gerenciar os produtos de cada lista;
- Marcar produtos como comprados;
- Editar listas e produtos;
- Excluir listas e produtos;
- Consultar rapidamente suas listas cadastradas.

---

# ✅ Requisitos Funcionais

| Código | Descrição |
|---------|-----------|
| RF01 | O sistema deverá permitir criar uma nova lista de compras. |
| RF02 | O sistema deverá permitir visualizar todas as listas cadastradas. |
| RF03 | O sistema deverá permitir editar uma lista existente. |
| RF04 | O sistema deverá permitir excluir uma lista. |
| RF05 | O sistema deverá permitir adicionar produtos em uma lista. |
| RF06 | O sistema deverá permitir informar a quantidade desejada para cada produto. |
| RF07 | O sistema deverá permitir editar um produto cadastrado. |
| RF08 | O sistema deverá permitir excluir um produto da lista. |
| RF09 | O sistema deverá permitir marcar um produto como comprado. |
| RF10 | O sistema deverá permitir pesquisar listas pelo nome. |
| RF11 | O sistema deverá armazenar todas as informações localmente. |
| RF12 | O sistema deverá validar os campos obrigatórios antes de salvar listas e produtos. |

---

# ⚙️ Requisitos Não Funcionais

| Código | Descrição |
|---------|-----------|
| RNF01 | O aplicativo será desenvolvido utilizando Flutter. |
| RNF02 | A linguagem utilizada será Dart. |
| RNF03 | O aplicativo deverá possuir interface responsiva para dispositivos móveis. |
| RNF04 | O sistema deverá apresentar tempo de resposta adequado para operações comuns. |
| RNF05 | Os dados deverão permanecer armazenados mesmo após o encerramento do aplicativo. |
| RNF06 | A interface deverá seguir os princípios do Material Design. |
| RNF07 | O código será organizado em módulos para facilitar futuras manutenções. |
| RNF08 | O aplicativo deverá funcionar sem conexão com a internet. |

---

# 🛠️ Tecnologias Previstas

O desenvolvimento utilizará as seguintes tecnologias:

- Flutter
- Dart
- SQLite (sqflite)
- path
- Material Design

---

# 🏗️ Arquitetura Prevista

O projeto seguirá uma arquitetura organizada em camadas, separando interface, lógica de negócio e persistência de dados, facilitando futuras manutenções e evolução do sistema.

---

# 📂 Estrutura Prevista do Projeto

```
lib/
├── main.dart
├── models/
├── database/
├── services/
├── screens/
├── widgets/
└── utils/
```

---

# ▶️ Como Executar o Projeto

```bash
# Clonar o repositório
git clone https://github.com/lukinh4/SmartList.git

# Entrar na pasta
cd SmartList

# Instalar as dependências
flutter pub get

# Executar o aplicativo
flutter run
```

---

# 🚀 Cronograma de Desenvolvimento

As etapas previstas para o desenvolvimento são:

- Estruturação inicial do projeto;
- Desenvolvimento das telas;
- Implementação do gerenciamento de listas;
- Implementação do gerenciamento de produtos;
- Persistência dos dados utilizando SQLite;
- Testes e correções;
- Publicação da versão final.

---

# 🔮 Evoluções Futuras

Como possíveis melhorias futuras, o SmartList poderá receber funcionalidades como:

- Login de usuários;
- Sincronização em nuvem;
- Compartilhamento de listas;
- Leitura de código de barras;
- Comparação de preços entre mercados;
- Histórico de compras;
- Estatísticas de consumo;
- Integração com serviços externos.

---

# 📌 Situação Atual

O projeto encontra-se em fase inicial de desenvolvimento.

Nesta etapa estão sendo definidos os requisitos, escopo, arquitetura e planejamento que servirão como base para a implementação das funcionalidades propostas.

---

# 👨‍💻 Autor

Projeto desenvolvido por **Lucas** como atividade da disciplina de **Programação para Dispositivos Móveis**, utilizando **Flutter** e **Dart**.