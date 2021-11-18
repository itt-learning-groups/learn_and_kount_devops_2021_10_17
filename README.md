# GRPC, Meeting #3

## Notes from the meeting

* ~~What gRPC is and why/how it is used~~ // Covered: meeting #1

* Ecosystem/Tools/Implementation/Standards

  * ~~gRPC communication with protobuf encoding~~ // Covered: meeting #1

  * ~~Creating protobuf message and service definitions~~ // Covered: meeting #1

  * ~~Updating, versioning and maintaining backwards compatibility~~ // Covered: meeting #1

  * ~~Compiling the protobuf into client/server stubs~~ // Covered: meeting #1

  * ~~gRPC server reflection~~ // Covered: meeting #2

  * ~~Tools~~ // Covered: meeting #2

  * ~~Unary vs streaming gRPC~~ // Covered: meeting #2

  * ~~[Interceptors](https://blog.dsb.dev/posts/creating-grpc-interceptors-in-go/)~~ // Covered: meeting #2

  * ~~Middleware~~ // Covered: meeting #2

  * Demo: Implementing streaming, vs simple/unary, gRPC endpoints (Luke K.)
    * See demo [README](https://github.com/itt-learning-groups/grpc_streaming_demo/blob/main/README.md) and [code](https://github.com/itt-learning-groups/grpc_streaming_demo).

    * **Exercise 6**: During session we will build a proto file describing a service that has two rpcs. One describing a streaming request, and the other a streaming response. From the [proto](https://github.com/itt-learning-groups/grpc_streaming_exercise) implement the service and client by adding the buf.gen.yaml and buf.yaml, compiling the go packages and implement the concrete services to fulfill the service interface.

  * [gRPC-Gateway](https://grpc-ecosystem.github.io/grpc-gateway/docs/tutorials/introduction/) // Todo: approx. meeting #4

* Resources, links
  
  * [Awesome gRPC](https://github.com/grpc-ecosystem/awesome-grpc): *"A curated list of useful resources for gRPC"*
  * [A Guide to gRPC and Interceptors](https://edgehog.blog/a-guide-to-grpc-and-interceptors-265c306d3773) (blog article also referenced above in Exercise 2)
  * [gRPC Go: Beyond the basics](https://blog.gopheracademy.com/advent-2017/go-grpc-beyond-basics/), from Gopher Academy Blog: *"The purpose of this blog is to be a guideline for where to find the resources and leverage these libraries and features to make the most of the gRPC ecosystem after you understand the basics of gRPC"*

* Kount implementation and standards/patterns // Todo: approx. meeting #5

* Common techniques & tasks, "gotchas", tips & tricks // Todo: approx. meeting #5-6

* ~~{Case Studie(s)}~~ // Skip for this unit

* {"Class" exercise(s)} // Todo: approx. meeting #6
