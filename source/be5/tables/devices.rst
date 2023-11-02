devices
=======


.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - id
     - INT PK
     - 

   * - sn
     - VARCHAR(100)
     - serial number

   * - title
     - TEXT
     - 

   * - typeID
     - INT

       Reference: device_types
     - 

   * - tocken
     - VARCHAR(100)

       can be null
     - authorisation key for remote access

   * - statusID
     - INT

       Reference: device_statuses
     - 

   * - stats
     - JSON

       can be null
     - 

   * - creationdate___
     - TIMESTAMP

       can be null
     - 

   * - modificationdate___
     - TIMESTAMP

       can be null
     - 

   * - whoinserted___
     - VARCHAR(100)

       can be null
     - 

   * - whomodified___
     - VARCHAR(100)

       can be null
     - 

