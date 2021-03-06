# Clip Contents Designer (Дизайнер за Съдържанието на Клипборда) #

*	Автори: Noelia Ruiz Martínez.
*	Изтегляне [стабилна версия][1]
*	Изтегляне [работна версия][2]

Тази добавка служи за прибавяне на текст към клипборда, което може да бъде
полезно когато искате да обедините в едно отделни части от текст, готов за
поставяне.  Съдържанието на клипборда може и да се изчиства.

## Клавиатурни команди ##
*	NVDA+Windows+C: Прибавяне към клипборда на избрания текст, уникод брайлови
  символи представящи обекти на MathML, или низа маркиран с курсора за
  преглед.
*	NVDA+Windows+X: Изчистване на съдържанието на клипборда.
*	NVDA+Windows+F9: Маркиране на текущата позиция на курсора за преглед като начало на текста, който да се прибави към клипборда.
    Ако използвате NVDA+F9, текстът няма да бъде прибавен.

Забележка: Командите от по-горе може да бъдат променени от менюто на NVDA
подменю Настройки, диалога Жестове на въвеждане, категория Преглед на
текста.

## Меню с настройките ##
*	Настройки на Дизайнера за Съдържанието на Клипборда: Позволява указването на разделител, който може да се използва за намирането на текстовите сегменти след поставянето на целия текст.
Също така е възможно да изберете дали добавеният текст ще бъде прибавен преди или след наличния текст.

Забележка: Командата от по-горе може да бъде променена от менюто на NVDA,
подменю Настройки, диалога Жестове на въвеждане, категория Настройки.

## Промени във версия 5.0 ##

*	Визуалното представяне на прозореца е подобрено, придържайки се към
  стандарта за изглед на прозорците, извеждани от NVDA.
*	Изисква NVDA 2016.4 или по-нова.

## Промени във версия 4.0 ##
*	Настройките на добавката се управляват от конфигурацията на NVDA, така че
  стандартните профили може да се използват за запазване на различни
  разделители. Освен това, отпада необходимостта да копирате настройките за
  импортиране при преинсталация.
*	Сега е възможно да изберете дали добавеният текст ще бъде прибавен преди
  или след наличния текст, с помощта на опцията "Добави текста преди данните
  в клипборда" в диалоговия прозорец за настройка на Clip Contents Designer.

## Промени във версия 3.0 ##
*	Ако е инсталиран MathPlayer, в клипборда могат да се добавят брайлови
  представяния на обекти на MathML,.
*	Ако няма зададен разделител, ще бъде поставен един празен ред между
  прибавените текстови сегменти.
*	Може да бъде зададен бърз клавиш за отваряне на прозореца с настройките на
  Clip Contents Designer.
*	В диалоговия прозорец с настройките е добавено поле за отметка за избор
  дали разделителят да бъде копиран за импортиране при преинсталиране на
  добавката.

## Промени във версия 2.0 ##
*	Знаци от хинди може да се използват като разделител между добавеното
  съдържание.

## Промени във версия 1.0 ##
*	Първоначално издание.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ccd

[2]: https://addons.nvda-project.org/files/get.php?file=ccd-dev
