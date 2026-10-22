# Plataforma de revisão manual e avaliação de linkage (Cidacs)

Plataforma para revisão manual de registros, análise da concordância entre revisores e avaliação da qualidade de bases integradas por *linkage*. Desenvolvida pelo Centro de Integração de Dados e Conhecimentos para Saúde (Cidacs), Fiocruz Bahia.

- **Usar on-line:** abra o endereço desta página no GitHub Pages.
- **Usar sem internet (recomendado para dados sigilosos):** na plataforma, clique em **Versão offline** e abra o arquivo baixado em qualquer navegador moderno.

## Privacidade

Todo o processamento acontece no navegador de quem usa a plataforma. Nenhum arquivo é enviado a servidores, nem na versão on-line: a página é estática, não coleta dados e não usa serviços externos, e a política de segurança do próprio arquivo impede conexões com outros endereços. Cada pessoa trabalha em uma sessão independente, sem interferência entre usuários.

## O que a plataforma faz

1. **Gerar amostra:** amostragem aleatória simples ou estratificada (inclusive por colunas de similaridade e score combinado), distribuição equilibrada entre revisores, manifesto e relatório para auditoria.
2. **Revisar:** classificação pelo teclado (match, non-match, potential match), realce das diferenças, retomada de revisões parciais.
3. **Resultados e desempate:** kappa de Fleiss, alfa de Krippendorff, AC1 de Gwet, Brennan-Prediger, kappa de Cohen por par, conflitos e rodadas de desempate.
4. **Score e ponto de corte:** curva ROC, sete critérios de corte, dois limiares (Fellegi e Sunter), score aprendido por regressão logística com validação cruzada e métricas da ferramenta na amostra.
5. **Base total:** aplicação da regra a toda a base (CSV ou Parquet, inclusive pastas particionadas) com métricas de qualidade do *linkage* e tratamento explícito dos registros sem candidato.
6. **Gráficos e tabelas:** figuras e tabelas editáveis para publicação (SVG, PNG 300/600 dpi, CSV, LaTeX, HTML, Markdown).

Interface em português, inglês e espanhol, com tema claro e escuro.

## Como citar

CENTRO DE INTEGRAÇÃO DE DADOS E CONHECIMENTOS PARA SAÚDE (CIDACS). **Plataforma de revisão manual e avaliação de linkage de registros**. Versão 1.0. Salvador: Fiocruz Bahia, 2026. Software.

As referências em APA e BibTeX estão na página "Sobre e como citar" da plataforma.

## Contato

Cidacs/Fiocruz Bahia | cidacs.comunicacao@fiocruz.br | https://cidacs.bahia.fiocruz.br/
