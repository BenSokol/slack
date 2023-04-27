# slack-webhook

Sends a message to a specified slack webhook

Install
```console
# Add source to APT
echo deb [signed-by=/etc/apt/keyrings/bensokol.gpg] https://deb.bensokol.com public main | sudo tee /etc/apt/sources.list.d/deb.bensokol.com.list

# Add key
curl https://deb.bensokol.com/public.key | sudo gpg --dearmor -o /etc/apt/keyrings/bensokol.gpg

# Update and install
sudo apt update
sudo apt install python3-slackwebhook
```
