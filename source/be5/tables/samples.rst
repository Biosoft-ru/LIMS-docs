samples
=======

Образцы
  Отдельные образцы для секвинирования. За основу взяты поля Illumina.

.. list-table::
   :header-rows: 1

   * - Колонка
     - Тип
     - Описание

   * - id
     - INT PK
     - 

   * - name
     - VARCHAR(100)
     - 

   * - plate
     - VARCHAR(100)

       can be null
     - 

   * - well
     - VARCHAR(100)

       can be null
     - 

   * - index_plate
     - VARCHAR(100)

       can be null
     - 

   * - index_well
     - VARCHAR(100)

       can be null
     - 

   * - I7_index_id
     - VARCHAR(100)

       can be null
     - 

   * - index1
     - VARCHAR(100)

       can be null
     - 

   * - I5_index_id
     - VARCHAR(100)

       can be null
     - 

   * - index2
     - VARCHAR(100)

       can be null
     - 

   * - description
     - TEXT

       can be null
     - 

   * - project_id
     - VARCHAR(100)

       can be null

       Reference: projects
     - 

   * - file_path
     - VARCHAR(300)

       can be null
     - 

   * - file_size
     - INT

       can be null
     - 

   * - metadata
     - TEXT

       can be null
     - 

   * - template_id
     - INT

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

