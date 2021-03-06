---
layout: post
title: Разработка оси Y
date: '2013-01-21 20:13:02 -0200'
tags: []
---
Как упоминалось ранее, разрабатывается станок со стационарным порталом. При сравнительно небольшой площади обработки перемещение стола более эффективно, нежели перемещение портала. Планируется изготовить портал из дюралюминиевого профиля с Т-образными пазами (он также называется T-slot и 80/20). Наш выбор пал на профиль серии 8, то есть с базовым сечением *40 &times; 40 мм*. На данный момент планируется использовать профиль *40 &times; 80 мм*, но это решение может измениться в зависимости от того, какой профиль будет доступен и по какой цене.

Использование такого профиля дает ряд преимуществ --- он прочный, легкий, прямой и не требует шлифования. Кроме того, существует масса разновидностей крепления для разных задач, в том числе крепления, позволяющие компенсировать неидеальные торцы профиля.

![Профиль 8, 80x40 (Item Industrietechnik)]({{ site.url }}/assets/images/2013-01-21-y-axis-design/item_8_80x40.jpg)

[На сайте производителя представлены](http://www.item24.com.ua/) средства расчета прогиба балки при различных условиях установки. Если предположить, что профиль представляет собой балку длиной *680 мм*, закрепленную с двух сторон на шарнирах, то под действием силы *150 Н* в его середине прогиб составит *0,06 мм*. При глухой заделке концов прогиб составит всего 0,01 мм. Такое отклонение нас вполне устраивает, особенно если учесть что края балки все-таки закреплены на боковых опорах портала, вся ось Z в сборе весит меньше, чем 15 килограмм, а ее вес не сосредоточен в одной точке, а распределен между четырьмя каретками (и, соответственно, двумя балками).

К сожалению, профиль не лишен и недостатков. Т-образный паз, предназначенный для крепления, расположен в строго определенном месте, а крепление других элементов конструкции к профилю помимо этого паза крайне затруднительно. Кроме того, при затягивании гайки, помещенной в паз, его стенки деформируются, обеспечивая более надежное крепление и препятствуя раскручиванию гайки. Это преимущество для нас оборачивается недостатком, так как для подобной деформации ширина детали, прижимаемой к профилю должна быть ощутимо шире паза (желательно *40 мм*). По этой причине между рельсами и профилем установлены полосы из дюралюминия. Для того, чтобы закрепить опоры ШВП придется изготовить специальные кронштейны, а чтобы муфта между ШД и ШВП могла свободно вращаться, в профиле придется выбрать небольшое углубление.

![Ось Y (1)]({{ site.url }}/assets/images/2013-01-21-y-axis-design/yaxis_01.jpg)

![Ось Y (2)]({{ site.url }}/assets/images/2013-01-21-y-axis-design/yaxis_02.jpg)

![Ось Y (3)]({{ site.url }}/assets/images/2013-01-21-y-axis-design/yaxis_03.jpg)

![Ось Y (4)]({{ site.url }}/assets/images/2013-01-21-y-axis-design/yaxis_04.jpg)

![Ось Y (5)]({{ site.url }}/assets/images/2013-01-21-y-axis-design/yaxis_05.jpg)

Следует отметить, что немаловажным преимуществом этого профиля также является наша возможность добыть его по оптовой цене. :)