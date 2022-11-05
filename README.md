# spring-examples

Spring Vault
------------------------

1. Install and Launch Hashicorp vault

  https://developer.hashicorp.com/vault/downloads
  Run Vault Server in development mode
  https://developer.hashicorp.com/vault/docs/get-started/developer-qs
  
  Use following command to run vault server
  
  vault server -dev -dev-root-token-id="dev-only-token"
  
  
  The -dev-root-token-id flag for dev servers tells the Vault server to allow full root access to anyone who presents a token with the specified value (in this case "dev-only-token").
  
  Vault is now listening over HTTP on port 8200. With all the setup out of the way, it's time to get coding!
  
  ![image](https://user-images.githubusercontent.com/117335998/200101073-f0a4249b-a9a3-4de9-808f-f78fe71b6bc4.png)

  
