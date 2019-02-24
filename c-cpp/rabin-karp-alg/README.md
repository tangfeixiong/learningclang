
# About Lab

## Test

for example
```
vagrant@ubuntu-bionic:/Users/fanhongling/Downloads/workspace/src/github.com/tangfeixiong/lang-learn/c-cpp/rabin-karp-alg$ gcc -o topleft topleft.c
```

```
vagrant@ubuntu-bionic:/Users/fanhongling/Downloads/workspace/src/github.com/tangfeixiong/lang-learn/c-cpp/rabin-karp-alg$ ./topleft
(0, 0); (1, 1); (2, 2); 
(0, 1); (1, 2); 
(0, 2); 
(1, 0); (2, 1); 
(2, 0); 
```

```
vagrant@ubuntu-bionic:/Users/fanhongling/Downloads/workspace/src/github.com/tangfeixiong/lang-learn/c-cpp/rabin-karp-alg$ ./topleft 5
(0, 0); (1, 1); (2, 2); (3, 3); (4, 4); 
(0, 1); (1, 2); (2, 3); (3, 4); 
(0, 2); (1, 3); (2, 4); 
(0, 3); (1, 4); 
(0, 4); 
(1, 0); (2, 1); (3, 2); (4, 3); 
(2, 0); (3, 1); (4, 2); 
(3, 0); (4, 1); 
(4, 0); 
```