ProcessingTimes
===============

.. code-block:: c#

	class ProcessingTimes {
		TotalWorkTime: TimeSpan,
		DeliveryTime: TimeSpan,
		ConnectorWorkTime: TimeSpan,
		ConnectorWaitTime: TimeSpan,
		DiadocWaitTime: TimeSpan,
		RecadvWaitTime: TimeSpan,
		DeliveryNotificationWaitTime: TimeSpan
	}

Время, затраченное на различные этапы обработки сообщения, и общее время доставки сообщения:

 - TotalWorkTime - общее время доставки сообщения, разница между DocumentCirculationCompletionTimestamp и DocumentCirculationStartTimestamp,
 - DeliveryTime - время доставки за вычетом времени ожидания пользовательских действий или пользовательских интеграционных решений,
 - ConnectorWorkTime - время обработки сообщения Коннектором,
 - ConnectorWaitTime - время ожидания выполнения условий, необходимых для продолжения обработки Коннектором,
 - DiadocWaitTime - время между формированием черновиков документов в Диадоке и их подписанием,
 - RecadvWaitTime - время ожидания уведомления о приемке, при использовании соответствующей схемы взаимодействия между партнерами,
 - DeliveryNotificationWaitTime - время с момента первой попытки доставки сообщения получателя, до момента получения подтверждения доставки.