MessageData
============

.. code-block:: c#

	class MessageData {
		MessageFileName: string,
		MessageBody: byte[]
	}
	
Содержимое сообщения:

 - MessageFileName – имя файла сообщения, используется при передаче сообщения специальными транспортами (например, FTP),
 - MessageBody – тело сообщения.