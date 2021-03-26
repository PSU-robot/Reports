# Датчики Холла и магниторезистивные датчики
## Датчики Холла
![](https://github.com/PSU-robot/Reports/blob/main/HallSensor.jpg?raw=true)
> Если на датчике Холла установлен магнит и контроллер Холла, то по величине индукции (близости магнита к датчику) можно определить угол вращения. Нужно правильно определить зависимость между индукцией и углом.
> ### Виды датчиков Холла
>> `Униполярные`<br/>
>> Контроллеры подобного вида работают только в том случае, если к ним прикладывается магнитное поле положительной полярности от южного полюса. Только при этом условии происходит срабатывание и отпускание контроллера.<br/>
>> `Биполярные`<br/>
>> Эти цифровые датчики работают под действием магнитного поля и южного, и северного полюса. Их особенность состоит в том, что срабатывают они под действием поля от южного полюса, а отпускаются под действием северного полюса.<br/>
>> `Омниполярные`<br/>
>> Уникальность этих контроллеров Холла состоит в том, что они могут включаться и выключаться под действием поля от любого полюса.
## Магниторезистивные датчики
![](https://github.com/PSU-robot/Reports/blob/main/MagnetoresistiveSensor.jpg?raw=true)
![](https://github.com/PSU-robot/Reports/blob/main/MagnetoresistiveSignal.jpg?raw=true)
> Магниторезистивные датчики магнитного поля в качестве чувствительного элемента содержат магниторезистор. Основным отличием магниторезистивных датчиков от датчиков Холла является то, что магниторезистивные датчики реагируют на направление тока, а не на силу. В магниторезистивном датчике чувствительной зоной в сенсоре является область с максимальным насыщением напряженности поля, поэтому достигается независимость от механических допусков (расстояния между магнитом и датчиком), а также от механических изменений, вызванных тепловым напряжением. Обработку сигналов с датчика `KMZ41` рекомендуется выполнять на чипах `UZZ9000` и `UZZ9001`
### Голышев Александр, 20ВО2
