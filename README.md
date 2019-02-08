# cppcheck_test
Run process:

```
docker pull rohank14/cppcheck_test
```

Assuming the code to be analyzed is placed in 'src' directory or change the last parameter from src to the folder name to be analyzed.

Run the container: 

```
docker run -t -v $(pwd):/src cppcheck
```
