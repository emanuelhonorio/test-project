# Test Project

## Casos de teste

| CT   | Entrada                | Saída esperada |
|------|------------------------|----------------|
| CT01 | username vazio         | falha          |
| CT02 | password vazio         | falha          |
| CT03 | username 4 caracteres  | falha          |
| CT04 | username 5 caracteres  | sucesso        |
| CT05 | username 12 caracteres | sucesso        |
| CT06 | username 13 caracteres | falha          |
| CT07 | password 4 caracteres  | falha          |
| CT08 | password 5 caracteres  | sucesso        |
| CT09 | password 12 caracteres | sucesso        |
| CT10 | password 13 caracteres | falha          |
| CT11 | cep vazio              | falha          |
| CT12 | cep inválido           | falha          |
| CT13 | cep válido             | sucesso        |