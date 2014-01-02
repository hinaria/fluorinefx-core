astralfoxy/fluorinefx-core (deprecated)
============================

**This library has been deprecated in favour of [https://github.com/astralfoxy/rtmp-sharp](https://github.com/astralfoxy/rtmp-sharp).**

> FluorineFx is the free and open source Flash/Flex remoting gateway, high-performance, scalable framework, streaming server that connects RIAs using Adobe software (Adobe Flash®, Adobe Flex®, Adobe AIR™ runtime) and Microsoft .NET®
>
> -- FluorineFx Website [&lt;fluorinefx.com&gt;](http://www.fluorinefx.com/)

The original FluorineFx project had very little activity and change throughout the years. This is a simple fork of the core library with a few enhancements:

- Client library now supports RTMPS
- "LAC" functionality has been disabled for improved performance (every time an object is deserialized, it loads and reflects through every DLL in a bunch of directories)

## License
FluorineFx is licensed under the GNU Lesser GPL, so by extension, this is too.
