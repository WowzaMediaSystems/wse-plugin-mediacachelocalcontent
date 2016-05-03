# MediaCacheLocalContent

MediaCacheLocalContent is a custom IRandomAccessReader implementation for [Wowza Streaming Engine™ media server software](https://www.wowza.com/products/streaming-engine).

## Prerequisites

Wowza Streaming Engine 4.0.0 or later is required.

## Usage

This Media Reader can be added to a new or existing video on demand (VOD) type application.

This media reader provides the following functionality:

**MediaCacheLocalContent** will look for a piece of content in the application's content storage directory first and then, if it cannot find it, will try to retrieve the content from a remote Media Cache source. This is a useful function when there is a need to stream locally stored content alongside remote content. For example, you could use this module if you have popular content that you need to store locally or if you have content that has just been recorded and you need to make it available before it has been transferred to the remote server.

## API Reference

[Wowza Streaming Engine Server-Side API Reference](https://www.wowza.com/resources/WowzaStreamingEngine_ServerSideAPI.pdf)

[How to extend Wowza Streaming Engine using the Wowza IDE](https://www.wowza.com/forums/content.php?759-How-to-extend-Wowza-Streaming-Engine-using-the-Wowza-IDE)

Wowza Media Systems™ provides developers with a platform to create streaming applications and solutions. See [Wowza Developer Tools](https://www.wowza.com/resources/developers) to learn more about our APIs and SDK.

To use the compiled version of this module, see [Media Cache implementation that will first try to access content locally before getting it from a remote source (MediaCacheLocalContent)](https://www.wowza.com/forums/content.php?520-Media-Cache-implementation-that-will-first-try-to-access-content-locally-before-getting-it-from-a-remote-source-%28MediaCacheLocalContent%29).

[Wowza Media Cache Deployment Architecture white paper](https://www.wowza.com/uploads/images/Wowza-Media-Cache-Deployment-Architecture__White_Paper_2014.pdf)

## Contact

[Wowza Media Systems, LLC](https://www.wowza.com/contact)

## License

This code is distributed under the [Wowza Public License](https://github.com/WowzaMediaSystems/wse-plugin-mediacachelocalcontent/blob/master/LICENSE.txt).
