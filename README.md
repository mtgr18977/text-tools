# Ferramentas de escrita técnica

Este repositório contém uma coleção de ferramentas e scripts para facilitar tarefas do dia a dia para redatores técnicos.

## Índice

- [Descrição](#descrição)
- [Ferramentas](#ferramentas)
- [Como usar](#como-usar)
- [Licença](#licença)

## Descrição

O objetivo deste repositório é centralizar utilitários e automações que auxiliam profissionais de escrita técnica, tornando processos mais ágeis e padronizados.

## Ferramentas

- **Conversor de arquivos**: scripts para conversão de formatos comuns em TC.
- **Automação de testes**: ferramentas para execução e análise de testes automatizados.
- **Relatórios**: geração automática de relatórios a partir de dados coletados.
- **Utilitários diversos**: scripts auxiliares para tarefas recorrentes.

## Como usar

1. Clone este repositório:

   ```bash
   git clone https://github.com/mtgr18977/text-tools.git
   ```
2. Navegue até a pasta do projeto:

   ```bash
   cd text-tools
   ```
3. Siga as instruções específicas de cada ferramenta no respectivo diretório.

---

## Análise de cobertura

Para utilizar a análise de cobertura da sua documentação você precisa gerar os embeddings para o seu *corpus*.
Para isso você pode utilizar um dos modelos de LLM disponíveis ou o toolkit [docs-cli](https://github.com/your-username/docs-cli-toolkit) feito por mim mesmo.

Para utilizar você vai precisar ter os seus documentos técnicos em formato `.md` em um mesmo diretório (pode conter subdiretórios). Você deverá, então, ter um front0matter na sua documentação conforme o modelo:

```txt
## Metadata_Start 
## code: en
## title: <title> 
## slug: <slug> 
## seoTitle: <seo> 
## description: <description> 
## contentType: Markdown
## Metadata_End
```

Ou então atualizar os scripts conforme o seu front-matter.

Você também precisará extrair as informações dos seus documentos, agrupá-los em um índice (em `.json`) e então gerar os embeddings para esses documentos.

---

## Licença

Este projeto está licenciado sob a licença MIT.
