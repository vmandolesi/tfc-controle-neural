# TFC – Controle neural indireto e direto, PID e LQR

Trabalho Final de Curso de Vitor Martuci Mandolesi (EA019, FEEC/Unicamp, 2026).
Orientador: Prof. Dr. Fernando José Von Zuben. Coorientador: Caique Santos Lima.

Comparação de desempenho entre PID, LQR e controle neural (indireto e direto)
em um sistema carro-pêndulo e em um sistema de infusão de fármaco.

## Conteúdo
- `TFC_controle_neural.ipynb`: notebook que reproduz todos os resultados do texto (já com as saídas gravadas).
- `TFC_cache/`: pesos treinados das redes e as 100 plantas sorteadas do cenário C3.

## Como reproduzir (Google Colab)
1. Baixe este repositório (botão **Code → Download ZIP**) e descompacte.
2. Copie a pasta `TFC_cache` para `MyDrive/TFC_cache` no seu Google Drive (arquivos direto na pasta, sem subpasta).
3. Abra o notebook no Colab e use **Executar tudo**. Com o cache, leva cerca de 4 minutos.

Sem o cache, o notebook treina todas as redes do zero (bem mais demorado), e os números
podem variar um pouco entre ambientes (Seção 4.5.5 do texto).
