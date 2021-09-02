# How To Make reflection token and deploy it - Full Guide

### Prerequisites:
1. The Source Code I have Provided <br>
2. PC<br>
3. Vs Code Editor<br>
4. Metamask Extention With BNB<br><br>

### Steps To Change Code: (If you wish to)
1. Open the code on Vs Code Editor. (CMD/CTRL + O)<br>
2. Goto #1212 line and change the contract name (Usually according to the token name or symbol but can be anything in one word).<br>
3. #1228, 1229 & 1230 line for changing the reflection, liquidity & marketing (dev) fees.<br>
4. #1233 line is for the address where the marketing or dev fees will go. Change it as you want but can’t be the same address as the owner (deployer).<br>
5. To change the name: <br>![image](https://user-images.githubusercontent.com/78958410/131809969-6b20519d-3c7a-40e3-b286-478169c333b5.png) <br>
6. #1280 line is for name and symbol (we have already changed the name on #4 step so this is for changing the symbol).
7. #1311 line is for total supply.
8. If you like to change the reward token (You can find the current reward token address on the #1224 line):![image](https://user-images.githubusercontent.com/78958410/131810268-a8f7390f-8185-4e12-a295-9aedfe03f1c5.png)
9. We are now done with the code. So save it in .sol format with CMD/CTRL + S

### How to deploy:
1. Go to https://remix.ethereum.org/
2. Follow Below Steps:![image](https://user-images.githubusercontent.com/78958410/131810450-c3cf33f6-4114-4253-bb0e-61655f2ee24e.png)
![image](https://user-images.githubusercontent.com/78958410/131810475-141ee161-a348-42fd-a92d-17e69bfd230f.png)
![image](https://user-images.githubusercontent.com/78958410/131810490-80ac5df6-2f38-453b-9451-54b0e56974b7.png)
![image](https://user-images.githubusercontent.com/78958410/131810526-49734f9d-f3c4-4d0d-902f-95eb144043cb.png)
3. After clicking you will be pop-uped for conferming a transaction, once it is completed you will be pop-uped for conferming another transaction. Once it is confirmed, your token is now created and the contract address will be shown here:![image](https://user-images.githubusercontent.com/78958410/131810740-1e68ab98-e5f9-4cc7-a343-6e5a0b533a50.png)
Copy the contract address by clicking the copy icon (marked with the circle)

### How To Verify the Token On BSCSCAN:
1. Go to https://bscscan.com and search the contract address.
2. Click Contract Button: ![image](https://user-images.githubusercontent.com/78958410/131810871-d32aa98d-9d11-45e1-99cf-6ce98293b3de.png)
3. Then click " Verify and Publish"
4. Then set up like below and click "Continue":<img width="755" alt="Screenshot 2021-09-02 at 1 50 52 PM" src="https://user-images.githubusercontent.com/78958410/131811247-03b12a75-b11f-4f41-8000-415779866e68.png">
5. Then: ![image](https://user-images.githubusercontent.com/78958410/131811308-0e56cfd4-3939-4703-9bd0-55d03daca6d6.png)
6. Now, click "Contract Library Address"![image](https://user-images.githubusercontent.com/78958410/131811366-1f7a8fd9-b3b3-43a9-bde0-e53a8f81ec31.png)
7. Once it expands, do the same as the picture:![image](https://user-images.githubusercontent.com/78958410/131811410-c160bbc8-73d5-40e9-b9b7-570d3b82345f.png)![image](https://user-images.githubusercontent.com/78958410/131811558-7d7c5962-f861-4b1f-8118-819fceb4eac3.png)
8. Now, click "Verify and Publish" and you are done now 😃

### If you face any errors, kindly message me with the screenshots so I can help you to fix them.

