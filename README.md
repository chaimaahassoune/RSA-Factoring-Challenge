# RSA Factoring Challenge

The RSA Factoring Challenge is an optional project aimed at factorizing numbers used for encryption in order to decode important documents. The goal is to factorize these numbers as quickly as possible before the target fixes the encryption bug on their server. This README provides an overview of the project and its requirements.

## Algorithm

The project involves implementing an algorithm to factorize given numbers into a product of two smaller numbers. The algorithm should be able to handle large numbers efficiently.

## Requirements

### General

- You can choose any programming language for the implementation.
- The operating system should be Standard Ubuntu 20.04 LTS.
- The project should be completed within the specified time frame: from Jun 19, 2023, 3:00 AM, to Jul 3, 2023, 3:00 AM.
- An auto review will be launched at the deadline.

### Task 0: Factorize all the things!

- Implement a program/script called `factors` that factorizes numbers from a given file.
- The file should contain natural numbers to factor, with one number per line.
- You can assume that all lines will be valid natural numbers greater than 1, and there will be no empty lines.
- The output format should be `n=p*q` for each factorization.
- The program should run without any external dependencies and must complete within 5 seconds.

### Task 1: RSA Factoring

- This task is an extension of Task 0 but with some changes.
- The file will contain only one number.
- The factorization should yield two prime numbers, p and q, such that n = p * q.
- The program should complete the factorization within 5 seconds.

## Repository

The project repository, "RSA-Factoring-Challenge," contains the necessary files for the implementation:

- `factors`: The executable program/script for Task 0.
- `rsa`: The executable program/script for Task 1.

## Example

Here's an example of running the `factors` program:
```
$ cat tests/test00
4
12
34
128
1024
4958
1718944270642558716715
9
99
999
9999
9797973
49
239809320265259
$ ./factors tests/test00
4=2*2
12=6*2
34=17*2
128=64*2
1024=512*2
4958=2479*2
1718944270642558716715=343788854128511743343*5
9=3*3
99=33*3
999=333*3
9999=3333*3
9797973=3265991*3
49=7*7
239809320265259=15485783*15485773
```
## License

This project is © 2023 ALX. All rights reserved.

