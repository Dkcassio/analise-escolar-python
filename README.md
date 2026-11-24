# Desafio 02 — Análise de desempenho e frequência escolar

> Projeto didático com dados fictícios.

**Equipe:** [Cassio Rezende Rodrigues Batista]

## Perguntas
1. Existe associação entre frequência escolar e média final?
2. Quais turmas apresentam as maiores e menores médias finais?
3. Estudantes com frequência ≥ 85% têm média final diferente dos estudantes com frequência < 85%? (teste de hipótese)

## Principais conclusões
Os resultados numéricos são apresentados nas células executadas do notebook. Consulte as tabelas, gráficos e a interpretação do teste de Welch antes de registrar a síntese final.

## Arquivos
- `desafio02_analise_escolar.ipynb`: notebook com preparação, exploração, análise e conclusões.
- `dados/base_escolar_original.csv`: base original, sem alterações.
- `dados/base_escolar_tratada.csv`: base depois da limpeza.
- `requirements.txt`: bibliotecas necessárias.
- `.gitignore`: arquivos temporários ignorados pelo Git.

## Como rodar
### No computador
1. Instale Python 3.10 ou mais recente.
2. Baixe o repositório.
3. Execute `pip install -r requirements.txt`.
4. Execute `python -m jupyter lab`.
5. Abra o notebook e use **Run → Run All Cells**.

O notebook precisa permanecer na mesma pasta que `dados/`.

### No Google Colab
Envie o notebook e a pasta `dados/` para o ambiente do Colab e use **Ambiente de execução → Executar tudo**.

## Observação
Os dados são fictícios e servem somente para demonstrar o processo de análise exploratória. Não representam alunos ou resultados reais.
