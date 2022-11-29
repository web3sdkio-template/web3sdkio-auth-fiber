## Getting Started

This example demonstrates how to use web3sdkio Auth with a fiber backend and react frontend.

To run this project, you need will first need to install the dependencies for the client and server with the following commands:

Then run one of the following commands to install the JS dependencies into the `client` folder:

```bash
cd client && npm install
# or
cd client && yarn install
```

We also need to install the Go dependencies for our backend, which we can do with the following command:

```bash
cd server && go get
```

Next, you need to create a `.env` file in the `server` folder and add the `ADMIN_PRIVATE_KEY` variable to it (similar to how it is in the `/server/.env.example` file) with the private key of the wallet you want to use as the admin wallet to generate and verify payloads. Your file should use something like the following:

```/server/.env
ADMIN_PRIVATE_KEY=...
```

Now, we need to run the frontend and the backend separately.

We can startup our frontend by running the following command in the root of the `login-with-next-fiber` directory:

```bash
make web
```

Finally, we can startup the backend in a separate terminal window by running the following command:

```bash
make server
```

Now, the demo should be ready to use - and we can navigate to [`http://localhost:3000`](http://localhost:3000) to try it out.


## Learn More

To learn more about web3sdkio, take a look at the following resources:

- [web3sdkio Auth Documentation](https://docs.web3sdk.io/auth) - learn about web3sdkio Auth.
- [web3sdkio React Documentation](https://docs.web3sdk.io/react) - learn about our React SDK.
- [web3sdkio Portal](https://docs.web3sdk.io) - check our guides and development resources.
  
You can check out [the web3sdkio GitHub organization](https://github.com/web3sdkio) - your feedback and contributions are welcome!

## Join our Discord!

For any questions, suggestions, join our discord at [https://discord.gg/web3sdkio](https://discord.gg/web3sdkio).