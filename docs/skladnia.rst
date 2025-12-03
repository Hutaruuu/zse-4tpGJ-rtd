=============================
Składnia dokumentu (przykład)
=============================

Nagłówki
--------
Nagłówek poziomu 1
==================

Nagłówek poziomu 2
------------------

Nagłówek poziomu 3
~~~~~~~~~~~~~~~~~~

Nagłówek poziomu 4
^^^^^^^^^^^^^^^^^^

Akapit tekstowy
---------------
To jest przykładowy akapit w RST.

Akapit informacyjny
-------------------
.. note:: To jest notatka informacyjna.
.. tip::  To jest przydatna wskazówka.

Fragmenty kodu
--------------
Liniowy: ``echo("Przykład")``

Blokowy:
.. code-block:: python

    print("Przykładowy komunikat")

Odnośniki
---------
Zewnętrzny: projekt <https://design.cricut.com/>
Lokalny: :doc:`o_autorze`

Listy
-----
Numerowana:
1. Pierwszy element listy
2. Drugi element listy

Wypunktowana:
- Pierwsza pozycja
- Druga pozycja

Listy definicji:
termin
    Krótkie objaśnienie terminu

Obraz
-----
.. image:: obrazek.png
   :alt: Przykładowy obraz
   :align: center

Tabela
------
.. list-table::
   :header-rows: 1

   * - Kolumna 1
     - Kolumna 2
   * - Wartość 1
     - Wartość 2
