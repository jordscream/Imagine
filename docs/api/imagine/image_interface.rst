ImageInterface
==============

.. php:interface:: Imagine\ImageInterface

   ImageInterface used to interact with images
   
   .. php:method:: get($format[, array $options = array()])
    
      Returns the image content as a binary string
      
      :param string $format: Format, e.g. 'png', 'jpg'
      :param array $options: Various options
      
      :returns: binary contents (string)