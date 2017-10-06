Типы событий
=============

.. code-block:: c#

	enum BoxEventType {
		Unknown,
		NewOutboxMessage,
		NewInboxMessage,
		RecognizeMessage,
		MessageDelivered,
		MessageUndelivered,
		MessageReadByPartner,
		MessageCheckingOk,
		MessageCheckingFail,
		DraftOfDocumentPackagePostedIntoDiadoc,
		DraftOfDocumentPackageSignedByMe,
		DraftOfDocumentPackageDeletedFromDiadoc,
		DraftOfDocumentPackageSignedBySender,
		ReceivedDiadocRoamingError,
		DiadocRevocationAccepted,
		DiadocRevocationAcceptedForBuyer,
		DocumentPackageSignedByRecipientOk,
		DocumentPackageSignedByMeOk,
		DocumentPackageSignedByRecipientFail,
		DocumentPackageSignedByMeFail,
		AmendmentRequested,
		ProcessingTimesReport
	}
