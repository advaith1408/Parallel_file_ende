Our project, a Parallel File Encryptor written in C++, tackles this exact problem. The key
innovation lies in utilizing multithreading to handle different parts of a file simultaneously.
Most modern processors today come with multiple cores, capable of running several tasks in
parallel. This project taps into that hardware advantage by dividing a file into chunks and
encrypting each chunk using a separate thread. As a result, we see a noticeable improvement
in speed, especially on multi-core systems.

