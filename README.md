Эта программа выполняет проверку Ethereum-адресов, сгенерированных из мнемонических фраз, на наличие транзакций и баланса. Программа выводит системные метрики (использование ЦП, оперативной памяти и жесткого диска) в реальном времени, и сохраняет результаты в файлы:

	Found_ETH.txt — адреса, у которых есть транзакции.
	BAD_ETH.txt — адреса без транзакций.

Инструкция по использованию:
Сначала установите все необходимые зависимости. 
Создайте файл requirements.txt с таким содержимым:

	aiohttp
	aiofiles
	blessed
	colorama
	configparser
	cryptofuzz
	keyboard
	mnemonic
	psutil
	pyfiglet
	requests
	rich
	web3

Далее выполните команду:

	pip install -r requirements.txt

Запустите скрипт в консоли командой:

	python script.py
--------------------------------------------------------------------------------------
This program performs a check of Ethereum addresses generated from mnemonic phrases for transactions and balances. It also displays real-time system metrics (CPU, RAM, and disk usage), and saves the results to files:

	Found_ETH.txt — contains addresses with transactions.
	BAD_ETH.txt — contains addresses without transactions.
 
Usage Instructions:
First, install all necessary dependencies. Create a requirements.txt file with the following content:

	aiohttp
	aiofiles
	blessed
	colorama
	configparser
	cryptofuzz
	keyboard
	mnemonic
	psutil
	pyfiglet
	requests
	rich
	web3
 
Then, run the command:

	pip install -r requirements.txt
 
Start the script by running the following command in the console:

	python script.py
