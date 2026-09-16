# Atividade - Hash

Atividade prática sobre uso de hash para verificar a integridade de um arquivo.

Neste repositório estão:

- `mensagem_original.txt`: arquivo utilizado na atividade;
- `hash_sha256.txt`: hash SHA-256 gerado a partir do arquivo original.

O hash foi gerado pelo PowerShell usando o comando:

`Get-FileHash .\mensagem_original.txt -Algorithm SHA256`

Ao alterar o conteúdo do arquivo, o valor do hash também é alterado.
