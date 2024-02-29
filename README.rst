|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Непрерывное время при построении нейроинтерфейса BCI
    :Тип научной работы: M1P
    :Автор: Соболевский Федор Александрович
    :Научный руководитель: д. ф.-м. н., Стрижов Вадим Викторович
    :Научный консультант: аспирант 3 курса ФПМИ, Самохина Алина Максимовна

Abstract
========

В задачах декодирования сигналов входные данные представляют собой одномерные или многомерные временные ряды. Применение методов, основанных на нейронных обыкновенных дифференциальных уравнениях, позволяет работать с временными рядами как с непрерывными по времени. Недавние исследования показывают, что подобные методы могут давать заметно более точные по метрикам качества результаты в задачах классификации сигналов, чем методы, работающие с дискретным представлением временных рядов. В данной работе рассматриваются различные методы, основанные на непрерывном представлении временных рядов, в приложении к задаче классификации электроэнцефалограмм (ЭЭГ) и аппроксимации исходного сигнала. В предложенном подходе к построению модели машинного обучения предполагается работа с функциональным пространством сигнала вместо его дискретного представления и использование пространства параметров аппроксимируемой функции в качестве признакового. Основной результат работы – построение обратимого потока и подбор оптимальных размерностей на каждом слое нейросети. 

Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/intsystems/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.comintsystems/ProjectTemplate/blob/master/code/main.ipynb>`_. Can use `colab <http://colab.research.google.com/github/intsystems/ProjectTemplate/blob/master/code/main.ipynb>`_.)
