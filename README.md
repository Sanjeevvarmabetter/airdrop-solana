# airdrop-solana

This project demonstrates a simple Solana Airdrop application, allowing users to initiate an airdrop by providing a Solana public key.

## How to Use

1. **Clone this repository:**

    ```bash
    git clone https://github.com/your-username/solana-airdrop.git
    cd solana-airdrop
    ```

2. **Download the Solana web3.js library** and save it as `web3.js` in the project folder. You can download it from [unpkg.com](https://unpkg.com/@solana/web3.js@latest/lib/index.iife.min.js).

3. **Open the `index.html` file** in your preferred text editor and update the script import to use the locally hosted `web3.js` file:

    ```html
    <script src="web3.js"></script>
    <script src="main.js" type="module"></script>
    ```

4. **Run the application:**

    Open `index.html` in a web browser.

## Functionality

- The `submitForm` function in `main.js` uses the Solana web3.js library to request an airdrop for the specified Solana public key.

## Technologies Used

- [Solana Web3.js](https://github.com/solana-labs/solana-web3.js)
- HTML

## Contributions

Contributions are welcome! Please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

