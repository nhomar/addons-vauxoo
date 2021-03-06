===========
MODULE HELP
===========

.. contents:: Table of Content

New features
------------

#. I add the contract expiration date field in the puchase order model and 
   show it in the purchase order form.

    .. figure:: images/figure-1.png
       :scale: 50 %
       :align: center

       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-YTlNT1NqM0ZPQnc/edit?usp=drivesdk

#. When a purchase order is confirm will create stock pikings, This pickings
   will have a expired contract date too, the date pull from the purchase
   order data.

    .. figure:: images/figure-1-1.png
       :scale: 50 %
       :align: center
       
       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-VFgxV0ZzTHhmYTA/edit?usp=drivesdk

    .. figure:: images/figure-1-2.png
       :scale: 50 %
       :align: center
       
       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-T2Fnamx0OUNYMkk/edit?usp=drivesdk

    .. figure:: images/figure-1-3.png
       :scale: 50 %
       :align: center
       
       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-UTNNZGVBajVQamc/edit?usp=drivesdk

#. When a stock picking is duplicated will clear the expiration contract date.

    .. figure:: images/figure-2.png
       :scale: 50 %
       :align: center
       
       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-UGNQNDBkV2hKUUE/edit?usp=drivesdk

    .. figure:: images/figure-2b.png
       :scale: 50 %
       :align: center
       
       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-NW9PVGxaZ2NSUTg/edit?usp=drivesdk

#. I create a purchase order and I assing a past contract expire date. Then I
   confirm the purchase order.

    .. figure:: images/figure-3.png
       :scale: 50 %
       :align: center
       
       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-UTlqYktiNHBiSWc/edit?usp=drivesdk

    .. TODO: this image need to change.

#. I go inside the picking generated by a contract expire date purchase order
   confirmation and I click in the Receive button. This error message is pop up
   saying Cannot receive a picking with a expired contract date of pickings in
   done state.

    .. figure:: images/figure-4.png
       :scale: 50 %
       :align: center
       
       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-R1NYV29MdEUtd2c/edit?usp=drivesdk

#. I use the Force Receive button to sucessfully recieve the picking Force
   Recevie button will open the receive wizard normally. 

    .. figure:: images/figure-5.png
       :scale: 50 %
       :align: center

       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-TUNPZk1VNDJHTnc/edit?usp=drivesdk

#. I use the Create Draft Invoice wizard from the stock picking in tree
   view. I select a picking whose purchase order is contract expired date.

    .. figure:: images/figure-6.png
       :scale: 50 %
       :align: center

       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-R2p2di1IdWNaVXc/edit?usp=drivesdk

#. I try to create an invoce from a stock picking in with contract expired
   date. And this is the result, a error message raise indicating that the
   action can be done.

    .. figure:: images/figure-7.png
       :scale: 50 %
       :align: center

       https://docs.google.com/a/vauxoo.com/file/d/0b1uuua6brx8-nnc2zmresevttda/edit?usp=drivesdk

#. I add the Force Create button in the create draft invoices wizard. When a
   stock picking have contract expired date then with this button will proceed
   no matter what and will create the invoice even if the stock picking have a
   expired contract date.

    .. figure:: images/figure-8.png
       :scale: 50 %
       :align: center

       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-S3gwOW93ajNkY2c/edit?usp=drivesdk

#. After a picking is received a button 'Create Invoice/Refund' is shown to
   create the invoice of the current picking

    .. figure:: images/figure-9.png
       :scale: 50 %
       :align: center

       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-YVAyWnBoN0NxUkE/edit?usp=drivesdk

    .. figure:: images/figure-10.png
       :scale: 50 %
       :align: center

       https://docs.google.com/a/vauxoo.com/file/d/0B1UUUA6bRx8-N3VSQ2VTX3VubzQ/edit?usp=drivesdk
