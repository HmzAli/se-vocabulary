# se-vocabulary
A glossary to define software engineering concepts as accurately as possible

-------

#### Tuple

A data structure that contains a finite sequence of elements. Tuples are immutable (cannot and should not be changed). Therefore, they are suitable to represent any information that is static by nature. An example of what can be a tuple is the word 'hello' in English which consists of finite sequence of letters. If the world 'hello' is accidently changed to 'hellor' during a process (e.g. writing), then it loses its meaning and become something else.

##### Why use tuples?
In my opinion, the best reason to use tuple is improve code readibility by communicate to the reader (the author or anyone else) that the information contained in the tuple is immutable (by design). It's not meant to be changed, ever.

-------
