
.. |ASN.1| replace:: BMPString

.. |encoding| replace:: utf-16-be

|ASN.1| type
------------

.. autoclass:: pyasn1.type.char.BMPString(value=NoValue(), tagSet=TagSet(), subtypeSpec=ConstraintsIntersection(), encoding='us-ascii')
   :members: hasValue, isSameTypeWith, isSuperTypeOf, tagSet

   .. note::

       The |ASN.1| type models a Unicode (ISO10646-1) character string implicitly serialized into UTF-16 big endian.
       
   .. automethod:: pyasn1.type.char.BMPString.clone(value=NoValue(), tagSet=TagSet(), subtypeSpec=ConstraintsIntersection(), encoding='us-ascii')
   .. automethod:: pyasn1.type.char.BMPString.subtype(value=NoValue(), implicitTag=Tag(), explicitTag=Tag(),subtypeSpec=ConstraintsIntersection(), encoding='us-ascii')
