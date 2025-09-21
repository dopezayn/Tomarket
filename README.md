# Tomarketod

Auto Claim for tomarket Telegram Bot

# Warning

All Risks are borne by the user!

# Features

- [x] Auto Claim
- [x] Multi Account Support
- [x] Auto Play Game
- [x] Proxy Support

# How to Use

## About Config

| Name            | Description                                                                                |
| --------------- | ------------------------------------------------------------------------------------------ |
| interval        | downtime between account                                                                   |
| play_game       | value must bool (true/false) set true for enable auto play game after claim                |
| game_point      | low : minimum earn from play game <br>high : maximum earn from play game                   |
| additional_time | min : minimum addition time for next claim <br> max : maximum addition time for next claim |

## About Proxy

```
http://host:port
http://user:pass@host:port
```

Example :

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
socks5://127.0.0.1:6969
socks5://user:pass@127.0.0.1:6969
```

## Windows 

1. Make sure you computer was installed python and git.
   
   python site : [https://python.org](https://python.org)
   
   git site : [https://git-scm.com/](https://git-scm.com/)

2. Clone this repository
   ```shell
   git clone https://github.com/dopezayn/Tomarket.git
   ```

3. goto Tomarket directory
   ```
   cd Tomarket
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Linux

1. Make sure you computer was installed python and git.
   
   python
   ```shell
   sudo apt install python3 python3-pip
   ```
   git
   ```shell
   sudo apt install git
   ```

2. Clone this repository
   
   ```shell
   git clone https://github.com/dopezayn/Tomarket.git
   ```

3. goto Tomarket directory

   ```shell
   cd Tomarket
   ```

4. Install the require library
   
   ```
   python3 -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Termux

1. Make sure you termux was installed python and git.
   
   python
   ```
   pkg install python
   ```

   git
   ```
   pkg install git
   ```

2. Clone this repository
   ```shell
   git clone https://github.com/dopezayn/Tomarket.git
   ```

3. goto Tomarket directory
   ```
   cd Tomarket
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Get Data](#how-to-get-data). One line for one data account, if you want add you second account add in new line!


6. execute the main program 
   ```
   python bot.py
   ```

# Run for 24/7 

You can run the script bot for 24/7 using vps / rdp. You can use `screen` application in vps linux to running the script bot in background process

# Discussion

If you have an question or something you can ask in here : [JOIN MY TELEGRAM ](https://t.me/Next_Gen_nexus)

# Thank you < 3