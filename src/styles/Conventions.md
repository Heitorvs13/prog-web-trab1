# Cores Padrão:

| Uso | Variável | Hex |
| --- | -------- | --- |
| Destaques | `--main-red` | `#D32E2E` |
| Fundo | `--backgorund-sand` | `#F9E7BF` |

# Fontes Padrão:

| Uso | Variável | Fonte |
| --- | -------- | ----- |
| Destaques | `--bold` | `Fugaz One` |
| Padrão | `--light` | `Alumni Sans` |

### Import:

    @import url('https://fonts.googleapis.com/css2?family=Alumni+Sans:ital,wght@0,100..900;1,100..900&family=Fugaz+One&display=swap');


# Elemento root:

Padrão com as variáveis descritas nos itens anteriores.

    :root {

    --main-red: #D32E2E;
    --background-sand: #F9E7BF;

    --bold: Fugaz One;
    --light: Alumni Sans;

    }

# Zerando o CSS padrão:

Remove estilizações pré-estabelecidas para evitar interações indesejadas com a estilização aplicada pelo arquivo

    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }