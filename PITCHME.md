#HSLIDE

## Защо Elixir?
![Image-Absolute](assets/open-fest.png)

#HSLIDE
![Image-Absolute](assets/elixir-logo.png)

#HSLIDE
### Кой съм аз?

* Аз съм Николай/Meddle. <!-- .element: class="fragment" -->
* Аз съм баща. <!-- .element: class="fragment" -->
* Програмирам сървъри, а понякога и клиенти  <!-- .element: class="fragment" -->
* Работя във ВИК-то <!-- .element: class="fragment" -->
* Част съм от elixir-lang.bg <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/sofia_elixir.png)

#HSLIDE
### DISCLAIMER
![Image-Absolute](assets/disclaimer.png)

#HSLIDE
### Кои сте вие?

* Хора с различни интереси в софтуера, а може би и в хардуера? <!-- .element: class="fragment" -->
* Фенове на Elixir/Erlang? <!-- .element: class="fragment" -->
* Интересно ви е какво сега е HYPE!!?11! <!-- .element: class="fragment" -->
* Честно казано по това време не очаквам да сте много :) <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/we.jpg)

#HSLIDE
### По същество!

![Image-Absolute](assets/the_topic.jpg) <!-- .element: class="fragment" -->

#HSLIDE
### Защо да уча нов език?!

* Нали си знам PHP | JAVA | C# | Ruby | Python | Това-с-което-си-вадя-хляба? <!-- .element: class="fragment" -->
* Тези хипстъри, дето всяка година учат нов език, за нищо не стават!  <!-- .element: class="fragment" -->
* Ееее, всяка година, не, всяка седмица, нова глупост, то не може всичко я! <!-- .element: class="fragment" -->
* Тоя ще ми обяснява : 'Ето вижте колко яко пиша, почвайте да пишете и вие!'. <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/Haters_gonna_hate.jpg)

#HSLIDE
### Защо Elixir?

* Всички твърдения от предния слайд са вярни. Не всичко работи за всички. <!-- .element: class="fragment" -->
* Аз няма да ви уча на Elixir, ако имате интерес, има курс. <!-- .element: class="fragment" -->
* Искам да ви покажа нещата, които го правят различен от всички други технологии в момента. <!-- .element: class="fragment" -->
* Няма себърен куршум. Но за всичко си има набор от добри инструмени. <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/tools.jpg)

#HSLIDE
### Какво е Elixir?

* Elixir е език, който върви на BEAM. <!-- .element: class="fragment" -->
* BEAM e виртуалната машина на Erlang.  <!-- .element: class="fragment" -->
* Ахаа! Значи нещо като Scala както се отнася към Java?  <!-- .element: class="fragment" -->
* И да и не.  <!-- .element: class="fragment" -->
* Elixir е Erlang. Но и нещо повече. <!-- .element: class="fragment" -->

#HSLIDE
### Какво е Erlang?

![Image-Absolute](assets/what_is_erlang.png)

#HSLIDE
### Имало едно време ...

* ... в средата на 80-те в лаборатория на Ericsson <!-- .element: class="fragment" -->
* ... един човек със задача <!-- .element: class="fragment" -->
* ... да създаде способ за писане на конкурентни програми, които трябва да могат да се изпълняват безкрайно. <!-- .element: class="fragment" -->
* По-добър начин за писане на Телеком програми. <!-- .element: class="fragment" -->

#HSLIDE
### Телеком програми
![Image-Absolute](assets/telecom.jpg)

#HSLIDE
### Телеком програми
* Конкурентни (едно устройство трябва да може да поддържа хиляди едновременни транзакции).
* Толерантни към грешки и проблеми, както софтуерни, така и хардуерни.  <!-- .element: class="fragment" -->
* Практически нулев downtime.  <!-- .element: class="fragment" -->
* Кодът им да може да се заменя с по-нови версии, докато те работят.  <!-- .element: class="fragment" -->

#HSLIDE
#### А какви проблеми имаме днес?
![Image-Absolute](assets/internet.jpeg) <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/fun1.jpg)

#HSLIDE
![Image-Absolute](assets/fridge.jpg)

#HSLIDE
![Image-Absolute](assets/social_media.gif)

#HSLIDE
#### Сериозно, да продължим напред: Разказвахме приказка!
![Image-Absolute](assets/prodaljavame.jpg)

#HSLIDE
### Имало едно време ...

* Човекът, Joe Armstrong, създал конкурентен диалект на Prolog. <!-- .element: class="fragment" -->
* Появил се втори човек, Рobert Virding, и двамата създали език за писане на телеком програми, написан на Prolog. <!-- .element: class="fragment" -->
* Накрая Mike Williams пренаписал всичко на C. <!-- .element: class="fragment" -->
* Следват още пренаписвания и се появява BEAM и OTP. <!-- .element: class="fragment" -->
* С времето езикът става отворен. <!-- .element: class="fragment" -->
* Да, това е Erlang. <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/joeerl.jpg)

#HSLIDE
### Erlang!
1. Кодът върви в процеси, които са на ниво език.
2. Тези процеси не споделят памет - имат собствен стек и собствен heap. <!-- .element: class="fragment" -->
3. Много са евтини за създаване и си комуникират чрез размяна на съобщения.  <!-- .element: class="fragment" -->
4. Лесно могат да си комуникират помежду си, дори да са на различни машини. <!-- .element: class="fragment" -->
5. Ако един процес 'умре', другите продължават да живеят. Може нов да го замести, зависи от стратегията. <!-- .element: class="fragment" -->

#HSLIDE
### Erlang!
![Image-Absolute](assets/all.jpg)

#HSLIDE
### Actor модела

* Erlang не е повлиян от и не имплементира Actor модела. <!-- .element: class="fragment" -->
* Процесите на Erlang и актьорите имат общ предшественик - комуникацията между обекти със съобщения.   <!-- .element: class="fragment" -->
* Доста от идеите за Актьорите намират своят път в процесите на Erlang независимо от Actor модела.  <!-- .element: class="fragment" -->
* Вътрешността на един процес няма нищо общо с Actor модела.  <!-- .element: class="fragment" -->

#HSLIDE
Joe Armstrong нарича Erlang език за конкурентно-ориентирано програмиране, като се базира на няколко правила:

#HSLIDE
* Системата е изградена от процеси.
* Процесите не споделят нищо.  <!-- .element: class="fragment" -->
* Процесите си комуникират чрез асинхронно изпращане на съобщения.  <!-- .element: class="fragment" -->
* Процесите са изолирани един от друг.  <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/history.jpg)

#HSLIDE
### Erlang върви на BEAM

* BEAM е способна да използва всички ядра на процесора без проблем. <!-- .element: class="fragment" -->
* BEAM-level процесите са много малки 1KB-2KB при сздаването си. <!-- .element: class="fragment" -->
* Можем да създаваме огромен брой процеси без да се притесняваме. Говорим за милиони.  <!-- .element: class="fragment" -->
* Scheduler-ите на BEAM използват стратегия, различна от стратеггите в други езици - превантивна стратегия.  <!-- .element: class="fragment" -->

#HSLIDE
### Preemptive Strategy
![Image-Absolute](assets/preemptive.jpg)

#HSLIDE
### Добре? A Elixir??

* Elixir наследява всички тези неща. Все пак върви на BEAM. <!-- .element: class="fragment" -->
* Elixir може да използва почти всичко писано на Erlang. <!-- .element: class="fragment" -->
* Elixir идва с много добър tooling. <!-- .element: class="fragment" -->
* Elixir има много добро и бързо-растящо общество. <!-- .element: class="fragment" -->
* Elixir е модерен език добър за web, IOT, embedded разработка. <!-- .element: class="fragment" -->
* Споменах ли, че е функционален език? <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/functional.jpeg)

#HSLIDE
### Началото

* Езикът се ползва някъде от 2012 (2011 първи копки) година, което го прави доста млад. <!-- .element: class="fragment" -->
* Създателят на Elixir, Жозе Валим (José Valim) идва от ruby/rails света. <!-- .element: class="fragment" -->
* Бързо набира популярност сред рубистите и ерлангаджиите. <!-- .element: class="fragment" -->

#HSLIDE
![Image-Absolute](assets/jose.jpg)

#HSLIDE
### Tooling

* Elixir идва с **mix**. <!-- .element: class="fragment" -->
* Mix изпънява различни задачи - да речем прави нов Elixir проект. <!-- .element: class="fragment" -->
* Много лесно е да си напишем и своя задачка. <!-- .element: class="fragment" -->

#HSLIDE
### MIX
![Image-Absolute](assets/mix.jpg)

#HSLIDE
### Tooling

* Всъщност с mix можем да си направим собствена библиотека. <!-- .element: class="fragment" -->
* И да я качим в **hex**, откъдето можем да сваляме библиотеки на други хора. <!-- .element: class="fragment" -->
* Под hex, имам предви - https://hex.pm . <!-- .element: class="fragment" -->
* Също така mix се справя страхотно с dependencies. <!-- .element: class="fragment" -->

#HSLIDE
### NOT MIX
![Image-Absolute](assets/npm.jpeg)

#HSLIDE
### Tooling

* Получаваме и **ex_doc**, за който има mix task - 'mix doc'. <!-- .element: class="fragment" -->
* Генерира лесна за навигиране и ползване документация с връзки към source code-a. <!-- .element: class="fragment" -->
* Както и вградена testing библиотека **ExUnit** . <!-- .element: class="fragment" -->
* Лесна и приятна за ползване. <!-- .element: class="fragment" -->

#HSLIDE
### ExDoc

![Image-Absolute](assets/docs.png)
