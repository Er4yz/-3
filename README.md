            #region Раздел 1. Базовые условия if и if-else.
            
            //1. Пользователь вводит целое число. Проверить, является ли оно положительным.
            1.Пользователь вводит целое число.Проверить, является ли оно положительным.
<img width="1920" height="1200" alt="№1" src="https://github.com/user-attachments/assets/bb474686-a004-4c9a-a4b7-a58cce88648b" />
            
            Console.Write("Введите целое число: ");
            int a = Convert.ToInt32(Console.ReadLine());
            if (a > 0)
            {
                Console.WriteLine("Число является положительным.");
            }
            else if (a < 0)
            {
                Console.WriteLine("Число является отрицательным.");
            }
            Console.Write("Введите второе целое число: ");
            int b = Convert.ToInt32(Console.ReadLine());
            if (b > 0)
            {
                Console.WriteLine("Число является положительным.");
            }
            else if (b < 0)
            {
                Console.WriteLine("Число является отрицательным.");
            }

            //2. Пользователь вводит целое число. Проверить, является ли оно четным.
<img width="1920" height="1200" alt="№2" src="https://github.com/user-attachments/assets/af03a123-2e42-4cf3-8262-a057d55ab2e0" />

            Console.Write("Введите целое число: ");
            int a = Convert.ToInt32(Console.ReadLine());
            if (a % 2 == 0)
            {
                Console.WriteLine($"Число является четным.");
            }
            else
            {
                Console.WriteLine($"Число является нечетным");
            }

            //3. Даны два целых числа. Вывести наибольшее из них.
<img width="1920" height="1200" alt="№3" src="https://github.com/user-attachments/assets/c4006577-fe9b-41ab-9ba3-175415213b79" />

             Console.Write("Введите первое целое число: ");
            int n1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Введите второе целое число: ");
            int n2 = Convert.ToInt32(Console.ReadLine());

            if (n1 > n2)
            {
                Console.WriteLine($"Наибольшим числом является первое целое - {n1}");
            }
            else if (n2 > n1)
            {
                Console.WriteLine($"Наибольшим числом является второе целое - {n2}");
            }

            //4. Даны два числа с плавающей точкой. Вывести наименьшее.
<img width="1920" height="1200" alt="№4" src="https://github.com/user-attachments/assets/197d420a-c5f8-4320-9a14-d4799ec91516" />

            Console.Write("Введите первое число с плавающей точкой: ");
            double n1 = Convert.ToDouble(Console.ReadLine());

            Console.Write("Введите второе число с плавающей точкой: ");
            double n2 = Convert.ToDouble(Console.ReadLine());

            if (n1 < n2)
            {
                Console.WriteLine($"Наименьшим числом с плавающей точкой является первое число {n1}");
            }
            else if (n2 < n1)
            {
                Console.WriteLine($"Наименьшим числом с плавающей точкой является второе число {n2}");
            }

            //5. Проверить, делится ли введенное число нацело на 5.
