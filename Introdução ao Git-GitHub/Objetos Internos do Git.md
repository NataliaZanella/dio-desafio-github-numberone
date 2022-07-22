# Objetos Internos do Git



- BLOBS
- TREES
- COMMINTS



**BLOBS**  \0 - Contém metadados do GIT que são o tipo de objeto, tamanho da string, tamanho do arquivo, entre outros.

**TREES** \0  - Armazena e aponta para o tipo de BLOBS diferentes.

**COMMINTS **- Conjunto de mudanças provisórias permanentes. Junta-se o BLOB e o TREE.

