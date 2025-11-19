
NO DIA DA APRESENTAÇÃO ABAIXAR DOS AS CHAVES ASSIM:
{

}




NO DIA DA APRESENTAÇÃO:
banco de dados no dia: criar uma tabela nova
clicar no icone de pasta azul do msql
abre o banco
remover as aspas dos nomes das tabelas
apagar o Unknown collation: 'utf8mb4_0900_ai_ci' de todas as tabelas



OPÇÃO 1: Exportar e Importar (MELHOR E MAIS SEGURO)
1. No seu PC (onde a tabela está funcionando):
No MySQL Workbench:
Server → Data Export
escolha o banco (schema)
marque a tabela tbusuarios
selecione Export to Self-Contained File
clique em Start Export
Isso gera um arquivo tipo:
banco.sql 

2. No PC da faculdade:
No MySQL Workbench:
Server → Data Import
escolha o arquivo .sql
clique em Start Import
Pronto!
✔ Ele cria a tabela
✔ Cria os dados
✔ Sem você precisar deletar nada manualmente

✅ OPÇÃO 2: Copiar e colar o SQL (funciona também)

Se você quer só copiar e colar o código SQL da tabela, então:

🔥 SE a tabela já existe:


