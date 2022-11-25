# se-vocabulary
A glossary to define software engineering concepts as accurately as possible

-------

### Tuple

A data structure that contains a finite sequence of elements. Tuples are immutable (cannot and should not be changed). Therefore, they are suitable to represent any information that is static by nature. An example of what can be a tuple is the word 'hello' in English which consists of finite sequence of letters. If the world 'hello' is accidently changed to 'hellor' during a process (e.g. writing), then it loses its meaning and become something else.

##### Other than making things static, why use tuples?
To is improve code readibility by communicate to the reader that the information contained in the tuple is immutable by design. It's not meant to be changed, ever.

More on tuples: https://encyclopediaofmath.org/wiki/Tuple

-------

### Thread

A unit of execution that is a part of a process. By default a process has 1 thread, but programmers can author programs with the capability to spawn multiple threads from the main thread. 

Threads have their own stack and data, but they can communicate with other threads via message passing e.g. IPC

There are 2 types of threads, user-level threads and kernel-level threads. User level threads are part of a process and thus not known to the kernel.

A major advantage of using multiple threads is that each thread of the same process can run on different CPU core thus enabling the threads to run in parallel.

-------
