# SpeechAuth_MvvmCross
Проект по идентификации пользователя посредством анализа его голоса. За основу взят проект [Cody](https://github.com/Vikont133/Cody)

Отличие от проекта Cody:
- реализация на iOS;
- использование вейвлета Морле и отбор значений по принципу максимальной спектральной мощности сигнала перед дискретным преобразованием Фурье.

Проект реализован на [Xamarin.iOS](https://github.com/xamarin) и [MvvmCross](https://github.com/MvvmCross)

В планах развития:
- реализация на [Xamarin.Android](https://github.com/xamarin);
- реализация на Windows Phone;
- уход от ДПФ к использованию только вейвлетов;
- добавление сверточной нейронной сети.