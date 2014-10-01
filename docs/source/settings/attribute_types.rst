Τύποι Δεδομένων
===============

:λέξεις κλειδιά:
    ``kb_AddEditCustomerPropertyKeyCode``
    ``kb_BrowseCustomerPropertyKeyCodes``
    ``kb_ViewCustomerPropertyKeyCode``
    ``kb_AddEditVehiclePropertyKeyCode``
    ``kb_BrowseVehiclePropertyKeyCodes``
    ``kb_ViewVehiclePropertyKeyCode``
    ``kb_AddEditVehicleServicePropertyKeyCode``
    ``kb_BrowseVehicleServicePropertyKeyCodes``
    ``kb_ViewVehicleServicePropertyKeyCode``
    ``kb_AddEditVehicleBrand``
    ``kb_BrowseVehicleBrands``
    ``kb_ViewVehicleBrand``
    ``kb_Settings_property_types``

Ένας πελάτης, ένα όχημα, μια εργασία μπορεί να έχει καμία ή κάποιες ιδιότητες.
Μια ιδιότητα δεν είναι τίποτα άλλο από τιμή (πχ. mail@example.com, 123456789, κτλ.)
και τι είδους/τύπου είναι αυτή η τιμή (πχ. email, τηλέφωνο, αρ. πλαισίου, κτλ.).

Οι τύποι είναι κάτι γενικό.

.. note:: Για παράδειγμα ένας άνθρωπος
          μπορεί να έχει τις παρακάτω 2, και όχι μόνο, ιδιότητες

          .. csv-table::
             :header: "ΑΑ", "Τύπος", "Τιμή"

             "#1", "Όνομα", "Γιώργος"
             "#2", "Ηλικία", "50"
          
          - Η ιδιότητα #1 έχει τύπο "Όνομα" και τιμή "Γιώργος"
          - Η ιδιότητα #2 έχει τύπο "Ηλικία" και τιμή "50"

Προσθήκη
--------

Για να προσθέσετε έναν νέο τύπο πατήστε το κουμπί "Προσθήκη".

.. figure:: /_static/images/screen-add-entity-button.png

.. note::
    Για περιγραφή των πεδίων
    δείτε στη παράγραφο `"Επεξεργασία"`__
    
    __ attribute_type_fields_

Αφού τελειώσετε με την επεξεργασία πατήστε το κουμπί
της αποθήκευσης για να καταχωρίσετε την εγγραφή
ή το κουμπί της ακύρωσης για να ακυρώσετε την καταχώριση.

.. figure:: /_static/images/entity-edit-save-cancel-buttons.png

.. _edit_attribute_type:

Επεξεργασία
-----------

Για να επεξεργαστείτε τα στοιχεία ενός τύπου επιλέξτε τον.

Για παράδειγμα

.. figure:: /_static/images/screen-settings-attribute_types-view-select.png

.. _attribute_type_fields:

.. warning:: TODO: να γίνει περιγραφή των πεδίων.

Αφού τελειώσετε με την επεξεργασία πατήστε το κουμπί
της αποθήκευσης για να καταχωρίσετε την εγγραφή
ή το κουμπί της ακύρωσης για να ακυρώσετε την καταχώριση.

.. figure:: /_static/images/entity-edit-save-cancel-buttons.png

Διαγραφή
--------

Εφόσον είστε στην :ref:`οθόνη επεξεργασίας κάποιου τύπου <edit_attribute_type>`,
πατήστε το κουμπί "Επεξεργασία"

.. figure:: /_static/images/screen-edit-entity-button.png

και επιλέξτε να κάνετε "Διαγραφή" της καταχώρισης.

.. figure:: /_static/images/screen-edit-delete-entity-option-button.png

Μάρκες
------

Κατά την ίδια έννοια με τους τύπους ιδιοτήτων μπορείτε να επεξεργαστείτε
και τη λίστα με τις μάρκες των οχημάτων.

