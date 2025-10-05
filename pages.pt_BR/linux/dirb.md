# dirb

> Escaneia servidores web baseados em HTTP por diretórios e arquivos.
> Mais informações: <https://manned.org/dirb>.

- Escaneia um servidor web usando a wordlist padrão:

`dirb {{https://exemple.org}}`

- Escaneia um servidor web usando uma wordlist personalizada:

`dirb {{https://example.org}} {{caminho/para/wordlist.txt}}`

- Escaneia um servidor web não-recursivamente:

`dirb {{https://example.org}} -r`

- Escaneia um servidor web usando um user-agent e cookie especificados para requisições HTTP:

`dirb {{https://example.org}} -a {{user_agent_string}} -c {{cookie_string}}`
