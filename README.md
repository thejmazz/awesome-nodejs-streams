# awesome-nodejs-streams
Awesome resources and modules for Streams in Node

## Articles

- [Why I don't use Node's core 'stream' module](https://r.va.gg/2014/06/why-i-dont-use-nodes-core-stream-module.html)
- [stream-handbook](https://github.com/substack/stream-handbook)

## Modules

- [almost/through2-concurrent](https://github.com/almost/through2-concurrent) - Simple Node.JS stream (streams2) Transform that runs the transform functions concurrently (with a set max concurrency)
- [bendrucker/stream-to-promise](https://github.com/bendrucker/stream-to-promise) - Convert streams (readable or writable) to promises
- [grncdr/merge-stream](https://github.com/grncdr/merge-stream) - Merge multiple streams into one interleaved stream
- [dominictarr/event-stream](https://github.com/dominictarr/event-stream) - EventStream is like functional programming meets IO
- [dominictarr/map-stream](https://github.com/dominictarr/map-stream) - refactored out of event-stream
- [dominictarr/split](https://github.com/dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk. matcher may be a String, or a RegExp
- [dominictarr/stream-combiner](https://github.com/dominictarr/stream-combiner) - Turn a pipeline into a single stream. Combine returns a stream that writes to the first stream and reads from the last stream
- [dominictarr/stream-spec](https://github.com/dominictarr/stream-spec) - executable specification for Stream (make testing streams easy)
- [feross/multistream](https://github.com/feross/multistream) - A stream that emits multiple other streams one after another (streams2)
- [floatdrop/stream-assert](https://github.com/floatdrop/stream-assert) - Assertion library for streams
- [freeall/progress-stream](https://github.com/freeall/progress-stream) - Read the progress of a stream
- [hughsk/from2](https://github.com/hughsk/from2) - Convenience wrapper for ReadableStream, inspired by through2
- [jahewson/node-byline](https://github.com/jahewson/node-byline) - Line-by-line Stream reader
- [mafintosh/duplexify](https://github.com/mafintosh/duplexify) - Turn a writeable and readable stream into a streams2 duplex stream with support for async initialization and streams1/streams2 input
- [mafintosh/end-of-stream](https://github.com/mafintosh/end-of-stream) - Call a callback when a readable/writable/duplex stream has completed or failed
- [mafintosh/peek-stream](https://github.com/mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it
- [mafintosh/pump](https://github.com/mafintosh/pump) - pipe streams together and close all of them if one of them closes
- [mafintosh/pumpify](https://github.com/) - Combine an array of streams into a single duplex stream using pump and duplexify
- [mafintosh/tar-stream](https://github.com/mafintosh/tar-stream) - tar-stream is a streaming tar parser and generator
- [maxogden/binary-split](https://github.com/maxogden/binary-split) - A fast newline (or any delimiter) splitter stream
- [maxogden/concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result
- [maxogden/mississippi](https://github.com/maxogden/mississippi) - A collection of useful stream utility modules for writing better code using streams
- [mcollina/split2](https://github.com/mcollina/split2) - Split streams3 style
- [nodejs/readable-stream](https://github.com/nodejs/readable-stream) - Node-core streams for userland
- [npm/fstream](https://github.com/npm/fstream) - Advanced FS Streaming for Node
- [parshap/node-stream-reduce](https://github.com/parshap/node-stream-reduce) - Reduce stream data to a single value
- [raynos/duplexer](https://github.com/raynos/duplexer) - Creates a duplex stream
- [rvagg/isstream](https://github.com/rvagg/isstream) - Determine if an object is a Node.js Stream
- [rvagg/through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise
- [samcday/node-stream-buffer](https://github.com/samcday/node-stream-buffer) - Readable and Writable Streams that use backing Buffers
- [schnittstabil/stream-from-promise](https://github.com/schnittstabil/stream-from-promise) - Create streams from promises
- [sindresorhus/first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - Buffer and transform the n first bytes of a stream
- [sindresorhus/get-stream](https://github.com/sindresorhus/get-stream) - Get a stream as a string, buffer, or array
- [sindresorhus/into-stream](https://github.com/sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream
- [sindresorhus/is-stream](https://github.com/sindresorhus/is-stream) - Check if something is a Node.js stream
- [spion/promise-streams](https://github.com/spion/promise-streams) - A collection of node.js streams that work well with promises (through, map, reduce, etc...)
- [stream-utils/destroy](https://github.com/stream-utils/destroy) - destroy a stream if possible
- [substack/emit-stream](https://github.com/substack/emit-stream) - turn event emitters into streams and streams into event emitters
- [substack/oppressor](https://github.com/substack/oppressor) - streaming http compression response negotiator
- [substack/stream-combiner2](https://github.com/substack/stream-combiner2) - stream-combiner for streams3
- [substack/resumer](https://github.com/substack/resumer) - a through stream that starts paused and resumes on the next tick
- [teambition/merge2](https://github.com/teambition/merge2) - Merge multiple streams into one stream in sequence or parallel
