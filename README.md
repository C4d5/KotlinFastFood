# 🍔 Kotlin FastFood

Aplicativo mobile nativo para Android desenvolvido em **Kotlin**, projetado para simular o sistema de pedidos e gerenciamento de uma rede de fast food.

## 🚀 Sobre o Projeto

Este projeto foi construído com foco no aprendizado e na aplicação prática do desenvolvimento Android nativo. A aplicação explora a estruturação de layouts modernos, gerenciamento de dependências e a arquitetura padrão para aplicativos móveis.

## 🛠️ Tecnologias Utilizadas

* **Kotlin** (Linguagem principal)
* **Android SDK**
* **Gradle (Kotlin DSL - `build.gradle.kts`)** para gerenciamento de dependências
* **XML / Material Design** para interfaces de usuário

## 📂 Estrutura do Projeto

```text
KotlinFastFood/
├── app/                  → Código fonte da aplicação, activities e layouts
├── gradle/               → Arquivos de configuração e wrapper do Gradle
├── build.gradle.kts      → Configuração de build do projeto
└── settings.gradle.kts   → Configurações de módulos do workspace
```
▶️ Como Executar o Projeto
Certifique-se de ter o Android Studio instalado em sua máquina.

Clone este repositório:

Bash
git clone [https://github.com/C4d5/KotlinFastFood.git](https://github.com/C4d5/KotlinFastFood.git)
Abra o Android Studio e selecione a opção Open an Existing Project, apontando para a pasta clonada.

Aguarde a sincronização do Gradle.

Conecte um dispositivo físico via USB (com a depuração USB ativada) ou inicie um Emulador Android virtual.

Clique no botão Run ▶️ para compilar e executar o aplicativo.

📌 Próximos Passos / Melhorias Futuras
Implementação de consumo de API REST para cardápio dinâmico.

Migração para arquitetura MVVM (Model-View-ViewModel).

Adição de persistência local com Room Database.
