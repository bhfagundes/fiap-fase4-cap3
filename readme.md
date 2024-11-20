# Classificação Automática de Grãos de Trigo

## Descrição
Este projeto implementa um sistema de classificação automática de grãos de trigo usando técnicas de machine learning. O objetivo é automatizar o processo de classificação tradicionalmente realizado manualmente em cooperativas agrícolas.

## Dataset
- **Fonte**: UCI Machine Learning Repository - Seeds Dataset
- **Amostras**: 210 grãos de trigo
- **Classes**: 3 variedades (Kama, Rosa, Canadian)
- **Características**: 7 medidas físicas

## Estrutura do Projeto
- `Analise_Graos.ipynb`: Notebook principal com análise e implementação
- `seeds_dataset.txt`: Dataset original
- `README.md`: Documentação do projeto

## Requisitos
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Instalação

```bash
# Instalar dependências
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Clonar o repositório (se aplicável)
git clone https://seu-repositorio/classificacao-graos.git
cd classificacao-graos

# Iniciar o Jupyter Notebook
jupyter notebook
```

## Execução
1. Abra o Jupyter Notebook no navegador
2. Navegue até o arquivo `Analise_Graos.ipynb`
3. Execute as células sequencialmente (Shift + Enter)

## Estrutura do Notebook
1. **Importação e Preparação dos Dados**
   - Carregamento do dataset
   - Análise inicial dos dados
   - Tratamento de valores ausentes

2. **Análise Exploratória**
   - Estatísticas descritivas
   - Visualizações (histogramas, boxplots)
   - Análise de correlações

3. **Pré-processamento**
   - Divisão treino/teste
   - Normalização dos dados
   - Preparação das features

4. **Modelagem**
   - Implementação de diferentes algoritmos
   - Treinamento dos modelos
   - Avaliação de performance

5. **Otimização**
   - Grid Search para ajuste de hiperparâmetros
   - Validação cruzada
   - Comparação de resultados

## Resultados
- Comparação entre diferentes algoritmos
- Métricas de avaliação (acurácia, precisão, recall)
- Análise das features mais importantes

## Contribuição
Para contribuir com o projeto:
1. Faça um Fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adicionando nova feature'`)
4. Push para a branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

## Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


## Agradecimentos
- UCI Machine Learning Repository pelo dataset
- Contribuidores que participaram deste projeto
- Referências e inspirações utilizadas


## Status do Projeto
- [x] Análise Exploratória
- [x] Implementação dos Modelos
- [x] Otimização
- [x] Documentação
- [ ] Deploy em Produção

## Próximos Passos
1. Implementar interface web para classificação
2. Adicionar mais variedades de grãos
3. Otimizar performance dos modelos
4. Desenvolver API REST para integração

## Referências
1. UCI Machine Learning Repository: [Seeds Dataset](https://archive.ics.uci.edu/dataset/236/seeds)
2. Documentação Scikit-learn: [Classification](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning)
3. Python Data Science Handbook
4. Artigos relacionados à classificação de grãos

## Notas de Versão
### v1.0.0 (Data Atual)
- Implementação inicial do projeto
- Análise completa do dataset
- Modelos de classificação básicos
- Documentação inicial

### Próxima Versão (Planejada)
- Interface gráfica
- Mais algoritmos de classificação
- Otimização avançada de hiperparâmetros