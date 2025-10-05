# dirbuster

> Realiza força bruta em diretórios e nomes de arquivos em servidores.
> Mais informações: <https://www.kali.org/tools/dirbuster/>.

- Inicia em modo GUI:

`dirbuster -u {{http://exemple.com}}`

- Inicia em modo headless (sem GUI):

`dirbuster -H -u {{http://exemple.com}}`

- Define a lista de extensão de arquivo:

`dirbuster -e {{txt,html}}`

- Habilita a saída verbosa:

`dirbuster -v`

- Define o local do relatório:

`dirbuster -r {{caminho/para/relatorio.txt}}`
