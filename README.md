# lesson 6 #

Задание на основе карточной игры которую вы делали на прошлых домашних заданиях.

1. Применить autolaout к игре что все карты были всегда по центру независимо от девайса на котором запустили приложение. Есть 2 способа это сделать (первый обезателен к выполенеию, воторой по желанию):
    * Положить все елементы вашей игры на UIView (с жестко задаными высотой и шириной) и выравнимать UIView по центру экрана.
    * Так сказать "со звездочкой" надо сделать что б кнопки вашей игры изменяли свой рамер подгоняя себя к экрану. Это можно сделать добаляя невидимые UIView между кнопок и сделать их жесткими по ширини и одинаковыми, а сами кнопки задать им AspectRatio.
2. Для всех следуйщих заданий сделать новый проект с таббаром на каждом отдельном табе реализоваит такие задания:
      * добавить елемент UILabel проставить нужные constraint'ы и вынести constraint ширины, после чего менять его слайдером.<br>
![Image](https://bradbambara.files.wordpress.com/2014/09/oij.gif)
      * добавить елемент UITextView проставить нужные constraint'ы и вынести constraint высоты, после чего менять его слайдером.<br>
![Image](https://bradbambara.files.wordpress.com/2014/09/wbfs.gif)
      * cоздать 3 екземпляра класа UIView и димамически изменять constraint ширины средней UIView<br>
![Image](https://bradbambara.files.wordpress.com/2014/09/vwlknf.gif)
      * создать UIView который будет контейнером для 3 UIView, динамически менять ширину и высоту контейнера при этом все дочерние UIView должны размещатся как на примире<br>
![Image](https://bradbambara.files.wordpress.com/2014/09/2efcs.gif)

P.S. Читать про Autolaout тут:(Get Started & Cookbook) https://developer.apple.com/library/prerelease/ios/documentation/UserExperience/Conceptual/AutolayoutPG/index.html#//apple_ref/doc/uid/TP40010853-CH7-SW1
