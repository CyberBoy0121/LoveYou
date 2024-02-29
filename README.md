# LoveYou


**LoveYou is a Python script to find admin panel of a website**

> [!WARNING]
> This tool is only for educational purpose, developer is not responsible for any misuse or illegal activities.


## Features

- Fast (Multithreaded)
- Random user-agents
- Proxy
- Big path list


## Requirements

1. Make sure you have python3 and pip3 installed on your device.

2. Install the requirements:

    ```sh
    pip3 install -r requirements.txt
    ```


## Usage

Start the scan:

```sh
python3 LoveYou.py http://example.com
```

## Options

- `-f` or `--fast` to enable multithreads:

    ```sh
    python3 LoveYou.py http://example.com --fast
    ```

- `-r` or `--random-agent` to enable random user-agents:

    ```sh
    python3 LoveYou.py http://example.com --random-agent
    ```

- `-p` or `--proxy` to use HTTP(s) or SOCKS(4/5) proxy:

    ```sh
    python3 LoveYou.py http://example.com --proxy http://127.0.0.1:8080
    ```

    or

    ```sh
    python3 LoveYou.py http://example.com --proxy socks5://127.0.0.1:8080
    ```


)
