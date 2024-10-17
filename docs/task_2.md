# Task 2

## Part A
In this part, we used the `find` command to search for all files over 1 MebiByte in size.

### Command
```bash
sudo find / -maxdepth 4 -type f -size +1M -exec ls -lh {} \;

We sorted the output and saved it to filesizes.txt.

sudo find / -maxdepth 4 -type f -size +1M -exec ls -lh {} \; | sort -k5hr > ~/filesizes.txt

The sorted list of file sizes is saved in filesizes.txt.
