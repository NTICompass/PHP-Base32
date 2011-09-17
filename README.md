Base32 For PHP
==============

This is a Base32 library for PHP.

It supports RFC 4648 or Crockford's implementation (http://www.crockford.com/wrmg/base32.html).

It does not support the check digit from Crockford's implementation yet.

Use:

    <?php
      include 'Base32.php'
      $a = new Base32();
      $base32 = $a->base32_encode('Test'); // KRSXG5A=
      $string = $a->base32_decode('KRSXG5A='); // Test
    ?>

It may not support encoding binary data yet.
