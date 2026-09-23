# Conflitos

## O que é um conflito?

Um conflito acontece quando o Git encontra alterações diferentes na mesma parte de um arquivo e não consegue decidir automaticamente qual alteração deve permanecer.

Isso pode acontecer quando duas branches modificam a mesma linha ou trecho de um arquivo.

## Como resolver um conflito?

Quando ocorre um conflito, é necessário:

1. Identificar o arquivo que possui o conflito.
2. Analisar as alterações realizadas em cada branch.
3. Escolher qual alteração deve permanecer ou combinar as alterações.
4. Remover as marcações do conflito.
5. Salvar o arquivo.
6. Registrar a resolução em um commit.

## Exemplo de conflito

Durante o desenvolvimento deste guia, foi criado um conflito controlado no arquivo `README.md`.

A branch `feature/conflito-readme` alterou a descrição do guia para:

> Guia de aprendizado interativo sobre Git e GitHub para estudantes de tecnologia.

Enquanto a branch `docs/estrutura-guia` alterou a mesma linha para:

> Guia de aprendizado interativo sobre Git e GitHub para iniciantes na área de tecnologia.

Como as duas branches fizeram alterações diferentes na mesma parte do arquivo, o GitHub não conseguiu realizar a integração automaticamente.

## Registro da resolução

O conflito foi resolvido manualmente no Pull Request.

As duas alterações foram analisadas e o texto final foi combinado como:

> Guia de aprendizado interativo sobre Git e GitHub para estudantes e iniciantes em tecnologia.

Após a resolução, o Pull Request foi integrado à branch `docs/estrutura-guia`.

Essa experiência demonstrou como o Git sinaliza alterações incompatíveis e como o desenvolvedor pode analisar e resolver o conflito antes de concluir a integração.

## Exercício

Imagine que duas pessoas alteraram a mesma linha de um arquivo de maneiras diferentes.

Explique:

1. Por que o Git pode gerar um conflito.
2. O que deve ser analisado durante a resolução.
3. Por que é importante revisar o arquivo antes de finalizar o merge.
