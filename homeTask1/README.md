# Accessibility testing tools home task #1

[1. Работа с Audit tools](#1---audit-tools)


## 1. Работа с Audit tools

### a. Результаты аудита в Google Chrome dev tools Accessibility Audit страницы https://www.epam.com/ (Desktop version).
<img src="./img/dev-tools-accessebility.PNG" />

### b-c. Аудит страницы в Siteimprove plugin  
<img src="./img/siteimprove.PNG" />

#### Список найденных ошибок:
* (А) 1.3.1 Info and Relationships. The 'bold' tag is used to highlight text.
* (А) 1.4.1 Use of Color
  It appears that color is the only distinguishing feature about links in blocks of text. 
  (Номера телефонов подчеркиваются как ссылки только при ховере)
* (АА) 1.4.3 Contrast (Minimum).
   The color of the text and the color of the background are not in sufficient contrast to each other.
*  (ААА) 1.4.6 Contrast (Enhanced).
  The color of the text and the color of the background are not in sufficient contrast to each other.
* (А) 4.1.2 Name, Role, Value. Missing required WAI-ARIA states or properties.
 
### d-e. Аудит страницы в Siteimprove plugin  
<img src="./img/wave.PNG" />

#### Список найденных ошибок:

* 1 X Empty heading
* 3 X Empty button
* 2 X Empty link
* 53 Contrast Errors