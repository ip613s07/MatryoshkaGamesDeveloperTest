# MatryoshkaGamesDeveloperTest

Описание задания:

По ссылке https://matryoshka.com/tests/TestDeveloper.zip находится Unity-проект, в котором
реализован минимальный прототип механики 2-го ресторана Нью-Йорка из Cooking Craze. В
прототипе два метода (ServeOrder и TryTrashFood) реализованы заглушками,
выбрасывающими NotImplementedException. К тому же, одно из двух блюд отсутствует
полностью (хот-доги). Таким образом, исходный прототип неработоспособен и не реализует
необходимую функциональность.

Задание состоит из следующих этапов:

1) Реализовать недостающие методы (CustomersController.ServeOrder и
FoodTrasher.TryTrashFood)
2) На основе имеющегося кода реализовать второе блюдо (хот-доги с добавкой в виде
горчицы). Все необходимые спрайты уже есть в проекте в папке Resources/Images
3) Добавить отсутствующее окно, которое должно показываться на старте игры (его
описание есть ниже, в разделе, описывающем механику прототипа)
4) Протестировать работоспособность прототипа и соответствие описанию.
5) Составить небольшой анализ реализации задания (это касается части, которая уже
была реализована до вас):
	- Какие недостатки и недоработки вам удалось найти?
	- Какие решения вы считаете сомнительными или нежелательными в более
		крупных проектах (и почему)?
	- Как можно было бы доработать прототип, чтобы улучшить его
		производительность на очень слабых мобильных устройствах, не жертвуя
		качеством картинки и без кардинальных изменений в коде или устройстве
		сцены?
	- Где можно изменить числовые параметры: время ожидания посетителей, время
		готовки/сгорания блюд, количество посетителей?
	- Что нужно сделать, если будет необходимость реализовать в рамках этого
		прототипа еще одно блюдо (луковые кольца, жареные во фритюре) с новой
		механикой:
		1) Игрок тапает по фритюрнице, начиная готовку
		2) Фритюрница запускает таймер на пять секунд
		3) По истечению таймера на стол автоматически выкладывается три
			порции луковых колец. (максимальное количество порций на столе – 3)
			(достаточно описать порядок действий, не обязательно реализовывать эту
			механику)