# Практическая работа 06 по предмету МДК 02.02
![MarkdownLogo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/360px-Markdown-mark.svg.png "Логотип Markdown")

## Что такое Markdown?
**Markdown** — язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его _читаемости_ человеком.

### История Markdown
Первоначально создан в 2004 году Джоном Грубером и Аароном Шварцем. Многие идеи языка были позаимствованы из существующих соглашений по разметке текста в электронных письмах. Реализации языка Markdown преобразуют текст в формате Markdown в правильно построенный ~~XHTML~~ и заменяют левые угловые скобки («<») и амперсанды («&») на соответствующие коды сущностей. Первой реализацией Markdown стала написанная Грубером реализация на Perl, однако спустя некоторое время появилось множество реализаций от сторонних разработчиков.

С помощью этого языка разметки можно:
+ Выделять блоки кода: 
``` C++
#include <iostream>

int main(){
  std::cout << "Hello world" << endl;
  return 0;
}
```

+ Создавать таблицы:


|Столбец 1|Столбец 2|Столбец 3|
|---------|:-------:|--------:|
|text01   |text02   |text03   |

+ Прикреплять ссылки:
[Google](https://www.google.com), [Stackoverflow](https://stackoverflow.com/), [CyberForum](https://www.cyberforum.ru/)

+ Использовать разнообразные эмодзи:
M⬇️, 💾, :trollface:
