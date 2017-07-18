# You Don't Know JS: Async & Performance
# Foreword
# Предисловие

Over the years, my employer has trusted me enough to conduct interviews. If we're looking for someone with skills in JavaScript, my first line of questioning… actually that's not true, I first check if the candidate needs the bathroom and/or a drink, because comfort is important, but once I'm past the bit about the candidate's fluid in/out-take, I set about determining if the candidate knows JavaScript, or just jQuery.

На протяжении многих лет мой работодатель доверял мне достаточно, чтобы проводить собеседования. Если мы ищем кого-то с навыками в JavaScript, моя первая строка вопроса ... на самом деле это неверно, я сначала проверяю, нуждается ли кандидат в ванной и / или напитке, потому что комфорт важен, но как только я пройду мимо Бит о жидкости кандидата в / из-за, я решил определить, знает ли кандидат JavaScript или просто jQuery.

Not that there's anything wrong with jQuery. It lets you do a lot without really knowing JavaScript, and that's a feature not a bug. But if the job calls for advanced skills in JavaScript performance and maintainability, you need someone who knows how libraries such as jQuery are put together. You need to be able to harness the core of JavaScript the same way they do.

Не то, чтобы что-то не так с jQuery. Это позволяет вам делать многое, не зная JavaScript, и это особенность, а не ошибка. Но если работа требует передовых навыков в производительности JavaScript и ремонтопригодности, вам нужен кто-то, кто знает, как объединяются библиотеки, такие как jQuery. Вы должны уметь использовать ядро JavaScript так же, как и они.

If I want to get a picture of someone's core JavaScript skill, I'm most interested in what they make of closures (you've read that book of this series already, right?) and how to get the most out of asynchronicity, which brings us to this book.

Если я хочу получить изображение чьего-то базового навыка JavaScript, меня больше всего интересует то, что они делают с закрытием (вы уже прочитали эту книгу этой серии, верно?) И как извлечь максимальную выгоду из асинхронности, которая Приводит нас к этой книге.

For starters, you'll be taken through callbacks, the bread and butter of asynchronous programming. Of course, bread and butter does not make for a particularly satisfying meal, but the next course is full of tasty tasty promises!

Для начала вы будете получать обратные вызовы, "хлеб и масло" асинхронного программирования. Конечно, хлеб и масло не приносят особенного удовлетворения, но следующий курс полон вкусных вкусных обещаний!

If you don't know promises, now is the time to learn. Promises are now the official way to provide async return values in both JavaScript and the DOM. All future async DOM APIs will use them, many already do, so be prepared! At the time of writing, Promises have shipped in most major browsers, with IE shipping soon. Once you've finished that, I hope you left room for the next course, Generators.

Если вы не знаете обещаний, сейчас самое время учиться. Посылы теперь являются официальным способом предоставления возвращаемых значений async как в JavaScript, так и в DOM. Все будущие API асинхронных DOM будут использовать их, многие уже делают, поэтому будьте готовы! На момент написания обещания были отправлены в большинстве основных браузеров с доставкой IE в ближайшее время. Как только вы закончите это, я надеюсь, вы оставили место для следующего курса «Генераторы».

Generators snuck their way into stable versions of Chrome and Firefox without too much pomp and ceremony, because, frankly, they're more complicated than they are interesting. Or, that's what I thought until I saw them combined with promises. There, they become an important tool in readability and maintenance.

Генераторы прокладывают себе путь в стабильные версии Chrome и Firefox без слишком высокой помпы и церемонии, потому что, честно говоря, они сложнее, чем они интересны. Или это то, о чем я думал, пока не увидел их в сочетании с обещаниями. Там они становятся важным инструментом в удобочитаемости и техническом обслуживании.

For dessert, well, I won't spoil the surprise, but prepare to gaze into the future of JavaScript! Features that give you more and more control over concurrency and asynchronicity.

На десерт, ну, я не буду удивлять сюрпризом, но приготовьтесь взглянуть в будущее JavaScript! Особенности, которые дают вам все больше контроля над параллелизмом и асинхронностью.

Well, I won't block your enjoyment of the book any longer, on with the show! If you've already read part of the book before reading this Foreword, give yourself 10 asynchronous points! You deserve them!

Ну, я больше не буду блокировать ваше удовольствие от книги, с шоу! Если вы уже прочитали часть книги, прежде чем читать это Предисловие, дайте себе 10 асинхронных точек! Вы их заслуживаете!

Jake Archibald<br>
[jakearchibald.com](http://jakearchibald.com), [@jaffathecake](http://twitter.com/jaffathecake)<br>
Developer Advocate at Google Chrome

Джейк Арчибальд 
[Jakearchibald.com] (http://jakearchibald.com), 
[@jaffathecake] (http://twitter.com/jaffathecake) 
Адвокат разработчика в Google Chrome
