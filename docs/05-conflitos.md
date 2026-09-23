\# Conflitos



\## O que é um conflito?



Um conflito acontece quando o Git encontra alterações diferentes na mesma parte de um arquivo e não consegue decidir automaticamente qual alteração deve permanecer.



Isso pode acontecer quando duas branches modificam a mesma linha ou trecho de um arquivo.



\## Como resolver um conflito?



Quando ocorre um conflito, é necessário:



1\. Identificar o arquivo que possui o conflito.

2\. Analisar as alterações realizadas em cada branch.

3\. Escolher qual alteração deve permanecer ou combinar as alterações.

4\. Remover as marcações do conflito.

5\. Salvar o arquivo.

6\. Registrar a resolução em um commit.



\## Exemplo de conflito



Durante o desenvolvimento deste guia, foi criado um conflito controlado no arquivo `README.md`.



Duas branches realizaram alterações diferentes na mesma parte do arquivo.



O Git identificou que não era possível realizar a integração automaticamente.



A resolução foi feita analisando as duas alterações e mantendo o conteúdo adequado para o projeto.



\## Registro da resolução



O conflito foi resolvido manualmente após a análise das alterações das duas branches.



Essa experiência demonstrou como o Git sinaliza alterações incompatíveis e como o desenvolvedor pode resolver o problema antes de concluir a integração.



\## Exercício



Imagine que duas pessoas alteraram a mesma linha de um arquivo de maneiras diferentes.



Explique:



1\. Por que o Git pode gerar um conflito.

2\. O que deve ser analisado durante a resolução.

3\. Por que é importante revisar o arquivo antes de finalizar o merge.

