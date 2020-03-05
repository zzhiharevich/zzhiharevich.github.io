# Color Peaker
## CMYK ↔ LAB ↔ HSV 

Изучить цветовые модели: RGB, CMYK, HSV, HLS, XYZ, LAB, переход от одной модели к другой, исследовать цветовой график МКО.
<br/> Создать приложение/веб-приложение, позволяющее пользователю  выбирать, а затем интерактивно менять цвет, показывая при этом его
<br/>составляющие в трех моделях одновременно (варианты приведены в таблице ниже).<br/>

### Основные требования к приложению 
В интерфейсе дать возможность пользователю задавать точные цвета (поля ввода), выбирать цвета из палитры (аналогично графическим редакторам),
<br/>плавно изменять цвета (например, ползунки).<br/>
При изменении любой компоненты цвета все остальные представления этого цвета в двух других цветовых моделях пересчитываются автоматически.<br/>
При «некорректных цветах» (например, при переходе из XYZ в RGB в вашем расчете получился выход за границы изменения рассчитываемого параметра)
<br/>выдавать некое ненавязчивое предупреждение, что происходит обрезаниеокругление и т.п.<br/>
