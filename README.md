# strings-it
Cylab CTF strings it

Q: Can you find the flag in [file](https://challenge-files.cylabacademy.net/library/dede17d717e026b75f6b9e7fb2c1601b46093ced6f209b8f6b27ffd883a9ae2f/strings) without running it?
Hint: https://linux.die.net/man/1/strings

Step1: Goto terminal and download the flag

wget https://challenge-files.cylabacademy.net/library/dede17d717e026b75f6b9e7fb2c1601b46093ced6f209b8f6b27ffd883a9ae2f/strings

<img width="543" height="362" alt="image" src="https://github.com/user-attachments/assets/6a5a3d33-99e6-4185-9274-be5fe7900d2c" />

Step2: strings strings | grep "academy"
Hing: grep is used to file the word in a file

<img width="543" height="107" alt="image" src="https://github.com/user-attachments/assets/55612790-8c7e-484a-b4ee-a4c00c5e48d3" />

Step3: Final Answer: academy{5tRIng5_1T_b1e21039}

