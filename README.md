# lifehack
Стили для обнуления верхних отступов у элементов
h1,
h2,
h3,
h4,
h5,
h6,
p {
	margin-top: 0;
    Padding: 0;
	
}Класс для обнуления базовых свойств у списков (ul) */
.list {
	list-style: none;
	padding-left: 0;
	margin: 0;
}
/* Класс для обнуления базовых свойств у ссылок */
.link {
	text-decoration: none;
	color: inherit;
}
/* Свойства для корректного отображения картинок */
img {
	display: block;
	max-width: 100%;
	height: auto;
}
/* Свойства для обнуления курсива у address */
address {
	font-style: normal;
	/* or */
	font-style: inherit;
}
Як приховати заголовок
visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  border: 0;
  clip: rect(0 0 0 0);
}