<img width="1920" height="1200" alt="№5" src="https://github.com/user-attachments/assets/83f6d4a4-4dbd-43e3-95ab-429131ee8e93" />

            Console.Write("Введите число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a % 5 == 0)
            {
                Console.WriteLine("Число делится на 5 нацело.");
            }
            else
            {
                Console.WriteLine("Число не делится на 5 нацело.");
            }

            //6. Проверить, оканчивается ли введенное целое число нулем.
<img width="1920" height="1200" alt="№6" src="https://github.com/user-attachments/assets/a7031696-334d-41ff-8b74-c2b1b2d391c7" />
            
             Console.Write("Введите целое число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a % 10 == 0) //возвращает последнюю цифру числа
            {
                Console.WriteLine("Число оканчивается на 0.");
            }
            else
            {
                Console.WriteLine("Число не оканчивается на 0");
            }

            
            7.Пользователь вводит температуру воздуха.Если она ниже нуля, вывести: «На улице мороз, наденьте шапку».
<img width="1920" height="1200" alt="№7" src="https://github.com/user-attachments/assets/4197b419-7d5c-4f91-99a5-1a1af41c8fc1" />
            
            Console.Write("Введите температуру воздуха: ");
            double t = Convert.ToDouble(Console.ReadLine());

            if (t < 0)
            {
                Console.WriteLine("На улице мороз, наденьте шапку!");
            }
            else if (t >= 0)
            {
                Console.WriteLine("На улице тепло, шапку можно не надевать!");
            }

            8.Дано число.Если оно больше 100, уменьшить его на 20, иначе увеличить на 10.
<img width="1920" height="1200" alt="№8" src="https://github.com/user-attachments/assets/0c86cd09-d672-4061-9a54-7eaee38cf88d" />

            Console.Write("Введите число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if (number > 100)
            {
                number -= 20;
            }
            else if (number < 100)
            {
                number += 10;
            }
            Console.WriteLine(number);

            9.Ввести два числа. Если они равны, вывести «Числа равны», иначе вывести их произведение.
<img width="1920" height="1200" alt="№9" src="https://github.com/user-attachments/assets/22966890-24ce-4407-ad75-ff7d74b6c841" />

            Console.Write("Введите первое число: ");
            int n1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Введите второе число: ");
            int n2 = Convert.ToInt32(Console.ReadLine());

            if (n1 == n2)
            {
                Console.WriteLine("Числа равны.");
            }
            else if (n1 != n2)
            {
                int mult = n1 *= n2; Console.WriteLine(mult);
            }

            10.Пользователь вводит свой возраст.Если возраст от 18 и старше, вывести «Доступ разрешен», иначе «Доступ запрещен».
<img width="1920" height="1200" alt="№10" src="https://github.com/user-attachments/assets/74204b79-cf28-4939-8eaa-36dea4379d9f" />

            Console.Write("Введите свой возраст: ");
            int age = Convert.ToInt32(Console.ReadLine());

            if (age >= 18)
            {
                Console.WriteLine("Доступ разрешен");
            }
            else if (age < 18)
            {
                Console.WriteLine("Доступ запрещен");
            }

            11.Ввести число.Если оно трехзначное, вывести «Да», иначе «Нет».
<img width="1920" height="1200" alt="№11" src="https://github.com/user-attachments/assets/f61bc6c9-589e-416a-9bc3-3570f262228b" />

            Console.Write("Введите число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if (number >= 100)
            {
                Console.WriteLine("Да");
            }
            else if (number < 100)
            {
                Console.WriteLine("Нет");
            }

            12.Проверить, делится ли число на 3 без остатка.
<img width="1920" height="1200" alt="№12" src="https://github.com/user-attachments/assets/9ad5e29d-8540-4bf8-a46b-f87cd74832d5" />

            Console.Write("Введите число: ");
            int num = Convert.ToInt32(Console.ReadLine());

            if (num % 3 == 0) //проверка, делится ли число делится нацело
            {
                Console.WriteLine("Делится");
            }
            else
            {
                Console.WriteLine("Не делится");
            }

            13.Даны координаты точки на числовой прямой X.Определить, лежит ли точка правее нуля.
<img width="1920" height="1200" alt="№13" src="https://github.com/user-attachments/assets/4c5c6c5a-8e7e-4c0f-bc69-7f6985e76197" />

            Console.Write("Введите точку на числовой прямой X: ");
            double point = Convert.ToDouble(Console.ReadLine());

            if (point > 0)
            {
                Console.WriteLine("Лежит правее нуля");
            }
            else if (point == 0)
            {
                Console.WriteLine("Точка равна нулю");
            }
            else
            {
                Console.WriteLine("Лежит левее нуля");
            }

            14.Ввести баланс счета. Если баланс отрицательный, вывести «Задолженность!».
<img width="1920" height="1200" alt="№14" src="https://github.com/user-attachments/assets/2fc82195-7271-420b-bffd-d14326fd8930" />

            Console.Write("Баланс счета: ");
            double balancescore = Convert.ToDouble(Console.ReadLine());

            if (balancescore < 0)
            {
                Console.WriteLine("Задолженность!");
            }
            else
            {
                Console.WriteLine("Ух ты, мне бы так...");
            }

            15.Пользователь вводит пароль(целое число). Если введен 1234, вывести «Вход выполнен», иначе «Неверный пароль».
<img width="1920" height="1200" alt="№15" src="https://github.com/user-attachments/assets/96c42cf9-e98e-46f6-8abc-36d07a65173a" />

            Console.Write("Введите пароль: ");
            int password = Convert.ToInt32(Console.ReadLine());

            if (password == 1234)
            {
                Console.WriteLine("Вход выполнен");
            }
            else
            {
                Console.WriteLine("Неверный пароль");
            }

            16.Проверить, является ли введенное число отрицательным.
<img width="1920" height="1200" alt="№16" src="https://github.com/user-attachments/assets/e7bdce72-e226-4e4a-b0c5-79267861c139" />

            Console.Write("Введите число: ");
            int n = Convert.ToInt32(Console.ReadLine());

            if (n < 0)
            {
                Console.WriteLine("Отрицательное");
            }
            else
            {
                Console.WriteLine("Положительное");
            }

            17.Даны два числа. Вывести разность большего и меньшего числа.
<img width="1920" height="1200" alt="№17" src="https://github.com/user-attachments/assets/e26c67d0-6568-4632-89d1-d0a296a4d41b" />

            Console.Write("Первое число: ");
            double a = Convert.ToInt32(Console.ReadLine());

            Console.Write("Второе число: ");
            double b = Convert.ToInt32(Console.ReadLine());

            double difference;

            if (a > b)
            {
                difference = a - b;
            }
            else
            {
                difference = b - a;
            }
            Console.WriteLine($"Разность чисел развна: {difference}");

            18.Ввести сумму покупки. Если сумма превышает 1000 рублей, предоставить скидку 5 % и вывести итоговую цену.
<img width="1920" height="1200" alt="№18" src="https://github.com/user-attachments/assets/dbb95aea-fa08-4e58-ba3a-1ff86cee6192" />

            Console.Write("Сумма покупки: ");
            double summ = Convert.ToDouble(Console.ReadLine());
            double reduction;

            if (summ > 1000)
            {
                reduction = summ * 0.95; Console.WriteLine($"Итоговая цена со скидкой: {reduction}");
            }
            else
            {
                Console.WriteLine($"Итоговая цена без скидки: {summ}");
            }

            19.Ввести число.Если оно четное, разделить его на 2, если нечетное — умножить на 3.
<img width="1920" height="1200" alt="№19" src="https://github.com/user-attachments/assets/6358fc20-3a18-47c9-b3c7-4445ed98b47d" />

            Console.Write("Введите число: ");
            double n = Convert.ToDouble(Console.ReadLine());

            if (n % 2 == 0)
            {
                n /= 2; Console.WriteLine(n);
            }
            else
            {
                n *= 3; Console.WriteLine(n);
            }

            20.Пользователь вводит скорость движения.Если скорость выше 90 км / ч, вывести сообщение о нарушении.
<img width="1920" height="1200" alt="№20" src="https://github.com/user-attachments/assets/feb1a94c-f023-4dd3-9a9d-9c15571638d2" />

            Console.Write("Введите скорость движения: ");
            double v = Convert.ToDouble(Console.ReadLine());

            if (v > 90)
            {
                Console.WriteLine("Превышенная скорость!");
            }
            else
            {
                Console.WriteLine("Красавчик");
            }

            21.Дано целое число. Проверить, равно ли оно нулю.
<img width="1920" height="1200" alt="№21" src="https://github.com/user-attachments/assets/cd383762-6d5d-4209-9c4b-9e0f10818a39" />

            Console.Write("Введите целое число: ");
            int n = Convert.ToInt32(Console.ReadLine());

            if (n == 0)
            {
                Console.WriteLine("Число равно нулю");
            }
            else
            {
                Console.WriteLine("Число не равно нулю");
            }

            #region Не поняла
            22.Ввести два вещественных числа.Проверить, равны ли они с точностью до 0.001.
            Console.Write("Первое вещественное число: ");
            float a = Convert.ToSingle(Console.ReadLine());
            Console.Write("Второе вещественное число: ");
            double b = double.Parse(Console.ReadLine);
            double epsilon = 0.001;
            if (Math.Abs(a - b) < epsilon) //Math.Abs - убирает минус, если он есть. В задаче нам важна сама величина разницы (a -b), а не то, что одно число больше, другое - меньше.
            {
                Console.WriteLine("Числа равны с точностью до 0.001.");
            }
            else
            {
                Console.WriteLine("Числа не равны с точностью до 0.001.");
            }

            #endregion

            23.Проверить, делится ли число A на число B без остатка.
<img width="1920" height="1200" alt="№23" src="https://github.com/user-attachments/assets/8ba54e1d-4146-4db9-b8e2-f06631e4ef4f" />

            Console.Write("Число A: ");
            int A = Convert.ToInt32(Console.ReadLine());

            Console.Write("Число B: ");
            int B = Convert.ToInt32(Console.ReadLine());

            if (A % B == 0)
            {
                Console.WriteLine("Делится без остатка");
            }
            else
            {
                Console.WriteLine("Делится с остатком");
            }

            24.Даны два угла треугольника в градусах.Проверить, существует ли такой треугольник(сумма меньше 180).
<img width="1920" height="1200" alt="№24" src="https://github.com/user-attachments/assets/98c471cf-699d-49f4-be44-6c945553f977" />

            Console.Write("Первый угол треугольника: ");
            int corner1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Второй угол треугольника: ");
            int corner2 = Convert.ToInt32(Console.ReadLine());

            if (corner1 + corner2 <= 180)
            {
                Console.WriteLine("Треугольник существует");
            }
            else
            {
                Console.WriteLine("Треугольник НЕ существует");
            }

            25.Ввести радиус круга и сторону квадрата.Определить, у какой фигуры площадь больше.
<img width="1920" height="1200" alt="№25" src="https://github.com/user-attachments/assets/c677a971-ebfe-4954-a6f2-fe2b4c3fda03" />

            const double Pi = 3.1415926535;

            Console.Write("Радиус круга: ");
            double r = Convert.ToDouble(Console.ReadLine());

            Console.Write("Сторона квадрата: ");
            double sidesquare = Convert.ToDouble(Console.ReadLine());

            double circleS = Pi * r * r;

            double squareS = sidesquare * sidesquare;

            if (circleS > squareS)
            {
                Console.WriteLine("Площадь круга больше");
            }
            else
            {
                Console.WriteLine("Площадь квадрата больше");
            }

            26.Ввести два числа. Вывести частное большего на меньшее(предусмотреть проверку деления на 0).
<img width="1920" height="1200" alt="№26 решение 1" src="https://github.com/user-attachments/assets/ec6a6982-651a-4eb6-9228-31fa05a08cb0" />

            Console.Write("Первое число: ");
            double a = Convert.ToDouble(Console.ReadLine());

            Console.Write("Второе число: ");
            double b = Convert.ToDouble(Console.ReadLine());

            double larger = a > b ? a : b;
            double smaller = a < b ? a : b;

            if (smaller == 0)
            {
                Console.WriteLine("Деление на ноль невозможно!");
            }
            else
            {
                double result = larger /= smaller; Console.WriteLine($"Частное: {result}");
            }

            27.Проверить, является ли последняя цифра числа семеркой.
<img width="1920" height="1200" alt="№27" src="https://github.com/user-attachments/assets/7a277546-4ccd-4f42-b91a-6ac7878749aa" />

            Console.Write("Введите число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a % 10 == 7)
            {
                Console.WriteLine("Число оканчивается на 7.");
            }
            else
            {
                Console.WriteLine("Число не оканчивается на 7");
            }

            28.Дано число.Если оно нечетное и положительное, вывести «Да».
<img width="1920" height="1200" alt="№28" src="https://github.com/user-attachments/assets/ffb9d102-3c2b-43da-85a6-b583711637d2" />

            Console.Write("Число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if (number % 2 != 0 && number > 0)
            {
                Console.WriteLine("Да");
            }
            else
            {
                Console.WriteLine("Нет");
            }

            29.Ввести объем свободного места на диске(в ГБ).Если места меньше 5 ГБ, вывести предупреждение.
<img width="1920" height="1200" alt="№29" src="https://github.com/user-attachments/assets/f4cbd389-647b-4573-88e4-a189fa2daeb5" />

            Console.Write("Введите объем свободного места на диске (в гб): ");
            int v = Convert.ToInt32(Console.ReadLine());

            if (v < 5)
            {
                Console.WriteLine("Мало места на диске");
            }
            else
            {
                Console.WriteLine("Место на диске присутствует");
            }

            30.Пользователь вводит оценку(2, 3, 4, 5). Если оценка 4 или 5, вывести «Молодец», иначе «Нужно подтянуться».
<img width="1920" height="1200" alt="№30" src="https://github.com/user-attachments/assets/fd23b04f-26f5-498f-b00c-46e219e58734" />

            Console.Write("Ваша оценка (2, 3, 4, 5): ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a == 4 | a == 5)
            {
                Console.WriteLine("Молодец");
            }
            else if (a == 2 | a == 3)
            {
                Console.WriteLine("Нужно подтянуться");
            }

            31.Даны два символа. Проверить, совпадают ли они.
<img width="1920" height="1200" alt="№31" src="https://github.com/user-attachments/assets/fbfe5a5d-06e0-42e4-8c7e-736a8a20bd72" />

            Console.Write("Первый символ: ");
            string a = Convert.ToString(Console.ReadLine());

            Console.Write("Второй символ: ");
            string b = Convert.ToString(Console.ReadLine());

            if (a == b && b == a)
            {
                Console.WriteLine("Символы совпадают");
            }
            else
            {
                Console.WriteLine("Символы не совпадают");
            }

            32.Ввести число.Если оно кратно и 2, и 7, вывести «Кратно 14».
<img width="1920" height="1200" alt="№32" src="https://github.com/user-attachments/assets/2a5e3f95-1ac2-4c57-a178-b3f099e40c08" />

            Console.Write("Число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a % 2 == 0 && a % 7 == 0)
            {
                Console.WriteLine("Кратно 14");
            }
            else
            {
                Console.WriteLine("НЕ кратно 14");
            }

            33.Ввести массу груза. Если масса превышает допустимые 3.5 тонны, вывести «Перегруз!».
<img width="1920" height="1200" alt="№33" src="https://github.com/user-attachments/assets/f706b6d4-eb78-4f91-95cd-1b21e8e9ee7d" />

            Console.Write("Масса груза: ");
            double m = Convert.ToDouble(Console.ReadLine());

            if (m > 3.5)
            {
                Console.WriteLine("Перегруз!");
            }
            else
            {
                Console.WriteLine("Всё отлично!");
            }

            34.Ввести текущее время(часы от 0 до 23). Если время от 6 до 12, вывести «Доброе утро».
<img width="1920" height="1200" alt="№34" src="https://github.com/user-attachments/assets/2173eee7-a78c-49c1-8382-01063f9ba050" />

            Console.Write("Текущее время (от 0 до 23): ");
            int time = Convert.ToInt32(Console.ReadLine());

            if (time == 6 | time <= 12)
            {
                Console.WriteLine("Доброе утро");
            }
            else if (time == 13 | time <= 18)
            {
                Console.WriteLine("Добрый день");
            }
            else if (time == 19 | time <= 23)
            {
                Console.WriteLine("Добрый вечер");
            }
            else if (time == 0 | time <= 5)
            {
                Console.WriteLine("Доброй ночи");
            }

            35.Ввести рост человека в см. Если рост больше 200 см, вывести «Очень высокий».
<img width="1920" height="1200" alt="№35" src="https://github.com/user-attachments/assets/a86ab058-36de-48fc-9768-28038a92e590" />

            Console.Write("Введите рост человека (в см): ");
            int l = Convert.ToInt32(Console.ReadLine());

            if (l > 200)
            {
                Console.WriteLine("Очень высокий");
            }
            else
            {
                Console.WriteLine("Норм");
            }

            36.Дано двузначное число. Определить, какая из его цифр больше.
<img width="1920" height="1200" alt="№36" src="https://github.com/user-attachments/assets/d27af6c1-f707-48df-913c-5a0cf1b0876b" />

            Console.Write("Введите двухзначное число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            int tens = number / 10; //Десятки. Первая цифра.
            int units = number % 10; //единицы. Вторая цифра.

            if (tens > units)
            {
                Console.WriteLine($"Первая цифра {tens} больше");
            }
            else if (units > tens)
            {
                Console.WriteLine($"Вторая цифра {units} больше");
            }

            37.Ввести стоимость товара. Если товар бесплатный(цена 0), вывести «Акция!».
<img width="1920" height="1200" alt="№37" src="https://github.com/user-attachments/assets/390be3ac-1a6d-4769-90ac-91330453a909" />

            Console.Write("Введите стоимость товара: ");
            int price = Convert.ToInt32(Console.ReadLine());

            if (price == 0)
            {
                Console.WriteLine("Акция!");
            }
            else
            {
                Console.WriteLine("Без Акции.");
            }

            38.Проверить, содержит ли введенное двузначное число одинаковые цифры.
<img width="1920" height="1200" alt="№38" src="https://github.com/user-attachments/assets/959aedb9-83a4-4336-935d-0189c921eeb2" />

            Console.Write("Введите двухзначное число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if ((number / 10) == (number % 10))
            {
                Console.WriteLine("Число содержит двузначное число с одинаковыми цифрами");
            }

            39.Ввести уровень громкости(0–100). Если громкость превышает 80, вывести «Слишком громко для слуха».
<img width="1920" height="1200" alt="№39" src="https://github.com/user-attachments/assets/9ed36d5e-a0c6-4a68-a0d3-ed3e83fbe6d8" />

            Console.Write("Введите уровень громкости: ");
            int lvl = Convert.ToInt32(Console.ReadLine());

            if (lvl > 80)
            {
                Console.WriteLine("Слишком громко для слуха");
            }

            40.Даны два числа. Если их сумма четная, вывести сумму, иначе вывести их разность.
<img width="1920" height="1200" alt="№40" src="https://github.com/user-attachments/assets/9aed8bcd-d7d3-45e1-b717-2d086d7b245c" />

            Console.Write("Первое число: ");
            int n1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Второе число: ");
            int n2 = Convert.ToInt32(Console.ReadLine());

            int summ = n1 + n2;
            int subtraction = n1 - n2;

            if (summ % 2 == 0)
            {
                Console.WriteLine($"Сумма: {summ}");
            }
            else
            {
                Console.WriteLine($"Разность: {subtraction}");
            }

            41.Ввести количество страниц в документе. Если страниц больше 100, включить двухстороннюю печать.
<img width="1920" height="1200" alt="№41" src="https://github.com/user-attachments/assets/03e939d4-06a5-4c8b-8f82-19171e0089a9" />

            Console.Write("Количество страниц в документе: ");
            int quantity = Convert.ToInt32(Console.ReadLine());

            if (quantity > 100)
            {
                Console.WriteLine("Включена двухсторонняя печать");
            }

            #region Не поняла

            42.Проверить, является ли введенное целое число полным квадратом(для проверки использовать Math.Sqrt).
            Console.Write("Введите целое число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if (number < 0)
            {
                Console.WriteLine("Число не является полным квадратом.");
            }
            else
            {
                double sqrtResult = Math.Sqrt(number);
            }

            #endregion

            43.Ввести атмосферное давление. Если давление ниже 740 мм рт. ст., вывести «Пониженное давление».
<img width="1920" height="1200" alt="№43" src="https://github.com/user-attachments/assets/ff1be72e-55fe-4f4f-93b8-81ba3d967a1a" />

            Console.Write("Атмосферное давление: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a < 740)
            {
                Console.WriteLine("Пониженное давление");
            }

            44.Ввести количество забитых мячей командами А и Б.Вывести победителя или сообщить о ничьей.
<img width="1920" height="1200" alt="№44" src="https://github.com/user-attachments/assets/5e93c228-093f-4915-8a5c-a87af90cddfe" />

            Console.Write("Забитые мячи команды A: ");
            int A = Convert.ToInt32(Console.ReadLine());

            Console.Write("Забитые мячи команды B: ");
            int B = Convert.ToInt32(Console.ReadLine());

            if (A > B)
            {
                Console.WriteLine($"Победителями является команда A со счетом {A}");
            }
            else if (B > A)
            {
                Console.WriteLine($"Победителями является команда B со счетом {B}");
            }
            else if (A == B)
            {
                Console.WriteLine($"{A}:{B}. Ничья!");
            }

            45.Дано число.Заменить его на абсолютную величину(модуль) без использования Math.Abs.
<img width="1920" height="1200" alt="№45" src="https://github.com/user-attachments/assets/c0e14a31-d9e2-43c4-ad3a-bfa59b11e4ad" />

            Console.Write("Число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if (number < 0)
            {
                number = -number;
            }
            Console.WriteLine(number);

            46.Ввести показатель уровня сахара в крови.Если показатель выше 6.1 ммоль / л, вывести «Выше нормы».
<img width="1920" height="1200" alt="№46" src="https://github.com/user-attachments/assets/5e09727a-a1b9-409d-b94b-1b4c53d48243" />

            Console.Write("Введите показатель уровня сахара в крови: ");
            double lvlcugar = Convert.ToDouble(Console.ReadLine());

            if (lvlcugar > 6.1)
            {
                Console.WriteLine("Выше нормы");
            }

            47.Проверить, хватит ли пользователю средств на счете для оплаты проезда стоимостью 35 рублей.
<img width="1920" height="1200" alt="№47" src="https://github.com/user-attachments/assets/0b2b4e0c-a4d9-4cf8-8a1f-ee157474cdab" />

            Console.Write("Баланс: ");
            int balance = Convert.ToInt32(Console.ReadLine());

            if (balance > 35)
            {
                Console.WriteLine("Оплата прошла успешно!");
            }
            else
            {
                Console.WriteLine("Оплата не прошла. На счету недостаточно средств!");
            }

            48.Ввести номер текущего этажа.Если этаж выше 10, вывести «Высотный этаж».
<img width="1920" height="1200" alt="№48" src="https://github.com/user-attachments/assets/a427b2fb-a97e-48db-9d25-1d6d1402acde" />

            Console.Write("Этаж: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a == 10)
            {
                Console.WriteLine("Высотный этаж");
            }

            49.Ввести два слова. Проверить, одинаковы ли они по длине.
<img width="1920" height="1200" alt="№49" src="https://github.com/user-attachments/assets/3948627e-56f4-4fc7-8827-53e3ab057dc0" />

            Console.Write("Первое слово: ");
            string word1 = Convert.ToString(Console.ReadLine());

            Console.Write("Второе слово: ");
            string word2 = Convert.ToString(Console.ReadLine());

            if (word1.Length == word2.Length) //Length считывает буквы, символы.
            {
                Console.WriteLine("Слова одинаковы по длине");
            }
            else
            {
                Console.WriteLine("Слова не совпадают по длине");
            }

            50.Пользователь вводит целое число.Вывести строковое сообщение: «Число четное» либо «Число нечетное».
<img width="1920" height="1200" alt="№50" src="https://github.com/user-attachments/assets/60a806a2-1bcf-4fdf-94a5-676eee9a3fe4" />

            Console.Write("введите целое число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a % 2 == 0)
            {
                Console.WriteLine("Число четное");
            }
            else
            {
                Console.WriteLine("Число нечтное");
            }

            #endregion

            #region Раздел 2. Множественные ветвления else if и диапазоны.

            51.Ввести балл за тест(0–100).Вывести оценку по шкале ECTS: A(90 - 100), B(80 - 89), C(70 - 79), D(60 - 69), F(менее 60).
<img width="1920" height="1200" alt="№51" src="https://github.com/user-attachments/assets/7b7cee6e-430a-43a9-84fe-b6915a34e706" />

            Console.Write("Балл за тест (0-100): ");
            int score = Convert.ToInt32(Console.ReadLine());

            if (score >= 90 && score <= 100)
            {
                Console.WriteLine("A");
            }
            else if (score >= 80 && score <= 89)
            {
                Console.WriteLine("B");
            }
            else if (score >= 70 && score <= 79)
            {
                Console.WriteLine("C");
            }
            else if (score >= 60 && score <= 69)
            {
                Console.WriteLine("D");
            }
            else if (score < 60)
            {
                Console.WriteLine("F");
            }

            52.Ввести возраст человека. Определить категорию: ребенок(0 - 12), подросток(13 - 17), взрослый(18 - 64), пожилой(65 +).
<img width="1920" height="1200" alt="№52" src="https://github.com/user-attachments/assets/e65c96de-dbbf-4694-9d77-f63f5f5d97f0" />

            Console.Write("Введите возраст человека: ");
            int age = Convert.ToInt32(Console.ReadLine());

            if (age >= 0 && age <= 12)
            {
                Console.WriteLine("Ребёнок");
            }
            else if (age >= 13 && age <= 17)
            {
                Console.WriteLine("Подросток");
            }
            else if (age >= 18 && age <= 64)
            {
                Console.WriteLine("Взрослый");
            }
            else if (age >= 65)
            {
                Console.WriteLine("Пожилой");
            }

            53.Ввести температуру воды. Вывести ее агрегатное состояние: «Лед» (≤0), «Жидкость» (0 < t < 100), «Пар» (≥100).
<img width="1920" height="1200" alt="№53" src="https://github.com/user-attachments/assets/bcc9bde9-df33-4805-9bd2-c49d76229499" />

            Console.Write("Введите температуру воды: ");
            int water = Convert.ToInt32(Console.ReadLine());

            if (water <= 0)
            {
                Console.WriteLine("Лед");
            }
            else if (water > 0 && water < 100)
            {
                Console.WriteLine("Жидкость");
            }
            else if (water >= 100)
            {
                Console.WriteLine("Пар");
            }

            54.Ввести уровень заряда аккумулятора смартфона(в %). Вывести: «Критический» (< 10), «Низкий» (10 - 20), «Нормальный» (21 - 80), «Полный» (81 - 100).
<img width="1920" height="1200" alt="№54" src="https://github.com/user-attachments/assets/c03207dc-3efb-4ee8-a8bb-afb3c96294d1" />

            Console.Write("Введите уровень заряда аккумулятора смартфона: ");
            int battery = Convert.ToInt32(Console.ReadLine());

            if (battery < 10)
            {
                Console.WriteLine("Критический");
            }
            else if (battery >= 10 && battery <= 20)
            {
                Console.WriteLine("Низкий");
            }
            else if (battery >= 21 && battery <= 80)
            {
                Console.WriteLine("Нормальный");
            }
            else if (battery >= 81 && battery <= 100)
            {
                Console.WriteLine("Полный");
            }

            55.Ввести число оборотов двигателя в минуту(RPM).Вывести режим: «Заглушен» (0), «Холостой ход» (1 - 900), «Рабочий» (901 - 3500), «Красная зона» (3501 +).
            Console.Write("Введите число оборотов двигателя в минуту (RPM): ");
            int ЧислоОборотов = Convert.ToInt32(Console.ReadLine());

            if (ЧислоОборотов == 0)
            {
                Console.WriteLine("Заглушен");
            }
            else if (ЧислоОборотов >= 1 && ЧислоОборотов <= 900)
            {
                Console.WriteLine("Холостой ход");
            }
            else if (ЧислоОборотов >= 901 && ЧислоОборотов <= 3500)
            {
                Console.WriteLine("Рабочий");
            }
            else if (ЧислоОборотов > 3501)
            {
                Console.WriteLine("Красная зона");
            }

            56.Ввести сумму дохода за год. Рассчитать подоходный налог: до 2.4 млн — 13 %, до 5 млн — 15 %, выше 5 млн — 18 %.
            Console.Write("Введите сумму дохода за год: ");
            double summ = Convert.ToDouble(Console.ReadLine());

            if (summ <= 2.4)
            {
                Console.WriteLine("13%");
            }
            else if (summ <= 5.0)
            {
                Console.WriteLine("15%");
            }
            else if (summ > 5.0)
            {
                Console.WriteLine("18%");
            }

            57.По введенной координате X точки на плоскости(при Y = 0) определить ее положение: на нуле, в положительной или отрицательной полуоси.
            Console.Write("Точка X: ");
            double X = Convert.ToDouble(Console.ReadLine());

            if (X == 0)
            {
                Console.WriteLine("Точка на нуле");
            }
            else if (X > 0)
            {
                Console.WriteLine("Точка находится в положительной полуоси");
            }
            else if (X < 0)
            {
                Console.WriteLine("Точка находится в отрицательной полуоси");
            }

            58.Ввести индекс массы тела(ИМТ).Вывести категорию: дефицит веса(< 18.5), норма(18.5 - 24.9), избыток(25 - 29.9), ожирение(30 +).
            Console.Write("Введите индекс массы тела (ИМТ): ");
            double m = Convert.ToDouble(Console.ReadLine());

            if (m < 18.5)
            {
                Console.WriteLine("Дефицит веса");
            }
            else if (m >= 18.5 && m <= 24.9)
            {
                Console.WriteLine("Норма");
            }
            else if (m >= 25 && m <= 29.9)
            {
                Console.WriteLine("Избыток");
            }
            else if (m > 30)
            {
                Console.WriteLine("Ожирение");
            }

            59.Ввести скорость ветра(м/ с). Вывести категорию по шкале: штиль(< 0.2), легкий ветерок(0.2 - 5), умеренный(5.1 - 14), шторм(14.1 - 24), ураган(> 24).
            Console.Write("Введите скорость ветра (м/с): ");
            double v = Convert.ToDouble(Console.ReadLine());

            if (v < 0.2)
            {
                Console.WriteLine("Штиль");
            }
            else if (v >= 0.2 && v <= 5)
            {
                Console.WriteLine("Легкий ветерок");
            }
            else if (v >= 5.1 && v <= 15)
            {
                Console.WriteLine("Умеренный");
            }
            else if (v >= 14.1 && v <= 24)
            {
                Console.WriteLine("Шторм");
            }
            else if (v > 24)
            {
                Console.WriteLine("Ураган");
            }

            60.Ввести стаж работы сотрудника(в годах).Вывести размер надбавки: < 1 года — 0 %, 1 - 5 лет — 5 %, 6 - 10 лет — 10 %, > 10 лет — 15 %.
            Console.Write("Введите стаж работы сотрудника (в годах): ");
            int experience = Convert.ToInt32(Console.ReadLine());

            if (experience < 1)
            {
                Console.WriteLine("0%");
            }
            else if (experience >= 1 && experience <= 5)
            {
                Console.WriteLine("5%");
            }
            else if (experience >= 6 && experience <= 10)
            {
                Console.WriteLine("10%");
            }
            else if (experience > 10)
            {
                Console.WriteLine("15%");
            }

            61.Пользователь вводит текущий час(0–23).Вывести: «Ночь» (0 - 5), «Утро» (6 - 11), «День» (12 - 17), «Вечер» (18 - 23).
            Console.Write("Введите текущий час (0-23): ");
            int hour = Convert.ToInt32(Console.ReadLine());

            if (hour >= 0 && hour <= 5)
            {
                Console.WriteLine("Ночь");
            }
            else if (hour >= 6 && hour <= 11)
            {
                Console.WriteLine("Утро");
            }
            else if (hour >= 12 && hour <= 17)
            {
                Console.WriteLine("День");
            }
            else if (hour >= 18 && hour <= 23)
            {
                Console.WriteLine("Вечер");
            }

            62.Ввести толщину льда на водоеме(см). Вывести: «Выход запрещен» (< 7), «Одиночный пешеход» (7 - 12), «Группа людей» (13 - 20), «Транспорт» (> 20).
            Console.Write("Введите толщину льда на водоеме (см): ");
            int толщина = Convert.ToInt32(Console.ReadLine());

            if (толщина < 7)
            {
                Console.WriteLine("Выход запрещен");
            }
            else if (толщина >= 7 && толщина <= 12)
            {
                Console.WriteLine("Одиночный пешеход");
            }
            else if (толщина >= 13 && толщина <= 20)
            {
                Console.WriteLine("Группа людей");
            }
            else if (толщина > 20)
            {
                Console.WriteLine("Транспорт");
            }

            63.Даны три целых числа A, B, C.Найти максимальное из них, используя каскадное условие.
            Console.Write("Целое число A: ");
            int A = Convert.ToInt32(Console.ReadLine());

            Console.Write("Целое число B: ");
            int B = Convert.ToInt32(Console.ReadLine());

            Console.Write("Целое число C: ");
            int C = Convert.ToInt32(Console.ReadLine());

            if (A > B && A > C)
            {
                Console.WriteLine("Число A максимальное");
            }
            else if (B > A && B > C)
            {
                Console.WriteLine("Число B максимальное");
            }
            else if (C > A && C > B)
            {
                Console.WriteLine("Число C максимальное");
            }

            64.Даны три числа. Найти минимальное из них.
            Console.Write("Первое число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            Console.Write("Второе число: ");
            int b = Convert.ToInt32(Console.ReadLine());

            Console.Write("Третье число: ");
            int c = Convert.ToInt32(Console.ReadLine());

            if (a < b && a < c)
            {
                Console.WriteLine("Первое число минимальное");
            }
            else if (b < a && b < c)
            {
                Console.WriteLine("Второе число минимальное");
            }
            else if (c < a && c < b)
            {
                Console.WriteLine("Третье число минимальное");
            }

            65.Даны три числа. Определить, сколько из них положительных(0, 1, 2 или 3).
            Console.Write("Первое число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            Console.Write("Второе число: ");
            int b = Convert.ToInt32(Console.ReadLine());

            Console.Write("Третье число: ");
            int c = Convert.ToInt32(Console.ReadLine());

            if (a > 0 && b > 0 && c > 0)
            {
                Console.WriteLine("Все ТРИ числа положительны");
            }
            else if ((a > 0) && (b > 0) && (c < 0))
            {
                Console.WriteLine("Положительны только ДВА числа");
            }
            else if ((a < 0) && (b > 0) && (c > 0))
            {
                Console.WriteLine("Положительны только ДВА числа");
            }
            else if ((a > 0) && (b < 0) && (c > 0))
            {
                Console.WriteLine("Положительны только ДВА числа");
            }
            else if ((a > 0) && (b < 0) && (c < 0))
            {
                Console.WriteLine("Положительно только ОДНО число");
            }
            else if ((a < 0) && (b > 0) && (c < 0))
            {
                Console.WriteLine("Положительно только ОДНО число");
            }
            else if ((a < 0) && (b < 0) && (c > 0))
            {
                Console.WriteLine("Положительно только ОДНО число");
            }
            else if (a < 0 && b < 0 && c < 0)
            {
                Console.WriteLine("НИ ОДНО число не положительно");
            }

            66.Ввести средний балл диплома.Вывести: «Без отличия» (< 4.5), «Претендент на красный диплом» (4.5 - 4.74), «Красный диплом» (≥4.75).
            Console.Write("Введите средний балл диплома: ");
            double среднийбалл = Convert.ToDouble(Console.ReadLine());

            if (среднийбалл < 4.5)
            {
                Console.WriteLine("Без отличия");
            }
            else if (среднийбалл >= 4.5 && среднийбалл <= 4.74)
            {
                Console.WriteLine("Претендент на красный диплом");
            }
            else if (среднийбалл >= 4.75)
            {
                Console.WriteLine("Красный диплом");
            }

            67.Ввести значение артериального давления(систолическое).Вывести: гипотония(< 90), норма(90 - 120), предгипертензия(121 - 139), гипертензия(≥140).
            Console.Write("Введите значение артериального давления (систолическое): ");
            int davlenie = Convert.ToInt32(Console.ReadLine());

            if (davlenie < 90)
            {
                Console.WriteLine("Гипотония");
            }
            else if (davlenie >= 90 && davlenie <= 120)
            {
                Console.WriteLine("Норма");
            }
            else if (davlenie >= 121 && davlenie <= 139)
            {
                Console.WriteLine("Предгипертензия");
            }
            else if (davlenie >= 140)
            {
                Console.WriteLine("Гипертензия");
            }

            68.Ввести рейтинг шахматиста(Эло). Вывести ранг: любитель(< 1400), разрядник(1400 - 1999), мастер(2000 - 2399), гроссмейстер(≥2400).
            Console.Write("Введите рейтинг шахматиста (Эло): ");
            int reiting = Convert.ToInt32(Console.ReadLine());

            if (reiting < 1400)
            {
                Console.WriteLine("Любитель");
            }
            else if (reiting >= 1400 && reiting <= 1999)
            {
                Console.WriteLine("Разрядник");
            }
            else if (reiting >= 2000 && reiting <= 2399)
            {
                Console.WriteLine("Мастер");
            }
            else if (reiting >= 2400)
            {
                Console.WriteLine("Гроссмейстер");
            }

            69.Ввести число и определить, сколькизначным оно является(однозначное, двузначное, трехзначное или более).
            Console.Write("Введите число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if (number < 10)
            {
                Console.WriteLine("однозначное");
            }
            else if (number < 100)
            {
                Console.WriteLine("двузначное");
            }
            else if (number < 1000)
            {
                Console.WriteLine("трехзначное");
            }
            else if (number < 10000)
            {
                Console.WriteLine("четырехзначное");
            }

            70.Ввести дальность поездки на такси(км). Рассчитать тариф: до 5 км — 200 руб, от 5 до 15 км — 200 + 25 руб / км, свыше 15 км — 200 + 20 руб / км.
            Console.Write("Введите дальность поездки на такси (км): ");
            int S = Convert.ToInt32(Console.ReadLine());

            if (S < 5)
            {
                Console.WriteLine("200 руб");
            }
            else if (S >= 5 && S <= 15)
            {
                Console.WriteLine("200 + 25 руб/км");
            }
            else if (S > 15)
            {
                Console.WriteLine("200 + 20 руб/км");
            }

            71.Ввести количество осадков за сутки(мм). Определить: без осадков(0), слабый дождь(0.1 - 4), умеренный(4.1 - 15), сильный ливень(> 15).
            Console.Write("Введите количество осадков за сутки (мм): ");
            double осадки = Convert.ToDouble(Console.ReadLine());

            if (осадки == 0)
            {
                Console.WriteLine("Без осадков");
            }
            else if (осадки >= 0.1 && осадки <= 4)
            {
                Console.WriteLine("Слабый дождь");
            }
            else if (осадки >= 4.1 && осадки <= 15)
            {
                Console.WriteLine("Умеренный");
            }
            else if (осадки > 15)
            {
                Console.WriteLine("Сильный ливень");
            }

            72.Ввести процент выполнения плана продаж. Вывести статус: план сорван(< 70), удовлетворительно(70 - 99 %), выполнен(100 - 119 %), перевыполнен(≥120).
            Console.Write("Введите процент выполнения плана продаж: ");
            int percent = Convert.ToInt32(Console.ReadLine());

            if (percent < 70)
            {
                Console.WriteLine("План сорван");
            }
            else if (percent >= 70 && percent <= 99)
            {
                Console.WriteLine("Удовлетворительно");
            }
            else if (percent >= 100 && percent <= 119)
            {
                Console.WriteLine("Выполнен");
            }
            else if (percent >= 120)
            {
                Console.WriteLine("Перевыполнен");
            }

            73.Даны три числа. Упорядочить их по возрастанию и вывести на консоль.
            Console.Write("Первое число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            Console.Write("Второе число: ");
            int b = Convert.ToInt32(Console.ReadLine());

            Console.Write("Третье число: ");
            int c = Convert.ToInt32(Console.ReadLine());

            //сравниваем a и b
            if (a > b)
            {
                int idk = a;
                a = b;
                b = idk;
            }
            //сравниваем b и c
            if (b > c)
            {
                int idk = b;
                b = c;
                c = idk;
            }
            //снова сравниваем a и b на всякий случай
            if (a > b)
            {
                int idk = a;
                a = b;
                b = idk;
            }
            Console.WriteLine("Числа в порядке возрастания:");
            Console.WriteLine(a);
            Console.WriteLine(b);
            Console.WriteLine(c);

            74.Дано число X.Вычислить значение кусочно - заданной функции: f(x) = x2, если x> 0; f(x) = 0, если x = 0; f(x) =−x, еслиx < 0.
            Console.Write("x: ");
            int x = Convert.ToInt32(Console.ReadLine());

            if (x == 0)
            {
                Console.WriteLine("f(x)=0");
            }
            else if (x > 0)
            {
                int result = x * 2; Console.WriteLine($"f(x)={result}");
            }
            else if (x < 0)
            {
                x = -x; Console.WriteLine($"f(x)={-x}");
            }

            75.Ввести октановое число бензина.Классифицировать: < 92— несоответствие стандарту, 92 — АИ - 92, 95 — АИ - 95, 98 - 100 — АИ - 98 / 100, > 100— спорт / авиатопливо.
            Console.Write("Введите октановое число бензина: ");
            int n = Convert.ToInt32(Console.ReadLine());

            if (n < 92)
            {
                Console.WriteLine("несоответствие стандарту");
            }
            else if (n == 92)
            {
                Console.WriteLine("АИ-92");
            }
            else if (n == 95)
            {
                Console.WriteLine("АИ-95");
            }
            else if (n == 98 && n == 100)
            {
                Console.WriteLine("АИ-98/100");
            }
            else if (n > 100)
            {
                Console.WriteLine("спорт/авиатопливо");
            }

            76.Ввести сумму покупок за месяц для начисления кешбэка: до 10 000 руб — 1 %, до 50 000 руб — 3 %, свыше 50 000 руб — 5 %.Вывести сумму кешбэка.
            Console.Write("Введите сумму покупок за месяц для начисления кешбэка: ");
            double summ = Convert.ToDouble(Console.ReadLine());

            if (summ < 10000)
            {
                double result = summ * 0.01; Console.WriteLine($"Сумма кэшбека: {result}");
            }
            else if (summ < 50000)
            {
                double result = summ * 0.03; Console.WriteLine($"Сумма кэшбека: {result}");
            }
            else if (summ > 50000)
            {
                double result = summ * 0.05; Console.WriteLine($"Сумма кэшбека: {result}");
            }

            77.Ввести глубину погружения аквалангиста(метры).Вывести зону: рекреационная(< 40), техническая(40 - 100), глубоководная(> 100)
            Console.Write("Введите глубину погружения аквалангиста (метры): ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a < 40)
            {
                Console.WriteLine("рекреационная");
            }
            else if (a >= 40 && a <= 100)
            {
                Console.WriteLine("техническая");
            }
            else if (a > 100)
            {
                Console.WriteLine("глубоководная");
            }

            78.Ввести количество штрафных баллов водителя. Вывести: «Предупреждение» (1 - 5), «Временное ограничение» (6 - 10), «Лишение прав» (> 10).
            Console.Write("Введите количество штрафных баллов водителя: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a >= 1 && a <= 5)
            {
                Console.WriteLine("Предупреждение");
            }
            else if (a >= 6 && a <= 10)
            {
                Console.WriteLine("Временное ограничение");
            }
            else if (a > 10)
            {
                Console.WriteLine("Лишение прав");
            }

            79.Ввести уровень кислотности почвы(pH).Определить: кислая(< 6.0), нейтральная(6.0 - 7.2), щелочная(> 7.2).
            Console.Write("Введите уровень кислотности почвы (pH) : ");
            double a = Convert.ToDouble(Console.ReadLine());

            if (a < 0.6)
            {
                Console.WriteLine("кислая");
            }
            else if (a >= 6.0 && a <= 7.2)
            {
                Console.WriteLine("нейтральная");
            }
            else if (a > 7.2)
            {
                Console.WriteLine("щелочная");
            }

            80.Ввести количество набранных очков в компьютерной игре. Присвоить медаль: Бронзовая(1000 - 2499), Серебряная(2500 - 4999), Золотая(5000 +), иначе без медали.
            Console.Write("Введите количество набранных очков в компьютерной игре: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a >= 1000 && a <= 2499)
            {
                Console.WriteLine("Бронзовая");
            }
            else if (a >= 2500 && a <= 4999)
            {
                Console.WriteLine("Серебряная");
            }
            else if (a >= 5000)
            {
                Console.WriteLine("Золотая");
            }
            else
            {
                Console.WriteLine("Без медали");
            }

            81.Ввести крепость напитка в градусах. Классифицировать: безалкогольный(0), слабоалкогольный(0.1 - 8), среднеалкогольный(8.1 - 25), крепкий(> 25).
            Console.Write("Введите крепость напитка в градусах: ");
            double a = Convert.ToDouble(Console.ReadLine());

            if (a == 0)
            {
                Console.WriteLine("безалкогольный");
            }
            else if (a >= 0.1 && a <= 8)
            {
                Console.WriteLine("слабоалкогольный");
            }
            else if (a >= 8.1 && a <= 25)
            {
                Console.WriteLine("среднеалкогольный");
            }
            else if (a > 25)
            {
                Console.WriteLine("крепкий");
            }

            82.Ввести показатель уровня шума в децибелах(дБ).Вывести вердикт: тихо(< 40), норма(40 - 60), шумно(61 - 80), вредно для здоровья(> 80).
            Console.Write("Введите показатель уровня шума в децибелах (дБ): ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a < 40)
            {
                Console.WriteLine("тихо");
            }
            else if (a >= 40 && a <= 60)
            {
                Console.WriteLine("норма");
            }
            else if (a >= 61 && a <= 80)
            {
                Console.WriteLine("шумно");
            }
            else if (a > 80)
            {
                Console.WriteLine("вредно для здоровья");
            }

            83.Ввести вес почтовой посылки(кг).Рассчитать категорию отправления: мелкий пакет(< 2), стандартная(2 - 10), тяжеловесная(10.1 - 31.5), крупногабарит(> 31.5).
            Console.Write("Введите вес почтовой посылки (кг): ");
            double a = Convert.ToDouble(Console.ReadLine());

            if (a < 2)
            {
                Console.WriteLine("мелкий пакет");
            }
            else if (a >= 2 && a <= 10)
            {
                Console.WriteLine("стандартная");
            }
            else if (a >= 10.1 && a <= 31.5)
            {
                Console.WriteLine("тяжеловесная");
            }
            else if (a > 31.5)
            {
                Console.WriteLine("крупногабарит");
            }

            84.Ввести количество комнат в квартире. Вывести: студия / однокомнатная(1), двухкомнатная(2), трехкомнатная(3), многокомнатная(4 +).
            Console.Write("Введите количество комнат в квартире: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a == 1)
            {
                Console.WriteLine("студия/однокомнатная");
            }
            else if (a == 2)
            {
                Console.WriteLine("двухкомнатная");
            }
            else if (a == 3)
            {
                Console.WriteLine("трехкомнатная");
            }
            else if (a >= 4)
            {
                Console.WriteLine("многокомнатная");
            }

            85.Ввести процент заряда повербанка.Вывести количество светящихся светодиодов на корпусе(1, 2, 3 или 4).
            –25 % → 0 светодиодов
            25–50 % → 1 светодиод
            50–75 % → 2 светодиода
            75–100 % → 3 светодиода
            100 % → 4 светодиод


            Console.Write("Введи процент заряда: ");
            string text = Console.ReadLine();

            if (int.TryParse(text, out int percent)) //переводим переменную text в int и задаем ей новое имя
            {
                int leds = 0;

                if (percent >= 100) leds = 4; //Если процент больше или равен 100, то пусть leds станет равен 4.
                else if (percent >= 75) leds = 3;
                else if (percent >= 50) leds = 2;
                else if (percent >= 25) leds = 1;

                Console.WriteLine("Горит светодиодов: " + leds);
            }

            86.Ввести выслугу лет военнослужащего.Вывести процент пенсионной надбавки.

            до 5 лет — 0 %
            от 5 до 10 лет — 10 %
            от 10 до 15 лет — 15 %
            от 15 до 20 лет — 20 %
            20 и больше — 30 %

            Console.Write("Введите выслугу лет военнослужащего: ");
            double percent = Convert.ToDouble(Console.ReadLine());

            if (percent < 5)
            {
                Console.WriteLine("0%");
            }
            else if (percent >= 5 && percent <= 10)
            {
                Console.WriteLine("10%");
            }
            else if (percent >= 10.1 && percent <= 15)
            {
                Console.WriteLine("15%");
            }
            else if (percent >= 15.1 && percent <= 20)
            {
                Console.WriteLine("20%");
            }
            else if (percent >= 20)
            {
                Console.WriteLine("30%");
            }

            87.Ввести время отклика сервера(пинг в мс).Вывести: идеальный(< 20), хороший(20 - 60), посредственный(61 - 120), плохой(> 120).
            Console.Write("Введите время отклика сервера (пинг в мс): ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a < 20)
            {
                Console.WriteLine("идеальный");
            }
            else if (a >= 20 && a <= 60)
            {
                Console.WriteLine("хороший");
            }
            else if (a >= 61 && a <= 120)
            {
                Console.WriteLine("посредственный");
            }
            else if (a > 120)
            {
                Console.WriteLine("плохой");
            }

            88.Ввести концентрацию CO2 в помещении(ppm). Вывести вердикт: норма(< 800), душно(800 - 1200), проветрить немедленно(> 1200).
            Console.Write("Введите концентрацию CO2 в помещении (ppm): ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a < 800)
            {
                Console.WriteLine("норма");
            }
            else if (a >= 800 && a <= 1200)
            {
                Console.WriteLine("душно");
            }
            else if (a > 1200)
            {
                Console.WriteLine("проветрить немедленно");
            }

            89.Ввести количество пройденных шагов за день.Вывести: гиподинамия(< 5000), норма(5000 - 9999), активный день(10000 - 14999), рекорд(> 15000).
            Console.Write("Введите количество пройденных шагов за день: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a < 5000)
            {
                Console.WriteLine("гиподамия");
            }
            else if (a >= 5000 && a <= 9999)
            {
                Console.WriteLine("норма");
            }
            else if (a >= 10000 && a <= 14999)
            {
                Console.WriteLine("активный день");
            }
            else if (a >= 15000)
            {
                Console.WriteLine("рекорд");
            }

            90.Ввести диаметр автомобильного колесного диска в дюймах. Определить класс: малолитражки(13 - 14), компактные авто(15 - 16), кроссоверы / бизнес(17 - 19), внедорожники / спорт(20 +).
            Console.Write("Введите диаметр автомобильного колесного диска в дюймах: ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a == 13 && a == 14)
            {
                Console.WriteLine("малолитражки");
            }
            else if (a == 15 && a == 16)
            {
                Console.WriteLine("компактные авто");
            }
            else if (a >= 17 && a <= 19)
            {
                Console.WriteLine("кроссоверы/бизнес");
            }
            else if (a >= 20)
            {
                Console.WriteLine("внедорожники/спорт");
            }

            91.Ввести значение влажности воздуха(%).Вывести: сухой воздух(< 30), комфорт(30 - 60), повышенная влажность(> 60).
            Console.Write("Введите значение влажности воздуха (%): ");
            int a = Convert.ToInt32(Console.ReadLine());

            if (a < 30)
            {
                Console.WriteLine("сухой воздух");
            }
            else if (a >= 30 && a <= 60)
            {
                Console.WriteLine("комфорт");
            }
            else if (a > 60)
            {
                Console.WriteLine("повышенная влажность");
            }

            92.Даны три числа. Проверить, сколько из них равны между собой(все разные, два равны, все три равны).
            Console.Write("Первое число: ");
            int a = Convert.ToInt32(Console.ReadLine());

            Console.Write("Второе число: ");
            int b = Convert.ToInt32(Console.ReadLine());

            Console.Write("Третье число: ");
            int c = Convert.ToInt32(Console.ReadLine());

            if (a == b && b == c && c == a)
            {
                Console.WriteLine("Все числа равны");
            }
            else if (a != b && b != c && c != a)
            {
                Console.WriteLine("Все числа разные");
            }
            else if (a == b && b == a)
            {
                Console.WriteLine("Два числа равны");
            }
            else if (b == c && c == b)
            {
                Console.WriteLine("Два числа равны");
            }
            else if (a == c && c == a)
            {
                Console.WriteLine("Два числа равны");
            }

            93.Ввести номер четверти координатной плоскости(1–4) и вывести диапазоны знаков для координат X и Y.
            Console.Write("Введите номер четверти (1–4): ");
            int q = Convert.ToInt32(Console.ReadLine());

            if (q == 1)
            {
                Console.WriteLine("1 четверть: X > 0, Y > 0");
            }
            else if (q == 2)
            {
                Console.WriteLine("2 четверть: X < 0, Y > 0");
            }
            else if (q == 3)
            {
                Console.WriteLine("3 четверть: X < 0, Y < 0");
            }
            else if (q == 4)
            {
                Console.WriteLine("4 четверть: X > 0, Y < 0");
            }
            else
            {
                Console.WriteLine("Ошибка: вводи число от 1 до 4.");
            }

            94.Ввести температуру процессора компьютера.Вывести: холодный(< 45), нормальная нагрузка(45 - 75), троттлинг / перегрев(> 75).
            Console.Write("Введите температуру процессора компьютера: ");
            int t = Convert.ToInt32(Console.ReadLine());

            if (t < 45)
            {
                Console.WriteLine("холодный");
            }
            else if (t >= 45 && t <= 75)
            {
                Console.WriteLine("нормальная нагрузка");
            }
            else if (t > 75)
            {
                Console.WriteLine("троттлинг/перегрев");
            }

            95.Ввести остаток срока годности продукта в днях. Вывести: «Срочно употребить» (≤2), «Нормально» (3 - 30), «Длительное хранение» (> 30).
            Console.Write("Введите остаток срока годности продукта в днях: ");
            int t = Convert.ToInt32(Console.ReadLine());

            if (t <= 2)
            {
                Console.WriteLine("Срочно употребить");
            }
            else if (t >= 3 && t <= 30)
            {
                Console.WriteLine("Нормально");
            }
            else if (t > 30)
            {
                Console.WriteLine("Длительное хранение");
            }

            96.Ввести сумму кредита и срок. Рассчитать процентную ставку в зависимости от срока(до года, до трех лет, свыше трех лет).
            Console.Write("Введите сумму кредита: ");
            double summ = Convert.ToDouble(Console.ReadLine());

            Console.Write("Введите срок кредита: ");
            int years = Convert.ToInt32(Console.ReadLine());

            double rate;

            if (years <= 1)
            {
                rate = 20; Console.WriteLine($"Процентная ставка: {rate}");
            }
            else if (years <= 3)
            {
                rate = 18; Console.WriteLine($"Процентная ставка: {rate}");
            }
            else
            {
                rate = 16; Console.WriteLine($"Процентная ставка: {rate}");
            }

            97.Ввести частоту обновления монитора(Гц).Определить: офис(60 - 75), базовый игровой(120 - 144), киберспорт(165 +).
            Console.Write("Введите частоту обновления монитора (Гц): ");
            int g = Convert.ToInt32(Console.ReadLine());

            if (g >= 60 && g <= 75)
            {
                Console.WriteLine("офис");
            }
            else if (g >= 120 && g <= 144)
            {
                Console.WriteLine("базовый игровой");
            }
            else if (g > 165)
            {
                Console.WriteLine("киберспорт");
            }

            98.Ввести расход топлива автомобиля на 100 км пути. Вывести вердикт: экономичный(< 6л), средний(6 - 10 л), прожорливый(> 10л).
            Console.Write("Введите расход топлива автомобиля на 100 км пути: ");
            int toplivo = Convert.ToInt32(Console.ReadLine());

            if (toplivo < 6)
            {
                Console.WriteLine("экономичный");
            }
            else if (toplivo >= 6 && toplivo <= 10)
            {
                Console.WriteLine("средний");
            }
            else if (toplivo > 10)
            {
                Console.WriteLine("прожорливый");
            }

            99.Ввести количество страниц книги.Классифицировать: брошюра(< 48), повесть(48 - 150), роман(151 - 600), фолиант(> 600).
            Console.Write("Введите количество страниц книги: ");
            int kolichestvo = Convert.ToInt32(Console.ReadLine());

            if (kolichestvo < 48)
            {
                Console.WriteLine("брошюра");
            }
            else if (kolichestvo >= 48 && kolichestvo <= 150)
            {
                Console.WriteLine("повесть");
            }
            else if (kolichestvo >= 151 && kolichestvo <= 600)
            {
                Console.WriteLine("роман");
            }
            else if (kolichestvo > 600)
            {
                Console.WriteLine("фолиант");
            }

            100.Ввести число и проверить, попадает ли оно в интервалы[0; 10], [20; 30] или[50; 100].
            Console.Write("Число: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if (number >= 0 && number <= 10)
            {
                Console.WriteLine("Число попало в интервалы [0;10]");
            }
            else if (number >= 20 && number <= 30)
            {
                Console.WriteLine("Число попало в интервалы [20;30]");
            }
            else if (number >= 50 && number <= 100)
            {
                Console.WriteLine("Число попало в интервалы [50;100]");
            }

            #endregion

            #region Раздел 3. Составные логические условия &&, ||, !

            101.Дано целое число. Проверить, принадлежит ли оно числовому отрезку[10; 50].
            Console.Write("Введите целое число: ");
            int n = Convert.ToInt32(Console.ReadLine());

            if (n >= 10 && n <= 50)
            {
                Console.WriteLine("Число принадлежит числовому отрезку [10;50]");
            }
            else
            {
                Console.WriteLine("Число НЕ принадлежит числовому отрезку [10;50]");
            }

            102.Проверить, является ли введенное целое число положительным и четным одновременно.
            Console.Write("Введите целое число: ");
            int n = Convert.ToInt32(Console.ReadLine());

            if (n > 0 && n % 2 == 0)
            {
                Console.WriteLine("Число является положительным и четным одновременно");
            }
            else
            {
                Console.WriteLine("Число НЕ является положительным и четным одновременно");
            }

            103.Проверить, лежит ли число вне диапазона[−10; 10].
            Console.Write("Введите число: ");
            int n = Convert.ToInt32(Console.ReadLine());

            if (n >= -10 && n >= 10)
            {
                Console.WriteLine("Число лежит вне диапазона [-10;10]");
            }
            else
            {
                Console.WriteLine("Число лежит в зоне диапазона [-10;10]");
            }

            104.Ввести логин и пароль пользователя. Вывести «Успех», если логин равен admin и пароль secret.
            Console.Write("Логин: ");
            string login = Convert.ToString(Console.ReadLine());

            Console.Write("Пароль: ");
            string password = Convert.ToString(Console.ReadLine());

            if (login == "admin" && password == "secret")
            {
                Console.WriteLine("Успех");
            }
            else
            {
                Console.WriteLine("Провал");
            }

            105.Проверить, является ли введенный год високосным(делится на 4, но не на 100, либо делится на 400).
            Console.Write("Год: ");
            int year = Convert.ToInt32(Console.ReadLine());

            if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0))
            {
                Console.WriteLine("Год является високосным");
            }
            else
            {
                Console.WriteLine("Год НЕ является високосным");
            }

            106.Даны координаты точки(X, Y).Определить, попадает ли точка в I координатную четверть(X > 0 и Y > 0).
            Console.Write("Введите X: ");
            double X = Convert.ToDouble(Console.ReadLine());

            Console.Write("Введите Y: ");
            double Y = Convert.ToDouble(Console.ReadLine());

            if (X > 0 && Y > 0)
            {
                Console.WriteLine("Точка попадает в I координатную четверть");
            }
            else
            {
                Console.WriteLine("Точка НЕ попадает в I координатную четверть");
            }

            107.Определить, попадает ли точка(X, Y)во II четверть плоскости.
            Console.Write("Введите X: ");
            double X = Convert.ToDouble(Console.ReadLine());

            Console.Write("Введите Y: ");
            double Y = Convert.ToDouble(Console.ReadLine());

            if (X < 0 && Y > 0)
            {
                Console.WriteLine("Точка попадает в II координатную четверть");
            }
            else
            {
                Console.WriteLine("Точка НЕ попадает в II координатную четверть");
            }

            108.Определить, попадает ли точка(X, Y)во III четверть плоскости.
            Console.Write("Введите X: ");
            double X = Convert.ToDouble(Console.ReadLine());

            Console.Write("Введите Y: ");
            double Y = Convert.ToDouble(Console.ReadLine());

            if (X < 0 && Y < 0)
            {
                Console.WriteLine("Точка попадает в III координатную четверть");
            }
            else
            {
                Console.WriteLine("Точка НЕ попадает в III координатную четверть");
            }

            109.Определить, попадает ли точка(X, Y)во IV четверть плоскости.
            Console.Write("Введите X: ");
            double X = Convert.ToDouble(Console.ReadLine());

            Console.Write("Введите Y: ");
            double Y = Convert.ToDouble(Console.ReadLine());

            if (X > 0 && Y < 0)
            {
                Console.WriteLine("Точка попадает в IV координатную четверть");
            }
            else
            {
                Console.WriteLine("Точка НЕ попадает в IV координатную четверть");
            }


            #region Не поняла

            110.Даны три стороны A, B, C.Проверить, является ли треугольник прямоугольным(теорема Пифагора).
            Console.Write("Сторона A: ");
            double A = Convert.ToDouble(Console.ReadLine());

            Console.Write("Сторона B: ");
            double B = Convert.ToDouble(Console.ReadLine());

            Console.Write("Сторона C: ");
            double C = Convert.ToDouble(Console.ReadLine());

            #endregion

            111.

            #endregion
        }
    }
}
