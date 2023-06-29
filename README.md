# Postman com Newman - Relatório de Testes

Este repositório contém uma ferramenta de relatório de testes utilizando o Postman e a biblioteca Newman. O Postman é uma plataforma de desenvolvimento de APIs que permite criar, testar e documentar APIs. Newman é uma biblioteca de linha de comando que permite executar coleções do Postman em um ambiente de linha de comando.

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado em sua máquina:

- [Postman](https://www.postman.com/downloads/)
- [Node.js](https://nodejs.org/) (versão 10 ou superior)
- [Newman](https://www.npmjs.com/package/newman) (instalado globalmente via npm)

## Instalação

1. Clone este repositório em sua máquina local:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Navegue até o diretório clonado:

```bash
cd nome-do-repositorio
```

3. Instale as dependências do projeto usando o npm:

```bash
npm install
```

## Uso

1. Exporte sua coleção do Postman como um arquivo JSON e salve-o no diretório raiz do projeto. Nomeie o arquivo como `collection.json`.

2. Execute a ferramenta de relatório de testes Newman com o seguinte comando:

```bash
newman run collection.json --reporters cli,html
```

Isso executará a coleção de testes do Postman e gerará relatórios em formato de linha de comando (`cli`) e HTML (`html`).

Os relatórios serão salvos no diretório `reports` dentro do projeto.

## Personalização

Você pode personalizar a aparência do relatório HTML editando o arquivo `template.hbs` no diretório `reports`. Este arquivo utiliza o formato Handlebars para geração do HTML.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões, melhorias ou correções, sinta-se à vontade para abrir uma issue ou enviar um pull request para este repositório.

## Licença

Este projeto está licenciado sob a licença [MIT](LICENSE). Leia o arquivo LICENSE para mais informações.

---

Esse é um exemplo básico de um README para a ferramenta Postman com a ferramenta de relatório de testes Newman. Lembre-se de adaptar as instruções e os detalhes do projeto de acordo com suas necessidades específicas.







