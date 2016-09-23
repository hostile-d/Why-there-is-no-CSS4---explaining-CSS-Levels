# Почему нет и не будет CSS4 - толкование "CSS Levels"
Источник: https://rachelandrew.co.uk/archives/2016/09/13/why-there-is-no-css4-explaining-css-levels/

У нас есть CSS1 и CSS2. У нас есть даже CCS2.1, после чего мы перешли к CCS3 - но так ли это? Этот пост - краткое пояснение того, как сейчас именуются версии CSS.

CSS первой и второй версии были монолитными спецификациями. Все подразделы CSS составляли единый массивный документ. Селекторы, позиционирование, цвета - все было в одном месте.

Проблема монолитных спецификаций состоит в том, что для того, чтобы завиршить ее, сначала нужно завершить все ее составляющие. Когда CSS стало настолько комплексным, что, добавляя новые фишки, стало бесмысленно останавливать всю работу и завялять о выходе новой версии. По этому, после выхода CSS2.1 все фишки спецификации 2.1 были разбиты на модули. По мере того, как создавались новые CSS модули, все что были ранее, плюс некоторые новые фичи, все они вошли в Level 3. 

Если относить все новые CSS к CSS3 - это не будет в действительности отражать то, чем является CSS сегодня. Если вы прочитаете что-нибудь про CSS селекторы, то все, что вы увидете - это часть спецификации  [CSS Selectors Level 3](https://www.w3.org/TR/css3-selectors/). По факту это все будет документ отмеченый, как завершенный и рекомендованый. Сейчас же, рабочая группа CSS занята разработкой [Selectors Level 4](https://drafts.csswg.org/selectors-4/) предлагающие новые возможности, а так же включающая старые селекторы из CSS1 и CSS2. Но это не CSS4, это лишь Level 4 всей спецификации, лишь маленькая часть CSS.

У нас так же есть спецификации для новых фишек, которых не было ни в CSS1, ни в CSS2, и эти спецификации находятся на Level 1. Они совершенно новые. Премером спецификации Level 1 может служить [CSS Grid](https://drafts.csswg.org/css-grid/) и [Flexbox](https://www.w3.org/TR/css-flexbox-1/). Flexbox уже отмечен, как рекомендованый к применению. Grid тоже перешел на этот уровень. Поэтому любые новые возможности, которые предлагаются в данный момент, вероятно, в конечном итоге попадут уже в следующий уровень этих спецификаций - Flexbox Level 2 и CSS Grid Level 2.

Если вы хотите узнать какой статус у той или иной фишки в CSS и уровень, к которому они относятся, посмотрите в [текущем рабочем документе](https://www.w3.org/Style/CSS/current-work) рабочей группы CSS. Что бы понять разницу в статусах, через которые проходит спецификация, посмотрите информацию в разделе [Статуса готовности](https://www.w3.org/2005/10/Process-20051014/tr#maturity-levels) на странице текущего рабочего протокола группы.