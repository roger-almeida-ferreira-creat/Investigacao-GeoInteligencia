# Inteligência Geográfica: Analisador de Trajetória LBS 🛰️🚔

Este projeto foi desenvolvido para otimizar a análise de dados de Estações Rádio Base (ERBs) em investigações criminais. O sistema processa coordenadas brutas (formato LBS) e gera mapas interativos para visualização de deslocamentos e manchas de calor.

## 🛠️ Tecnologias Utilizadas
* **Python 3.10+**: Linguagem base.
* **Pandas**: Manipulação e normalização de grandes volumes de dados.
* **Folium**: Renderização de mapas dinâmicos usando Leaflet.js.
* **Base64 Encoding**: Injeção de assets (ícones) para garantir portabilidade total do relatório HTML.

## 💡 Funcionalidades
* **Normalização de Coordenadas**: Conversão automática de dados brutos de operadoras.
* **HeatMap Dinâmico**: Visualização de áreas com maior permanência do alvo.
* **Assets Customizados**: Identificação visual de Viaturas, ERBs e Cenas de Crime.
* **Relatório Autônomo**: Gera um arquivo HTML único que pode ser visualizado offline por outros investigadores.

## 🧪 Como Testar
Para fins de demonstração e conformidade com a LGPD, utilize o script `gerador_dados_teste.py` incluído neste repositório para criar uma planilha de exemplo.

## 🚀 Como Executar
1. Instale as dependências: `pip install -r requirements.txt`
2. Execute o gerador de testes: `python gerador_dados_teste.py`
3. Rode o analisador: `python main.py`

## 👨‍💻 Autor
**Roger de Almeida Ferreira** - Engenheiro de Computação e soluções de Inteligência.
