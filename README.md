# Awesome Performance Dotnet!
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=flat&logo=.net&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=flat&logo=csharp&logoColor=white)

A opionated collection of libraries and resources for reducing C# memory usage and maximizing performance.

Inspired by [awesome-dotnet](https://github.com/quozd/awesome-dotnet), [awesome-python](https://github.com/vinta/awesome-python) and [awesome-go](https://github.com/avelino/awesome-go).

Thanks to all [contributors](https://github.com/gregyjames/awesome-performance-dotnet/graphs/contributors)!
 - Collections
 	 - [PooledCollections](https://github.com/jtmueller/Collections.Pooled): Collections library that uses `System.Span<T>` and `System.Buffers.ArrayPool<T>` libraries to minimize memory allocations.
 - FFI
 	 - [csbindgen](https://github.com/Cysharp/csbindgen): Generate C# FFI from Rust.
 - Messaging
 	 - [ZeroMQ](https://github.com/zeromq/netmq): NetMQ is a 100% native C# port of the lightweight messaging library ZeroMQ.
 - Object to object mapping
 	 - [TinyMapper](https://github.com/TinyMapper/TinyMapper): A quick object mapper for .Net
 - Serialization
 	 - [MemoryPack](https://github.com/Cysharp/MemoryPack): Zero encoding extreme performance binary serializer for C# and Unity.
     - [Sep](https://github.com/nietras/Sep/): Modern, minimal, fast, zero allocation, library for reading and writing CSVs.
 - Strings
	 - [ZString](https://github.com/Cysharp/ZString): Zero Allocation StringBuilder
  	 - [csFastFloat](https://github.com/CarlVerret/csFastFloat): FastFloat C# port
 - Tasks
	 - [PooledAwait](https://github.com/mgravell/PooledAwait): Low allocation async/await for C#/.NET
     - [UniTask](https://github.com/Cysharp/UniTask): An efficient allocation free async/await integration for Unity. 
