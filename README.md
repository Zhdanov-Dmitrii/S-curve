# Интерполяция траектории с профилем скорости S-curve
Проект в рамках учебной дисциплины "Моделирование информационных систем" выполнен в  Matlab c использованием символьных вычислений

Процесс делится  на 7 этапов:
1) постоянный рывок d^3S/dt^3 = J до достяжении ускорения d^2S/dt^2 = a
2) Постоянное ускорение d^2S/dt^2 = a
3) Постоянный отрицательный рывок d^3S/dt^3 = -J до достяжения скорости v
4) Постоянная скорость dS/dt = v
5) Постоянный отрицательный рывок d^3S/dt^3 = -J до достяжения ускорения -a
6) Постоянное отрицательное ускорение d^2S/dt^2 = -a 
7) Постоянный рывок d^3S/dt^3 = J до достяжения v = 0;

Функция скорости с иллюстрацией этапов и указанием начала/конца каждого этапа

![img](https://user-images.githubusercontent.com/48201807/174833990-7eca85bd-5898-4fb9-997b-4fffb02f35a7.png)


Результат работы с параметрами J = 1; a = 1; v = 4; T = 14:

![img_5](https://user-images.githubusercontent.com/48201807/174834084-c6da35dd-23e8-4905-a05e-48cd0f6650c6.png)
![img_6](https://user-images.githubusercontent.com/48201807/174834086-aba4c0dd-31b3-486a-878d-cb99a652bf0c.png)
![img_7](https://user-images.githubusercontent.com/48201807/174834087-0fd4f71d-4064-4f32-a4b2-cd39e9b01629.png)
![img_8](https://user-images.githubusercontent.com/48201807/174834080-f90c86ab-1bde-4959-a626-372c6b1d7148.png)
