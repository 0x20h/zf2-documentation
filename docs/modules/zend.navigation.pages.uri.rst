
Zend_Navigation_Page_Uri
========================

Pages of type ``Zend_Navigation_Page_Uri`` can be used to link to pages on other domains or sites, or to implement custom logic for the page. *URI* pages are simple; in addition to the common page options, a *URI* page takes only one option —uri. Theuriwill be returned when calling$page->getHref(), and may be a ``String`` or ``NULL`` .

.. note::
    ****

     ``Zend_Navigation_Page_Uri`` will not try to determine whether it should be active when calling$page->isActive(). It merely returns what currently is set, so to make a *URI* page active you have to manually call$page->setActive()or specifyingactiveas a page option when constructing.


