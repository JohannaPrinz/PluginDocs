Step 2: Name your elements
============================

| Its neccessary to name specific elements the right way, so they will be implemented correctly.
| There for you find a table with all elements that will be supported in the plugin and how to name them:

.. list-table::
    :name: element-table
    :widths: 70 70 70
    :header-rows: 0

    * - **Adobe element**
      - **HTML element**
      - **keyword** [#FN1]_
    * - rectangle + text
      - button
      - button
    * - rectangle + text
      - input with placeholder
      - input
    * - rectangle
      - inputfield
      - input
    * - rectangle
      - checkbox
      - checkbox
    * - rectangle
      - radiobutton
      - radiobutton
    * - line
      - line
      - line
    * - text [#FN2]_
      - list
      - list
    * - text
      - link
      - link

.. [#FN1] the keyword has to be includen in the elementname

.. hint::

   | Make sure you give all your other elements an unique name as well. 
   | Especially all your text-elements, because the name will be used as an **ID** in the CSS File.
    
**For example:**