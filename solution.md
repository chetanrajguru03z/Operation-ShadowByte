# ShadowByte's Last Message - Solution

## Step 1: Analyze the Evidence

The provided file appears to be a normal image.

File:
shadowbyte_evidence.png

## Step 2: Search for Hidden Content

Use:
Select-String -Path .\shadowbyte_evidence.png -Pattern "R0NT"

This reveals a Base64 encoded string hidden inside the image.

## Step 3: Extract Encoded Data

Recovered string:

R0NTe1NoYWRvd0J5dGVfTGFzdF9NZXNzYWdlfQ==

## Step 4: Decode the String

Use CyberChef or any Base64 decoder.

## Step 5: Recover the Flag

Flag:

GCS{ShadowByte_Last_Message}
