# ReFlashIG
Instagram Password Cracker

# Usage
`
Usage: ReFlashIG.py [-i] [-m] [-v] [-c <thread count>] -u <username> -p <password file> -x <proxy file> -t <timeout>

Options:
  -h, --help        show this help message and exit
  -u USERNAME       Instagram username to target
  -p PASSWORD_FILE  File containing list of passwords
  -x PROXY          File containing list of proxies
  -t TIMEOUT        Instagram connection timeout
  -c THREAD_COUNT   Thread count
  -v                Verbose output
  -m                Open interactive menu
  -i                Information page`
  
Example: `python ReFlash.py -u the.red.team2 -p passwords.txt -x proxies.txt -t 5 -v`
Example: `python ReFlash.py -m` (walks through setup)

Download: wget "https://raw.githubusercontent.com/the-red-team/ReFlashIG/master/ReFlashIG.py" -O ReFlashIG.py
