# Getting-Started

  - Clone the repository.
  - Create a GitHub OAuth app[ https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app ]  
  - set homepage url to http://localhost:3000 and callback url to http://localhost:3000/github/callback.
  - Check the npm versions required in the `package.json` file.
  - Run yarn install to build the dependencies.
  - Make .env file that has GITHUB_CLIENT_ID=client_id and GITHUB_CLIENT_SECRET=client_secret from the Github OAuth app.
  - Run `npm run start` to start the server.

# How to use

- Go to `http://localhost:3000` or `https://truefoundry-github_integration.herokuapp.com`.
- Click on `Create a Github repository`, authorize the app 
- this will create a repo with name `Bias-Variance-Tradeoff-app` by using the template present in `ayushsharma-crypto/Bias-Variance-Tradeoff`.

# Execution flow

You click on  `Create a Github repository` -> It takes you to the authorization page -> Repository with sample files are created.