# GenLayer Zero to Hero: My First Intelligent Contract

**Builder Contribution – Official Introductory Tutorial**

## Overview
Completed the full "From Zero to GenLayer" tutorial. I set up the environment from scratch, created a wallet, funded it, wrote my first Intelligent Contract, deployed it on Bradbury Testnet, and interacted with it.

## Wallet
**Address:** `0x6db41d61801c8e38304e041bf248d97b70668f3e`

## Commands I Used

```bash
# Set network
genlayer network set testnet-bradbury

# Create wallet
genlayer account create --name default

# Create project
genlayer new my-first-contract
cd my-first-contract

# Deploy contract
genlayer deploy --contract contracts/hello_world.py --args "Hello from Bradbury!"

# Interact
genlayer call YOUR_CONTRACT_ADDRESS get_greeting
genlayer write YOUR_CONTRACT_ADDRESS set_greeting --args "I just deployed on GenLayer!"
