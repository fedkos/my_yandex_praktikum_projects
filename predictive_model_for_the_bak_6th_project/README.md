# Проект "Отток клиентов из банка"

## Цель
Подготовить модель, которая будет прогнозировать, уйдёт клиент из банка в ближайшее время или нет.  

## Вывод
Модель RandomForest показала лучшие результаты.  
Стартовые метрики на учебной выборке: F1: 0.5357142857142858, AUR-ROC: 0.695208817286319 
Регулировка гиперпараметров n_estimators = 271 и max_depth= 20, а также добавление min_samples_leaf = 5, class_weight = 'balanced'  
позволили улучшить показатели модели. Во вторую итреацию улучшения показатели на тестовой выборке составили:  
F1: 0.6533996683250415, AUR-ROC: 0.8020829721743886.    
  
На контрольной выборке:  
F1: 0.6317460317460318, AUR-ROC: 0.8020829721743886.   
Таким образом, была достигнута цель проекта (метрика F1 не менее 0.59). AUR-ROC лучше, чем у случайной модели, так как  
превышает 0.5.  

## Стек  
- Matplotlib
- Pandas
- SciPy
- math
- numpy
- sklearn
  
## Статус проекта  
Завершён
