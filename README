The SocialSDK Bundle
====================

This bundle adds the SDK required by social networks at the end of the web page, only when
the SDK is required.

This means that the facebook sdk is added to the page, only when a fecebook button
is added to the page.


Supported SDK
-------------

At the moment the SocialSDK Bundle supports those social networks:

* Twitter
* Facebook


Installation
------------

You can add the **SocialSDK Bundle** to your application adding it to your composer.json
file:

.. code-block:: text

    {
        "require": {
            "alphalemon/social-sdk-bundle": "dev-master",        
        }
    }

If you use the AlphaLemonBootstrapBundle the bundle is autoloaded, otherwise add it to the
application **AppKernel.php** file:

.. code-block:: php

    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                [...]

                new AlphaLemon\Block\SearchBlockBundle\SearchBlockBundle(),
            );
        }
    }


Add a new SDK
-------------

A new SDK is easily added, add a new provider that extends the **AlphaLemon\Block\SocialSDKBundle\Core\Sdk\SdkBase**.
This abstract base class provides a common constructor and implements the **AlphaLemon\Block\SocialSDKBundle\Core\Sdk\SdkInterface**,
without implementing its method as well, which must be defined in the derived class.


Unit test
---------

The bunde is not yet unit tested, so use it just with test or implementation pourpose.