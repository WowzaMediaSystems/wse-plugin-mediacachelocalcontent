# MediaCacheLocalContent
The **MediaCacheLocalContent** Media Reader is a custom **IRandomAccessReader** implementation for [Wowza Streaming Engine™ media server software](https://www.wowza.com/products/streaming-engine) that enables you to make locally stored content available before it's transferred to a remote Media Cache source.

## Prerequisites
Wowza Streaming Engine 4.0.0 or later is required.

## Usage
This Media Reader can be added to new or existing on-demand (VOD) applications. It looks for the requested piece of content in an on-demand application's content storage directory first, and if it can't find it, then tries to retrieve the content from a remote Media Cache source. This is a useful function when you need to stream locally stored content alongside remote content. For example, you could use this module if you have popular content that you need to store locally or if you have content that was just recorded and you need to make it available before transferring it to the remote server.

## More resources
[Wowza Streaming Engine Server-Side API Reference](https://www.wowza.com/resources/serverapi/)

[How to extend Wowza Streaming Engine using the Wowza IDE](https://www.wowza.com/forums/content.php?759-How-to-extend-Wowza-Streaming-Engine-using-the-Wowza-IDE)

Wowza Media Systems™ provides developers with a platform to create streaming applications and solutions. See [Wowza Developer Tools](https://www.wowza.com/resources/developers) to learn more about our APIs and SDK.

To use the compiled version of this module, see [Media Cache implementation that first tries to access content locally before getting it from a remote source (MediaCacheLocalContent)](https://www.wowza.com/forums/content.php?520-Media-Cache-implementation-that-will-first-try-to-access-content-locally-before-getting-it-from-a-remote-source-%28MediaCacheLocalContent%29).

[Wowza Media Cache Deployment Architecture white paper](https://www.wowza.com/uploads/images/Wowza-Media-Cache-Deployment-Architecture__White_Paper_2014.pdf)

## Contact
[Wowza Media Systems, LLC](https://www.wowza.com/contact)

## License
This code is distributed under the [Wowza Public License](https://github.com/WowzaMediaSystems/wse-plugin-mediacachelocalcontent/blob/master/LICENSE.txt).
