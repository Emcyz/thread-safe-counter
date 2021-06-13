# thread-safe-counter
## OS Environment
- Ubuntu 18.04

# time
![Screenshot from 2021-06-13 19-29-04](https://user-images.githubusercontent.com/11612272/121803797-1c704f00-cc7e-11eb-9bb3-e6dbaa964f2c.png)
-Mutex (./a) : about 0.15s
-Semaphore (./b) : about 5s

# my analysis
### Semaphore has too many statement of
- declaring struct sembuf s
- initializing and calculating elements of struct sembuf s
### this is because Semaphore handle shared memory

# my information
- name : 이승욱
- student id : 20173417
- subject : Computer Architecture and Real-Time Operating System (1241501-01) 
