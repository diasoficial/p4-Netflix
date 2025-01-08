# Layout Android - Estudo com ConstraintLayout

Este repositório foi criado como parte de um projeto de estudo, com foco na prática do desenvolvimento de layouts no Android utilizando ConstraintLayout. O layout é inspirado no design da interface da Netflix, demonstrando o uso de XML para construir uma interface estruturada e responsiva.

---

## 📋 Visão Geral

O arquivo de layout foi escrito em XML e é projetado para uma aplicação Android. Ele utiliza o `ConstraintLayout` como elemento raiz para posicionar os componentes de forma relativa uns aos outros ou ao contêiner principal. Essa abordagem permite um design de interface flexível e dinâmico.

---

## 🛠 Funcionalidades

- **ConstraintLayout**: Proporciona um design responsivo e recursos de alinhamento para diferentes tamanhos de tela.
- **Componentes de UI**:
  - `ImageView`: Exibe imagens (ex.: logos, capas, etc.).
  - `TextView`: Usado para exibir textos como rótulos, títulos e categorias.
  - `Button`: Botões interativos para ações do usuário, como "Assistir" ou "Detalhes".
  - **Guidelines**: Utilizados para alinhar e organizar elementos vertical e horizontalmente.

---

## 📑 Detalhes do Layout

1. **Seção de Cabeçalho**:
   - Contém uma imagem (`@drawable/capa`) que serve como capa.
   - Inclui opções de navegação como "Séries", "Filmes" e "Minha Lista".

2. **Seção de Conteúdo**:
   - Exibe uma imagem (`@drawable/logo_peaky`) com texto descritivo para gêneros ou temas como "Violência" ou "Sinistro".
   - Inclui botões para ações como "Assistir" e "Detalhes".

3. **Rolagem Horizontal**:
   - As seções "Lançamentos" e "Anime" apresentam imagens de conteúdo (ex.: pôsteres) alinhadas horizontalmente.

4. **Diretrizes Responsivas**:
   - Componentes `Guideline` são usados para garantir espaçamento e alinhamento consistentes em diferentes dispositivos.

---

## 📋 Como Usar
1. **Importe o Layout: Coloque o arquivo activity_main.xml no diretório res/layout do seu projeto Android.

2. **Adicione os Recursos:
  - Adicione os arquivos de imagem necessários no diretório res/drawable.
  - Defina as cores e strings nos arquivos res/values/colors.xml e res/values/strings.xml, respectivamente.

3. Compile e Execute: Abra o projeto no Android Studio, sincronize os arquivos Gradle e execute o app em um emulador ou dispositivo físico.

---

## 📂 Estrutura de Arquivos

```plaintext
.
├── res/
│   ├── layout/
│   │   ├── activity_main.xml (Este arquivo)
│   ├── drawable/
│   │   ├── capa.png
│   │   ├── logo.png
│   │   ├── ic_executar_24.png
│   │   ├── f1.png
│   │   ├── f2.png
│   │   ├── f3.png
│   │   ├── f4.png
│   │   ├── f5.png
│   │   ├── f6.png
│   ├── values/
│   │   ├── colors.xml
│   │   ├── strings.xml

```

## Autor
Desenvolvido por [Gabriel Dias](https://github.com/diasoficial). Sinta-se à vontade para contribuir ou enviar feedback!

---

## 📜 Licença
Este projeto é open-source e está disponível sob a [Licença MIT](./LICENSE).

---

## 🖼 Pré-visualização
![Screenshot_2](https://github.com/user-attachments/assets/6f95ce21-a79f-4e38-9909-8060493eca34)
