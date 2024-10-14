
# unichain-node


### System Requirements

| **Requirement**       | **Specification** |
|-----------------------|-------------------|
| **CPU**               | 4 Cores           |
| **RAM**               | 6 GB or more      |
| **SSD**               | 150 GB or more    |
| **Operating System**  | Ubuntu 22.04      |

## Repository Setup 

```
wget https://raw.githubusercontent.com/furidngrt/Unichain-Node/refs/heads/master/unichain.sh
chmod +x unichain.sh
./unichain.sh
```

*After downloading the necessary applications, we will download and edit the Unichain node files.*

```
git clone https://github.com/Uniswap/unichain-node
cd unichain-node

nano .env.sepolia
```

*Here, we will change the places you see on the screen; to get the endpoint URL, you need to find the URL as shown below.*

*Site: https://drpc.org/*

<img width="870" alt="Screenshot at Oct 11 16-45-00" src="https://github.com/user-attachments/assets/a3944772-45c9-4544-bf19-e2d3b5a289c1">


*After entering the information, we exit with Ctrl + X, then Y, and finally Enter.*

*To start the node, we run the following command.*

```
docker compose up -d 
```

*Done*
