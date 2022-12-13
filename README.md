# hw5
# Основная часть
## Нормализация данных
### Данные были нормализованы методом TPM, формулой:
### ![](https://render.githubusercontent.com/render/math?math={\Large%20TPM_i%20=%20\frac{q_i%20/%20l_i}{\sum%20(q_j%20/%20l_j)}%20\cdot%2010^6}#gh-light-mode-only)
### Длина неизвестна, так что будет использоваться следующую формула:
### ![](https://render.githubusercontent.com/render/math?math={\Large%20TPM_i%20=%20\frac{q_i}{\sum%20q_j}%20\cdot%2010^6}#gh-light-mode-only)
### ![Ссылка на Colab](https://colab.research.google.com/drive/1-MCqzg_TOIX7t0UMj7k_KRK74Q3SYh3N#scrollTo=IzvXSt0Fi9pv)
## Heatmap
![](https://github.com/luuuuuuca/hw5/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-12-13%20204835.png)
#### Клетки каждого кластера принадлежат одному типу, так как на картинке есть несколько (~5) кластеров клеток
## UMAP
![](https://github.com/luuuuuuca/hw5/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-12-13%20204902.png)
## PCA
![](https://github.com/luuuuuuca/hw5/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-12-13%20204927.png)
#### Данные разбиты по группам cTEC, mTEC-I, mTEC-II, mTEC-III, mTEC-IV, из-за этого понизилась размерность данных и получилось деление на группы
