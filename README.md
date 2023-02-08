# Concordium_T03
Donation dApp

# Concordium wallet address
3o6Vx8zqtZU7SCiX6T4pfEvqeuVa6DCD9jT9G8Xg4pXECLWy9s

# Explanation of the donation app
Donation app is an app that allows users from particular locations to donate to the contract. 

#  creating donation
Clicking on "Create Donation" will initialize the contract on the blockchain and creates a new contract index. 
parameters 
{
  donation_locations: ["CM", "IT", "DK", "GM"],
  end_time: 30/04/2023 01:00:00Z
}

# donating to the contract
Clicking on "Donate" will donate 0.0001 CCD to the contract. We provide the contract index and your location
parameter
index: 2834
donation_location: "CM"
# Get the results
Clicking on "Get Results" will get the time and the current balance in the contract and display it

# Closing a donation
Clicking on "Close donation" will set the state of donation to closed and also transfers all the balance in the contract to the owner.
Hence clicking on the "Get results" will return a 0 balance

# Opening a donation
Clicking on "Open donation" will set the state of donation to open

# Preview

