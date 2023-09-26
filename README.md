# 2022-computer-games-sales
Анализ мирового рынка продаж компьютерных игр

# **ПРОЕКТ «Интернет-магазин „Стримчик‟»**

---

## **Примененные библиотеки**

* Pandas, Numpy, Random, Matplotlib, Seaborn, Scipy

---

## **Цель и задачи проекта**

**Цель**: на основе исследования информации из открытых источников (данные о продаже компьютерных игр в ретроспективе, оценках пользователей и экспертов, жанрах и платформах) выявить факторы и закономерности, определяющие успех выпуска компьютерной игры при планировании вывода на рынок новой компьютерной игры и оптимизации бюджета рекламной компании.

**Задачи**:

* изучена общая информация об имеющемся в распоряжении датасете;

* проведена предобработка данных датасета для последующего анализа (устранены дубликаты, пропуски, изучены выбросы в данных и др.);

* проведен исследовательский анализ данных (изучены различные характеристики компьютерных игр и платформ, показатели продаж и др.);

* составлен потрет пользователя компьютерных игр, характерный для различных регионов планеты (Северная Америка, Европейский Союз, Япония);

* проверены две гипотезы: о средних пользовательских рейтингах платформ и о средних пользовательских рейтингах жанров;

* сформированы выводы и рекомендации, направленные на повышение эффективности разработки и вывода на рынок новых компьютерных игр.

---

## **Основные результаты**

**(1)** с учетом анализа динамики количества выпуска компьютерных игр по всем платформам, динамики продаж копий компьютерных игр по всем платформам и по каждой из представленных в датасете 31-й платформе в отдельности актуальный период для анализа определен в 6 лет (2011-2016 годы). Ключевыми для анализа стали платформы 'PS4', 'PC', '3DS', 'XOne', 'WiiU', 'PSV', пик деятельности которых пришелся на указанный актуальный период;

**(2)** лидерами продаж являются жанры: 'Shooter' (1.22 млн. проданных копий в среднем на одну игру); 'Platform' (0.72 млн. проданных копий в среднем на одну игру); 'Sports' (0.6 млн. проданных копий в среднем на одну игру); 'Role-Playing' (0.52 млн. проданных копий в среднем на одну игру); 'Racing' (0.48 млн. проданных копий в среднем на одну игру);

**(3)** в 2011-2016 годах вывод на рынок игры в любом из жанров: 'Action', 'Shooter', 'Role-Playing', 'Sports' и 'Simulation' – позволил потенциально охватить рынки одновременно Северной Америки, Европейского союза и Японии;

**(4)**  Северная Америка, Европейский Союз и объединенный регион «Другие» практически не различаются по структуре продаж в зависимости от рейтинга ESRB: примерно 20% игр не имеют возрастных ограничений, порядка 10% игр предназначены для детей до 10 лет, от 13 до 14% игр скрашивают досуг подростков старше 13 лет, на взрослую аудиторию ориентирована треть всех продаваемых копий компьютерных игр. Соответственно, в Северной Америке, Европейском Союзе и регионах категории «Другие» самый большой охват аудитории дают «игры для взрослых». Неоднозначна ситуация с Японией. Очень большое число пропущенных значений (58% против примерно 22% для трех рассмотренных выше регионов) не позволяет сформулировать релевантные выводы относительно влияния рейтинга ESRB на продажи компьютерных игр в этой стране. В Японии с 2002 года действует собственная некоммерческая ассоциация, присваивающая возрастные ограничения для компьютерных игр: Computer Entertainment Rating Organization. Учитывая, что рынок компьютерных игр в Японии показывает быстрый рост в актуальном периоде, продажи в Японии представляют несомненный интерес, но требуется дополнительное исследование структуры внутреннего японского рынка компьютерных игр с точки зрения возраста пользовательской аудитории и возможных требований по представлению компьютерной игры на обязательную экспертизу в Computer Entertainment Rating Organization.
