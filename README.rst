=======
Install
=======

.. code-block:: bash

    pip install amazon_reviews

=======
Example
=======

.. code-block:: python

    from amazon_reviews.api import AmazonParseReviews

    product = AmazonParseReviews('B01ETPUQ6E')
    print product.average_star_rating()
    print product.review_count()
    print product.full()


=======

.. image:: https://img.shields.io/badge/Donate-PayPal-green.svg
  :target: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YYZQ6ZRZ3EW5C
