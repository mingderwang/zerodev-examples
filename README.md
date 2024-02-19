# ZeroDev Examples

## Setup and Installation

Follow these steps to get this project up and running on your local machine:

1. **Clone the repository**

   Use the following command to clone this repository to your local machine:

   ```bash
   git clone git@github.com:zerodevapp/zerodev-examples.git
   ```

2. **Install dependencies**

   Navigate to the project directory and install the dependencies:

   ```bash
   cd zerodev-examples
   npm install
   ```

3. **Setup environment variables**

   Copy the `.env.example` file to `.env` and fill in the required values (most examples only require a few of these env vars)

   ```bash
    cp .env.example .env
    ```

4. **Run the script**

   Run the script using the following command:

   ```bash
   npx ts-node create-account/with-preset.ts
   ```

   Run tutorial on Mumbai

   ```bash
➜  zerodev-examples git:(main) ✗ yarn tutorial
yarn run v1.22.21
$ npx ts-node tutorial/completed.ts
My account: 0xB09b0cD91c70F08019F90566b9bd150Eb982A89C
Submitted UserOp: 0xe6ad530fea68271e94b45bb4cbff06bd4e40e1a8614e3a07117750de9a81fbec
UserOp confirmed: 0xe6ad530fea68271e94b45bb4cbff06bd4e40e1a8614e3a07117750de9a81fbec
NFT balance: 1
✨  Done in 28.34s.
```

   Check UserOp on Explorer [https://jiffyscan.xyz/userOpHash/0xe6ad530fea68271e94b45bb4cbff06bd4e40e1a8614e3a07117750de9a81fbec?network=mumbai](https://jiffyscan.xyz/userOpHash/0xe6ad530fea68271e94b45bb4cbff06bd4e40e1a8614e3a07117750de9a81fbec?network=mumbai)
