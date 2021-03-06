class: animation-fade
layout: true

---

class: impact

# Внезапная
## теория чисел

---

# Модульная арифметика

* Модуль

    $ 3 \cdot 4 = 5 \pmod 7 $

--

* Поле остатков по модулю $ N $

    $ \mathbb{Z}\_N = \\{ 0, 1, 2 .. N-1 \\} $

--

* Обратный элемент $ x^{-1} $

    $ x \cdot x^{-1} = 1 \pmod N $

--
    $ x^{-1} $ может и не существовать в $ \mathbb{Z}\_N $, в частности если $ gcd(x, N) \neq 1 $

--

* Группа обратимых остатков по модулю $ N $

    $ \mathbb{Z}\_{N}^{*} = \\{ \forall x \in \mathbb{Z}\_{N} | x^{-1} \in \mathbb{Z}\_{N} \\} $

--
    Например, $ \mathbb{Z}\_{12}^{*} = \\{ 1, 5, 7, 11 \\} $

---

# Модульная арифметика

* Группа обратимых остатков по простому модулю $ p $

    $ \mathbb{Z}\_{p}^{*} = \\{ 1, 2, .. p-1 \\} = \mathbb{Z}\_{p} \backslash \\{ 0 \\} $

--

* Генератор группы $ g $

    $ \exists g \in \mathbb{Z}\_{p}^{\*} | \mathbb{Z}\_{p}^{\*} = \\{ 1,g^1,g^2 .. g^{p-2} \\} $

--
    Например, для $ \mathbb{Z}\_{7}^{*} $ $ g = 3 $, потому как $ \\{ 1,3,3^2,3^3,3^4,3^5 \\} = \\{ 1,3,2,6,4,5 \\} $

--
    Однако, если $ g = 2 $, то $ \\{ 1,2,2^3,2^2,2^4,2^5 \\} = \\{ 1,2,4 \\} $

--

* Порядок $ g $

    $ ord_p(g) = |\\{ 1,g^1,g^2 .. g^{p-2} \\}| $

--
    Например, $ ord_7(3) = 6 $, $ ord_7(2) = 3 $

---

class: impact

# Это нам
## скоро пригодится
