PaidFeatureInfo
===============

.. code-block:: c#

	class PaidFeatureInfo {
		BillingAccountId: guid,
		PaidFeatureType: PaidFeatureType,
		PaidPeriods: PaidPeriod[],
		GracePeriodEnd: dateTime
	}
	
Информация о платных услугах:

 - BillingAccountId - идентификатор лицевого счета в системе Контур.Биллинг,
 - PaidFeatureType - :doc:`тип платной услуги <../enums/PaidFeatureType>`,
 - PaidPeriods - список :doc:`оплаченных периодов <../structures/PaidPeriod>`,
 - GracePeriodEnd - дата окончания действия льготного периода.