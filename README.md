Лекции към курса "Програмиране с Go"
======

Презентациите се пишат с [present](http://godoc.org/code.google.com/p/go.tools/present) tool-а на Go.

Всяка презентация представлява един `xx-name_of_the_lecturee.slide` файл, а кодът към нея в `code/xx/`. Където xx е поредният номер на лекцията.

Инсталация
-----

	go get code.google.com/p/go.talks/present
	cd $GOPATH/src/code.google.com/p/go.talks/present
	go get
	go install

Употреба
------

От текущата директория изпълнявате:

    present -base="assets"

http://127.0.0.1:3999/


Упътвания за принос
------

За да допринесете по някакъв начин към тези материали, е необходимо първо да си подкарате локално `present`, и да я прегледате в браузър, за да се уверите, че промените изглеждат така, както сте очаквали.
Препоръчително е да правите pull request-и в съответен branch, например `08-fix-typos` (за поправка на правописни грешки в презентация 8).
