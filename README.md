# Panfletador

<p align="center">
  <a href="https://rios-impassiveis.github.io/panfletador/">
    <img src="https://img.shields.io/badge/🚀%20Abrir%20Panfletador-Online-111827?style=for-the-badge" alt="Abrir Panfletador">
  </a>
</p>

**Panfletador** é uma ferramenta web simples para preparar panfletos para impressão, organizando várias cópias de uma mesma imagem em uma única folha.

O projeto roda **100% no navegador**, sem servidor, banco de dados ou instalação. A proposta é transformar rapidamente uma arte pronta em uma folha de impressão com múltiplas cópias.

## ✨ Recursos

- Upload de imagens diretamente pelo navegador
- Prévia da folha em tempo real
- Papéis **A4, A3, A5, Carta e Ofício/Legal**
- Orientação **retrato ou paisagem**
- Configuração de quantidade de **colunas e linhas**
- Controle de **margem externa**
- Controle de **espaçamento entre panfletos**
- Controle de **escala**
- Opção de preencher a célula com corte do excesso
- Linhas de corte para facilitar o acabamento
- Impressão em folha com dimensões configuradas
- Exportação da folha completa para **PNG**
- Exportação da folha completa para **PDF**

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- File API
- Canvas API
- Impressão via CSS `@page`

Não há frameworks ou dependências externas.

## 🚀 Como usar

1. Baixe ou clone o repositório.
2. Abra `index.html` no navegador.
3. Escolha a imagem do panfleto.
4. Configure o tamanho do papel e a orientação.
5. Escolha quantas cópias deseja por folha.
6. Ajuste margens, espaçamento e escala.
7. Escolha uma das opções:
   - **Imprimir folha**
   - **PNG**
   - **PDF**

### Exemplo

Para colocar uma arte pequena em uma folha A4, basta selecionar, por exemplo:

```text
Papel: A4
Orientação: Retrato
Colunas: 2
Linhas: 3
```

Resultado: **6 cópias do panfleto em uma folha A4**.

## 💡 Motivação

O Panfletador surgiu de uma necessidade prática: preparar rapidamente materiais gráficos para impressão sem precisar abrir um software de editoração ou montar manualmente cada cópia em uma página.

A ideia do projeto é manter o processo simples: **carregar a arte → configurar a folha → imprimir ou exportar**.

## 📁 Estrutura

```text
panfletador/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## 🔒 Privacidade

A imagem selecionada é processada no próprio navegador. O projeto não envia as imagens para um servidor.

## 📄 Licença

Distribuído sob a licença MIT. Consulte o arquivo [`LICENSE`](LICENSE).

## 👤 Autor

**Lúcio Alves**

Projeto desenvolvido como parte do portfólio de desenvolvimento web e automação de ferramentas digitais.
