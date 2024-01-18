![19-4-challenge-image](https://github.com/ahcano/krypto_jobs/assets/141194281/76193921-b0f6-43c4-a246-d54fc1fc71e6)
## The objective of this initiative is to assume the role of a KryptoJobs2Go client, where Fintech professionals are paid through Ethereum transactions for their work and blockchain transactions are validated.
+ The code was developed using Python and Ganache. **crypto_wallet_assignment.py** contains Ethereum transaction functions; the Python script is integrated into the KryptoJobs2Go interface program found in the **krypto_jobs.py** file. <br>
+ A database was created with the details of four **Fintech professionals**; the candidates name, hourly rate and ethereum address to receive payments are displayed on the **KryptoJobs2Go!** webpage.<br> 
<p align="center"><img width="417" alt="Screenshot 2024-01-16 214638 - Copy" src="https://github.com/ahcano/krypto_jobs/assets/141194281/d1fa0280-30fa-4f3c-b4b7-f4a123287bd7"></p>

## Client Account 
+ A Client Ethereum account was created using a **mnemonic** seed and linked through Ganache. 
+ The mnemonic generated in Ganache was saved on the **.ENV** file.<br>

<img width="1117" alt="Screenshot 2024-01-17 182303" src="https://github.com/ahcano/krypto_jobs/assets/141194281/3c3439e1-496d-447d-8500-3c8c225ca381"> <br>

+ The following image shows the Client account **address** and **balance** of 100 Ethereum. <br>
<img width="1128" alt="Screenshot 2024-01-16 214456" src="https://github.com/ahcano/krypto_jobs/assets/141194281/3aa3890a-b28e-420a-ae29-dd2a196d8c45">

## Execution
+ A Streamlit page opens by running the following command on the Python terminal: streamlit run krypto_jobs.py
+ The Client account address and balance appear on the left sidebar
+ A Client can select a candidate and a wage is calculated based on the hourly rate and hours required.

# Sidebar Results
### 
<img width="799" alt="Screenshot 2024-01-16 223023" src="https://github.com/ahcano/krypto_jobs/assets/141194281/ebbd8d4c-10a1-46a3-9ba3-48b70127a8e5">

###
<img width="239" alt="Screenshot 2024-01-17 072624" src="https://github.com/ahcano/krypto_jobs/assets/141194281/a207baaf-7a38-49cd-b47d-e32d7a2d7464">

###
<img width="236" alt="Screenshot 2024-01-17 074459" src="https://github.com/ahcano/krypto_jobs/assets/141194281/84a0d809-d749-44f4-a6e9-3a25e7bd8650">

###
<img width="230" alt="Screenshot 2024-01-17 074521" src="https://github.com/ahcano/krypto_jobs/assets/141194281/d12545a1-f390-4356-9b49-5ddcbb3c525e">

### Validated Transaction
<img width="1545" alt="Screenshot 2024-01-17 184954" src="https://github.com/ahcano/krypto_jobs/assets/141194281/72e19165-cd49-4ce1-916d-fbd8551d5365">

### Account Balance 
<img width="881" alt="Screenshot 2024-01-17 185650" src="https://github.com/ahcano/krypto_jobs/assets/141194281/88d576ec-faf5-4b10-8235-4ccd59a4795c">

### Transactions
<img width="889" alt="Screenshot 2024-01-17 185701" src="https://github.com/ahcano/krypto_jobs/assets/141194281/2dfa2d02-dddc-4582-bf3a-299e7cde2987">


## Usage

## Contributor
Ana Cano - Author  

## License
Copyright (c) 2011-2017 GitHub Inc. Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

