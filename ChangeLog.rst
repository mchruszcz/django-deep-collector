ChangeLog
=========


.. _v0.2.1:

0.2.1 (2016-02-03)
------------------

*bugfix:*

    - Fixing MANIFEST.in to include ``compat`` module, not added in distribution version (packaging was broken).


.. _v0.2:

0.2 (2016-02-02)
------------------

*New:*

    - Adding new ``compat`` module.
    - Now compatible with Django 1.7.x.


.. _v0.1.1:

0.1.1 (2015-09-23)
------------------

*New:*

    - Adding new ``get_report`` method to have collect detailed informations.
    - Various bug fixes


.. _v0.1:

0.1 (2015-04-21)
------------------

*New:*

    - Adding new ``RelatedObjectsCollector`` to collect every object that is related to given object.
    - Adding new ``MultiModelInheritanceSerializer`` to properly serialize collected item, to then be imported with Django `load_data` command.
