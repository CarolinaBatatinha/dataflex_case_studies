# 📋 **demanda_01**: Análise simples de dados de clientes (*Perfil: Analista de Dados*)
### Problema:  
O time de produto quer entender o perfil dos nossos clientes mais inadimplentes. Temos um CSV com os dados dos últimos 1.000 clientes, contendo:
```
id_cliente	idade	renda_mensal	score_credito	inadimplente
         1	   32	      3500.0	          620	           1

         2	   45	      8000.0	          700	           0
       ...	  ...	         ...	          ...	         ...
```

### Tarefa:

- Ler o CSV com Python (Pandas)
- Gerar um relatório simples (pode ser em Markdown, Jupyter ou só um .py com print mesmo) respondendo:
- Quantos clientes estão inadimplentes?
- Qual a média de idade dos inadimplentes?
- Qual a renda média dos inadimplentes?
- Existe alguma faixa etária que concentra mais inadimplentes? (faixas de 10 em 10 anos)